<template>
  <footer class="page-footer teal lighten-2">
    <div class="container">
      <div class="row">
        <div class="col l6 s12">
          <h5 class="white-text">鸣谢</h5>
          <p class="grey-text text-lighten-5">感谢北邮人提供视频源</p>
        </div>
        <div class="col l4 offset-l2 s12">
          <h5 class="white-text">联系我们</h5>
          <ul class="zmdi-hc-ul">
            <li><a class="grey-text text-lighten-3" target="_blank" href="https://github.com/huiyiqun/iptv"><i class="zmdi zmdi-github zmdi-hc-li"></i>Github</a></li>
            <li><a class="grey-text text-lighten-3" target="_blank" href="mailto:its@tsinghua.edu.cn"><i class="zmdi zmdi-email zmdi-hc-li"></i>Email</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer-copyright">
      <div class="container">
        Powered by Tsinghua University © 2017
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'iptv-footer',
};
</script>

<style>
div#body {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}

main {
  flex: 1 0 auto;
}
</style>
