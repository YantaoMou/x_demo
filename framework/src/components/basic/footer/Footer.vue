<template>
  <view class="footer x-ai-flex-row x-ai-items-center x-ai-justify-between">
    <view class="left-section">
      <text class="copyright">© 2024 AI视频换脸. All rights reserved.</text>
    </view>
    <view class="right-section x-ai-flex-row x-ai-items-center">
      <text class="link" @click="handlePrivacyClick">隐私政策</text>
      <text class="separator">|</text>
      <text class="link" @click="handleTermsClick">服务条款</text>
    </view>
  </view>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Footer',
  setup(props, { emit }) {
    const handlePrivacyClick = () => {
      emit('privacy-click');
    };

    const handleTermsClick = () => {
      emit('terms-click');
    };

    return {
      handlePrivacyClick,
      handleTermsClick
    };
  }
});
</script>

<style lang="scss" scoped>
.footer {
  width: 100%;
  height: 60px;
  background-color: #171824;
  padding: 0 24px;
  border-top: 1px solid #242632;

  .copyright {
    font-size: 14px;
    color: #ffffff;
    opacity: 0.6;
  }

  .right-section {
    .link {
      font-size: 14px;
      color: #ffffff;
      opacity: 0.8;
      cursor: pointer;
      transition: opacity 0.3s;

      &:hover {
        opacity: 1;
      }
    }

    .separator {
      margin: 0 12px;
      color: #ffffff;
      opacity: 0.3;
    }
  }
}
</style>