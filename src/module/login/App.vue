<template>
  <div>
     <v-header></v-header>
    <div class="tab">
      <div class="tab-item"><router-link to="/goods">商品</router-link></div>
      <div class="tab-item"><router-link to="/goods">评论</router-link> </div>
      <div class="tab-item"><router-link to="/goods">商家</router-link></div>
    </div>
    <router-view></router-view>
    <p>啊啊啊</p>
    <div>
      222222222222222222222
      <div class="tab">
        <div class="tab-item"><router-link to="/goods">商品</router-link></div>
        <div class="tab-item"><router-link to="/goods">评论</router-link> </div>
        <div class="tab-item"><router-link to="/goods">商家</router-link></div>
      </div>
      <router-view></router-view>
      <p>啊啊啊</p>
    </div>
  </div>
</template>

<script>
  import header from '../../components/base/header/header'
  export default {
    components: {
      'v-header': header
    }
  }
</script>

<style  lang="scss" rel="stylesheat/sass">
  html, body, div, span, applet, object, iframe,
  h1, h2, h3, h4, h5, h6, p, blockquote, pre,
  a, abbr, acronym, address, big, cite, code,
  del, dfn, em, img, ins, kbd, q, s, samp,
  small, strike, strong, sub, sup, tt, var,
  b, u, i, center,
  dl, dt, dd, ol, ul, li,
  fieldset, form, label, legend,
  table, caption, tbody, tfoot, thead, tr, th, td,
  article, aside, canvas, details, embed,
  figure, figcaption, footer, header, hgroup,
  menu, nav, output, ruby, section, summary,
  time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
  }
  /* HTML5 display-role reset for older browsers */
  article, aside, details, figcaption, figure,
  footer, header, hgroup, menu, nav, section {
    display: block;
  }
  body {
    line-height: 1;
  }
  ol, ul {
    list-style: none;
  }
  blockquote, q {
    quotes: none;
  }
  blockquote:before, blockquote:after,
  q:before, q:after {
    content: '';
    content: none;
  }
  table {
    border-collapse: collapse;
    border-spacing: 0;
  }
  a {
    text-decoration:none;
    out-line: none;
    color: #000000;
  }
  /* 以上是rest，下面是个人样式 */

  .tab{
    display: flex;
    width: 100%;
    height: 40px;
    line-height: 40px;
  }
  .tab-item{
    flex: 1;
    text-align: center;
  }
</style>
