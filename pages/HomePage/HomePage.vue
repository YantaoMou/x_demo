<template>
  <view class="x-ai-flex-col x-ai-relative page">
    <view class="x-ai-flex-col x-ai-justify-start x-ai-items-end x-ai-self-stretch text-wrapper">
      <text class="font text">登录 ｜ 注册</text>
    </view>
    <view class="x-ai-flex-col x-ai-items-center x-ai-self-end section_2">
      <text class="text_9">视频</text>
      <view class="x-ai-flex-col x-ai-justify-start x-ai-items-center text-wrapper_2 mt-251">
        <text class="text_10">登录/注册</text>
      </view>
    </view>
    <view class="x-ai-flex-col section pos">
      <view class="x-ai-flex-row x-ai-justify-center x-ai-relative group">
        <image class="image pos_2" src="../../assets/8c3431dba996a5d2dff8948999fbcf3c.png" />
        <image class="x-ai-self-start image_2" src="../../assets/6e6214e55ed9c931687e2a2c4332b40d.png" />
      </view>
      <view class="x-ai-flex-col group_2">
        <text class="x-ai-self-start font_2 text_2">探索</text>
        <view class="x-ai-flex-row x-ai-items-center x-ai-self-stretch section_3">
          <image class="image_3" src="../../assets/d535ab12aa855aaba1c5eb5616c73df6.png" />
          <text class="font text_3 ml-9">范例</text>
        </view>
        <view class="x-ai-flex-row x-ai-items-center x-ai-self-stretch group_3">
          <image class="image_4" src="../../assets/18144823abcbe13c67d3a6cb9ce856f6.png" />
          <text class="x-ai-ml-8 font text_2 text_4">教程</text>
        </view>
      </view>
      <view class="x-ai-flex-col group_4">
        <text class="x-ai-self-start font_2 text_2 text_5">创作</text>
        <view class="x-ai-mt-20 x-ai-flex-row x-ai-self-stretch group_5">
          <image class="image_5" src="../../assets/3c752b54e940f7b8a81387f9c58497e9.png" />
          <text class="font text_2 ml-9">视频换脸</text>
        </view>
      </view>
      <view class="x-ai-flex-col group_6">
        <text class="x-ai-self-start font_2 text_2 text_6">我的</text>
        <view class="x-ai-flex-row x-ai-items-center x-ai-self-stretch group_7">
          <image class="image_3" src="../../assets/e0c317b9ddff7b7384919e489173debd.png" />
          <text class="x-ai-ml-8 font text_2 text_7">会员中心</text>
        </view>
        <view class="x-ai-flex-row x-ai-items-center x-ai-self-stretch group_5 view">
          <image class="image_6" src="../../assets/2e3ea41c1a0a4329e96478b298622a76.png" />
          <text class="font text_2 text_8 ml-9">创作历史</text>
        </view>
      </view>
    </view>
  </view>
</template>

<script>
  export default {
    components: {},
    props: {},
    data() {
      return {};
    },

    methods: {},
  };
</script>

<style scoped lang="css">
  .mt-251 {
    margin-top: 15.69rem;
  }
  .ml-9 {
    margin-left: 0.56rem;
  }
  .page {
    padding-bottom: 2.5rem;
    background-color: #171824;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .text-wrapper {
    padding: 1.63rem 0;
    background-color: #171924;
    box-shadow: 0rem 0.063rem 0rem #242632;
  }
  .font {
    font-size: 1rem;
    font-family: PingFang SC;
    line-height: 0.93rem;
    color: #ffffff;
  }
  .text {
    margin-right: 1.88rem;
    line-height: 1rem;
    opacity: 0.6;
  }
  .section_2 {
    margin-right: 2.5rem;
    margin-top: 1.94rem;
    padding: 22.63rem 0 3.5rem;
    background-color: #191c2a;
    border-radius: 1.5rem;
    width: 69.25rem;
    border-left: solid 0.063rem #ffffff1a;
    border-right: solid 0.063rem #ffffff1a;
    border-top: solid 0.063rem #ffffff1a;
    border-bottom: solid 0.063rem #ffffff1a;
  }
  .text_9 {
    color: #ffffff;
    font-size: 6.25rem;
    font-family: PingFang SC;
    line-height: 5.83rem;
    letter-spacing: 1.25rem;
    opacity: 0.2;
  }
  .text-wrapper_2 {
    padding: 1.25rem 0;
    background-image: linear-gradient(180deg, #8358f0 0%, #5f45a0 100%);
    border-radius: 0.75rem;
    width: 27.75rem;
  }
  .text_10 {
    color: #dcceff;
    font-size: 1.13rem;
    font-family: PingFang SC;
    line-height: 1.05rem;
  }
  .section {
    padding: 0.88rem 1.25rem 31.38rem 1.5rem;
    background-color: #171924;
    box-shadow: 0.063rem 0rem 0rem #252733;
    width: 16.25rem;
  }
  .pos {
    position: absolute;
    left: 0;
    top: 0;
  }
  .group {
    padding: 0.88rem 1rem 0.38rem;
  }
  .image {
    width: 2.31rem;
    height: 2.31rem;
  }
  .pos_2 {
    position: absolute;
    left: 1.02rem;
    top: 50%;
    transform: translateY(-50%);
  }
  .image_2 {
    width: 5.5rem;
    height: 1.06rem;
  }
  .group_2 {
    margin-top: 3.25rem;
  }
  .font_2 {
    font-size: 0.88rem;
    font-family: PingFang SC;
    line-height: 0.8rem;
    color: #ffffff;
  }
  .text_2 {
    opacity: 0.5;
  }
  .section_3 {
    margin-top: 0.38rem;
    padding: 0.75rem 1rem;
    background-color: #b194f90f;
    border-radius: 0.5rem;
  }
  .image_3 {
    width: 1.25rem;
    height: 1.25rem;
  }
  .text_3 {
    margin-right: 7.75rem;
    color: #b194f9;
    line-height: 0.93rem;
  }
  .group_3 {
    padding: 0.75rem 1rem 0;
  }
  .image_4 {
    opacity: 0.5;
    width: 1.25rem;
    height: 1.25rem;
  }
  .text_4 {
    line-height: 0.92rem;
  }
  .group_4 {
    margin-top: 3.5rem;
  }
  .text_5 {
    line-height: 0.81rem;
  }
  .group_5 {
    padding: 0 1.13rem;
  }
  .image_5 {
    opacity: 0.5;
    width: 1.13rem;
    height: 1.06rem;
  }
  .group_6 {
    margin-top: 3.63rem;
  }
  .text_6 {
    line-height: 0.79rem;
  }
  .group_7 {
    margin-top: 1.13rem;
    padding: 0 1rem;
  }
  .text_7 {
    line-height: 0.93rem;
  }
  .view {
    margin-top: 1.63rem;
  }
  .image_6 {
    opacity: 0.5;
    width: 1.13rem;
    height: 1.13rem;
  }
  .text_8 {
    line-height: 0.92rem;
  }
</style>