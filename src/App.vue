<template>
  <div id="app">
    <div class="content">
      <h1>退讚，同場加映韓導</h1>
      <p>邀請朋友共襄盛舉吧 👎</p>
    </div>
    <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FDoctorKoWJ&tabs&width=340&height=214&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId" width="340" height="214" style="border:none;overflow:hidden"
      scrolling="no" frameborder="0" allowTransparency="true" allow="encrypted-media"></iframe>
    <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Ftwherohan%2F&tabs&width=340&height=214&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId" width="340" height="214" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allow="encrypted-media"></iframe>
    <div class="footer">
      <p>本頁由 <a target="_blank" href="https://github.com/WeiChiaChang">WeiChiaChang</a> 製作。</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
html, body {
  padding: 0;
  margin: 0;
}

body {
  background-image: url(https://upload.cc/i1/2019/09/07/9pZ7L8.gif);
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  margin: auto;
  min-width: 50%;
  min-height: 50%;
  opacity: 1;
  width: 100%;
  max-width: 100%;
  height: auto;
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.content {
  color: white;
  text-align: center;
}

.footer {
  color: white;
  font-size: .75rem;
}

.footer a {
  text-decoration: none;
  color: white;
}
</style>
