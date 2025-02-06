<script>
  export default {
    onLaunch: function () {
      console.log('App Launch');
    },
    onShow: function () {
      console.log('App Show');
    },
    onHide: function () {
      console.log('App Hide');
    },
  };
</script>

<style>
    /************************************************************
  ** 请将全局样式拷贝到项目的全局 CSS 文件或者当前页面的顶部 **
  ** 否则页面将无法正常显示                                  **
  ************************************************************/

  html {
    font-size: 16px;
  }

  body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans',
      'Droid Sans', 'Helvetica Neue', 'Microsoft Yahei', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  view,
  image,
  text {
    box-sizing: border-box;
    flex-shrink: 0;
  }

  #app {
    width: 100vw;
    height: 100vh;
  }
	/* #ifdef H5 */
	uni-page-head {
	  display: none;
	}
	/* #endif */
  .x-ai-flex-row {
    display: flex;
    flex-direction: row;
  }

  .x-ai-flex-col {
    display: flex;
    flex-direction: column;
  }

  .x-ai-justify-start {
    justify-content: flex-start;
  }

  .x-ai-justify-end {
    justify-content: flex-end;
  }

  .x-ai-justify-center {
    justify-content: center;
  }

  .x-ai-justify-between {
    justify-content: space-between;
  }

  .x-ai-justify-around {
    justify-content: space-around;
  }

  .x-ai-justify-evenly {
    justify-content: space-evenly;
  }

  .x-ai-items-start {
    align-items: flex-start;
  }

  .x-ai-items-end {
    align-items: flex-end;
  }

  .x-ai-items-center {
    align-items: center;
  }

  .x-ai-items-baseline {
    align-items: baseline;
  }

  .x-ai-items-stretch {
    align-items: stretch;
  }

  .x-ai-self-start {
    align-self: flex-start;
  }

  .x-ai-self-end {
    align-self: flex-end;
  }

  .x-ai-self-center {
    align-self: center;
  }

  .x-ai-self-baseline {
    align-self: baseline;
  }

  .x-ai-self-stretch {
    align-self: stretch;
  }

  .x-ai-flex-1 {
    flex: 1 1 0%;
  }

  .x-ai-flex-auto {
    flex: 1 1 auto;
  }

  .x-ai-grow {
    flex-grow: 1;
  }

  .x-ai-grow-0 {
    flex-grow: 0;
  }

  .x-ai-shrink {
    flex-shrink: 1;
  }

  .x-ai-shrink-0 {
    flex-shrink: 0;
  }

  .x-ai-relative {
    position: relative;
  }

  .x-ai-ml-2 {
    margin-left: 0.13rem;
  }

  .x-ai-mt-2 {
    margin-top: 0.13rem;
  }

  .x-ai-ml-4 {
    margin-left: 0.25rem;
  }

  .x-ai-mt-4 {
    margin-top: 0.25rem;
  }

  .x-ai-ml-6 {
    margin-left: 0.38rem;
  }

  .x-ai-mt-6 {
    margin-top: 0.38rem;
  }

  .x-ai-ml-8 {
    margin-left: 0.5rem;
  }

  .x-ai-mt-8 {
    margin-top: 0.5rem;
  }

  .x-ai-ml-10 {
    margin-left: 0.63rem;
  }

  .x-ai-mt-10 {
    margin-top: 0.63rem;
  }

  .x-ai-ml-12 {
    margin-left: 0.75rem;
  }

  .x-ai-mt-12 {
    margin-top: 0.75rem;
  }

  .x-ai-ml-14 {
    margin-left: 0.88rem;
  }

  .x-ai-mt-14 {
    margin-top: 0.88rem;
  }

  .x-ai-ml-16 {
    margin-left: 1rem;
  }

  .x-ai-mt-16 {
    margin-top: 1rem;
  }

  .x-ai-ml-18 {
    margin-left: 1.13rem;
  }

  .x-ai-mt-18 {
    margin-top: 1.13rem;
  }

  .x-ai-ml-20 {
    margin-left: 1.25rem;
  }

  .x-ai-mt-20 {
    margin-top: 1.25rem;
  }

  .x-ai-ml-22 {
    margin-left: 1.38rem;
  }

  .x-ai-mt-22 {
    margin-top: 1.38rem;
  }

  .x-ai-ml-24 {
    margin-left: 1.5rem;
  }

  .x-ai-mt-24 {
    margin-top: 1.5rem;
  }

  .x-ai-ml-26 {
    margin-left: 1.63rem;
  }

  .x-ai-mt-26 {
    margin-top: 1.63rem;
  }

  .x-ai-ml-28 {
    margin-left: 1.75rem;
  }

  .x-ai-mt-28 {
    margin-top: 1.75rem;
  }

  .x-ai-ml-30 {
    margin-left: 1.88rem;
  }

  .x-ai-mt-30 {
    margin-top: 1.88rem;
  }

  .x-ai-ml-32 {
    margin-left: 2rem;
  }

  .x-ai-mt-32 {
    margin-top: 2rem;
  }

  .x-ai-ml-34 {
    margin-left: 2.13rem;
  }

  .x-ai-mt-34 {
    margin-top: 2.13rem;
  }

  .x-ai-ml-36 {
    margin-left: 2.25rem;
  }

  .x-ai-mt-36 {
    margin-top: 2.25rem;
  }

  .x-ai-ml-38 {
    margin-left: 2.38rem;
  }

  .x-ai-mt-38 {
    margin-top: 2.38rem;
  }

  .x-ai-ml-40 {
    margin-left: 2.5rem;
  }

  .x-ai-mt-40 {
    margin-top: 2.5rem;
  }

  .x-ai-ml-42 {
    margin-left: 2.63rem;
  }

  .x-ai-mt-42 {
    margin-top: 2.63rem;
  }

  .x-ai-ml-44 {
    margin-left: 2.75rem;
  }

  .x-ai-mt-44 {
    margin-top: 2.75rem;
  }

  .x-ai-ml-46 {
    margin-left: 2.88rem;
  }

  .x-ai-mt-46 {
    margin-top: 2.88rem;
  }

  .x-ai-ml-48 {
    margin-left: 3rem;
  }

  .x-ai-mt-48 {
    margin-top: 3rem;
  }

  .x-ai-ml-50 {
    margin-left: 3.13rem;
  }

  .x-ai-mt-50 {
    margin-top: 3.13rem;
  }

  .x-ai-ml-52 {
    margin-left: 3.25rem;
  }

  .x-ai-mt-52 {
    margin-top: 3.25rem;
  }

  .x-ai-ml-54 {
    margin-left: 3.38rem;
  }

  .x-ai-mt-54 {
    margin-top: 3.38rem;
  }

  .x-ai-ml-56 {
    margin-left: 3.5rem;
  }

  .x-ai-mt-56 {
    margin-top: 3.5rem;
  }

  .x-ai-ml-58 {
    margin-left: 3.63rem;
  }

  .x-ai-mt-58 {
    margin-top: 3.63rem;
  }

  .x-ai-ml-60 {
    margin-left: 3.75rem;
  }

  .x-ai-mt-60 {
    margin-top: 3.75rem;
  }

  .x-ai-ml-62 {
    margin-left: 3.88rem;
  }

  .x-ai-mt-62 {
    margin-top: 3.88rem;
  }

  .x-ai-ml-64 {
    margin-left: 4rem;
  }

  .x-ai-mt-64 {
    margin-top: 4rem;
  }

  .x-ai-ml-66 {
    margin-left: 4.13rem;
  }

  .x-ai-mt-66 {
    margin-top: 4.13rem;
  }

  .x-ai-ml-68 {
    margin-left: 4.25rem;
  }

  .x-ai-mt-68 {
    margin-top: 4.25rem;
  }

  .x-ai-ml-70 {
    margin-left: 4.38rem;
  }

  .x-ai-mt-70 {
    margin-top: 4.38rem;
  }

  .x-ai-ml-72 {
    margin-left: 4.5rem;
  }

  .x-ai-mt-72 {
    margin-top: 4.5rem;
  }

  .x-ai-ml-74 {
    margin-left: 4.63rem;
  }

  .x-ai-mt-74 {
    margin-top: 4.63rem;
  }

  .x-ai-ml-76 {
    margin-left: 4.75rem;
  }

  .x-ai-mt-76 {
    margin-top: 4.75rem;
  }

  .x-ai-ml-78 {
    margin-left: 4.88rem;
  }

  .x-ai-mt-78 {
    margin-top: 4.88rem;
  }

  .x-ai-ml-80 {
    margin-left: 5rem;
  }

  .x-ai-mt-80 {
    margin-top: 5rem;
  }

  .x-ai-ml-82 {
    margin-left: 5.13rem;
  }

  .x-ai-mt-82 {
    margin-top: 5.13rem;
  }

  .x-ai-ml-84 {
    margin-left: 5.25rem;
  }

  .x-ai-mt-84 {
    margin-top: 5.25rem;
  }

  .x-ai-ml-86 {
    margin-left: 5.38rem;
  }

  .x-ai-mt-86 {
    margin-top: 5.38rem;
  }

  .x-ai-ml-88 {
    margin-left: 5.5rem;
  }

  .x-ai-mt-88 {
    margin-top: 5.5rem;
  }

  .x-ai-ml-90 {
    margin-left: 5.63rem;
  }

  .x-ai-mt-90 {
    margin-top: 5.63rem;
  }

  .x-ai-ml-92 {
    margin-left: 5.75rem;
  }

  .x-ai-mt-92 {
    margin-top: 5.75rem;
  }

  .x-ai-ml-94 {
    margin-left: 5.88rem;
  }

  .x-ai-mt-94 {
    margin-top: 5.88rem;
  }

  .x-ai-ml-96 {
    margin-left: 6rem;
  }

  .x-ai-mt-96 {
    margin-top: 6rem;
  }

  .x-ai-ml-98 {
    margin-left: 6.13rem;
  }

  .x-ai-mt-98 {
    margin-top: 6.13rem;
  }

  .x-ai-ml-100 {
    margin-left: 6.25rem;
  }

  .x-ai-mt-100 {
    margin-top: 6.25rem;
  }
</style>