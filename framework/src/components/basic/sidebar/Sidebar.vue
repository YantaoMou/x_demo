<template>
  <view class="sidebar x-ai-flex-col">
    <view class="menu-section x-ai-flex-col">
      <view 
        v-for="(item, index) in menuItems" 
        :key="index"
        class="menu-item x-ai-flex-row x-ai-items-center"
        :class="{ 'active': activeIndex === index }"
        @click="handleMenuClick(index)"
      >
        <image class="menu-icon" :src="item.icon" />
        <text class="menu-text">{{ item.text }}</text>
      </view>
    </view>
  </view>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'Sidebar',
  props: {
    menuItems: {
      type: Array,
      default: () => []
    },
    defaultActive: {
      type: Number,
      default: 0
    }
  },
  setup(props, { emit }) {
    const activeIndex = ref(props.defaultActive);

    const handleMenuClick = (index: number) => {
      activeIndex.value = index;
      emit('menu-click', index);
    };

    return {
      activeIndex,
      handleMenuClick
    };
  }
});
</script>

<style lang="scss" scoped>
.sidebar {
  width: 240px;
  height: 100%;
  background-color: #171824;
  padding: 16px 0;

  .menu-section {
    width: 100%;
  }

  .menu-item {
    padding: 12px 24px;
    cursor: pointer;
    transition: background-color 0.3s;

    &:hover {
      background-color: rgba(255, 255, 255, 0.05);
    }

    &.active {
      background-color: rgba(255, 255, 255, 0.1);
    }

    .menu-icon {
      width: 24px;
      height: 24px;
      margin-right: 12px;
    }

    .menu-text {
      font-size: 16px;
      color: #ffffff;
      opacity: 0.8;
    }
  }
}
</style>