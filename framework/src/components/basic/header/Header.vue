<template>
  <view class="header x-ai-flex-row x-ai-items-center x-ai-justify-between">
    <view class="x-ai-flex-row x-ai-items-center left-section">
      <image class="logo" src="@/assets/images/logo.png" />
      <text class="app-name">AI视频换脸</text>
    </view>
    <view class="x-ai-flex-row x-ai-items-center right-section">
      <view class="user-info x-ai-flex-row x-ai-items-center" @click="handleUserClick">
        <image class="avatar" :src="userAvatar" />
        <text class="username">{{ username }}</text>
      </view>
    </view>
  </view>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Header',
  props: {
    username: {
      type: String,
      default: '未登录'
    },
    userAvatar: {
      type: String,
      default: ''
    }
  },
  setup(props, { emit }) {
    const handleUserClick = () => {
      emit('user-click');
    };

    return {
      handleUserClick
    };
  }
});
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  height: 60px;
  background-color: #171824;
  padding: 0 24px;
  box-shadow: 0 1px 0 #242632;

  .left-section {
    .logo {
      width: 32px;
      height: 32px;
    }

    .app-name {
      font-size: 18px;
      font-weight: 500;
      color: #ffffff;
      margin-left: 12px;
    }
  }

  .right-section {
    .user-info {
      cursor: pointer;
      padding: 6px 12px;
      border-radius: 4px;
      transition: background-color 0.3s;

      &:hover {
        background-color: rgba(255, 255, 255, 0.05);
      }

      .avatar {
        width: 32px;
        height: 32px;
        border-radius: 16px;
      }

      .username {
        font-size: 14px;
        color: #ffffff;
        margin-left: 8px;
        opacity: 0.8;
      }
    }
  }
}
</style>