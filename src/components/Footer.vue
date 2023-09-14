<template>
  <footer class="copyright">
    <p>Copyright © 2023 <span>Jerry</span> All Rights Reservea</p>
    ICP备案号  粤ICP备2023030454号
    <div class="copyright-iframe" style="margin-top: 10px">
      <iframe name="weather_inc" src="http://i.tianqi.com/?c=code&amp;id=1" height="25" frameborder="0" marginwidth="0"
        marginheight="0" scrolling="no" style="max-width: 1200px"></iframe>
    </div>
  </footer>
</template>

<style lang="less" scoped>
.copyright {
  padding: 20px 0;
  width: 100%;
  text-align: center;
  font-size: 0.8rem;
  color: #dbd9d9;

  .copyright-iframe {
    display: flex;
    justify-content: center;

    iframe {
      width: 500px;
    }
  }

  span {
    color: #ef652a80;
  }
}
</style>