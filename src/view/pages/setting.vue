<template>
  <div class="setting">
    <el-container>
      <el-header>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <h3>AI百晓生-附属版</h3>
          </div>
        </transition>
      </el-header>
      <el-main>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <span>
              一站式人工智能AI工具，润色文章、修正语法、生成文案、写代码、聊天，绘图，全方位提升网页效率！
            </span>
            <div>
              <a href="http://wj.lzlspyxgs.asia/">轻工具资源站</a>
            </div>
            <div>
              <h3>愿半生编码，如一生老友</h3>
            </div>
            <div>
              <img src="http://aai.yjie.fun/ds/img/alipay.png" width="300px" height="300px"/>
              <img src="http://aai.yjie.fun/ds/img/wxpay.png" width="300px" height="300px"/>
            </div>
          </div>
        </transition>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      show: false,
    };
  },
  mounted() {
    this.show = true;
  },
};
</script>

<style>
  .transition-box {
    text-align: center;
    margin-top: 5%;
    color: #F2F6FC;
    font-size: 30px;
  }
  h1 {
    color: aliceblue;
    font-size: 80px;
  }
  a {
    text-decoration: none;
    color: #67C23A;
  }
</style>
