<template>
  <view class="navbar x-ai-flex-row x-ai-items-center">
    <view class="x-ai-flex-row x-ai-items-center left-section" @click="handleBack" v-if="showBack">
      <image class="back-icon" src="@/assets/images/icons/back.png" />
      <text class="back-text">返回</text>
    </view>
    <view class="title-section x-ai-flex-row x-ai-justify-center x-ai-items-center">
      <text class="title">{{ title }}</text>
    </view>
    <view class="right-section x-ai-flex-row x-ai-items-center" v-if="$slots.right">
      <slot name="right"></slot>
    </view>
  </view>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Navbar',
  props: {
    title: {
      type: String,
      default: ''
    },
    showBack: {
      type: Boolean,
      default: true
    }
  },
  setup(props, { emit }) {
    const handleBack = () => {
      emit('back');
      uni.navigateBack({
        delta: 1
      });
    };

    return {
      handleBack
    };
  }
});
</script>

<style lang="scss" scoped>
.navbar {
  width: 100%;
  height: 44px;
  background-color: #171824;
  padding: 0 16px;
  position: relative;

  .left-section {
    position: absolute;
    left: 16px;
    z-index: 1;

    .back-icon {
      width: 24px;
      height: 24px;
    }

    .back-text {
      font-size: 16px;
      color: #ffffff;
      margin-left: 4px;
    }
  }

  .title-section {
    width: 100%;
    position: absolute;
    left: 0;

    .title {
      font-size: 18px;
      font-weight: 500;
      color: #ffffff;
    }
  }

  .right-section {
    position: absolute;
    right: 16px;
    z-index: 1;
  }
}
</style>