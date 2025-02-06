<template>
  <view class="logo x-ai-flex-row x-ai-items-center" @click="handleClick">
    <image class="logo-image" :src="src" />
    <text v-if="showText" class="logo-text">{{ text }}</text>
  </view>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Logo',
  props: {
    src: {
      type: String,
      required: true
    },
    text: {
      type: String,
      default: 'AI视频换脸'
    },
    showText: {
      type: Boolean,
      default: true
    }
  },
  setup(props, { emit }) {
    const handleClick = () => {
      emit('click');
    };

    return {
      handleClick
    };
  }
});
</script>

<style lang="scss" scoped>
.logo {
  cursor: pointer;
  
  .logo-image {
    width: 32px;
    height: 32px;
  }

  .logo-text {
    margin-left: 12px;
    font-size: 18px;
    font-weight: 500;
    color: #ffffff;
  }
}
</style>