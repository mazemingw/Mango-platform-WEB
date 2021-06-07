<template>
  <div class="page-container" style="width:99%;margin-top:15px;">
    <el-carousel :interval="3000" type="card" height="450px" class="carousel">
      <el-carousel-item class="carousel-item-intro">
        <h2>项目介绍</h2>
        <ul>
          <li>基于 Spring Boot、Spring Cloud、Vue、Element 的 Java EE 快速开发平台</li>
          <li>虽然吧还有bug，但是</li>
          <li>不修了</li>
        </ul>
        <div><img src="@/assets/logo.png" style="width:120px;height:120px;padding-top:15px;" /></div>
      </el-carousel-item>

        <el-carousel-item class="carousel-item-intro">
          <h2>DESIGN BY MA</h2>
          <li>Powered By Vue.js / Spring Admin / ElementUI</li>
          <br>
           <br> <br>
            <br>
        <div><img src="@/assets/user.png" style="width:120px;height:120px;padding-top:15px;" /></div>
      </el-carousel-item>

      <el-carousel-item class="carousel-item-func">
        <h2>功能计划</h2>
        <ul>
          <li>✔ 系统登录</li>
          <li>✔ 用户管理：增删改查 ■■■■■</li>
          <li>✔ 机构管理：增删改查 ■■■■■</li>
          <li>✔ 角色管理：增删改查 ■■■■■</li>
          <li>✔ 菜单管理：增删改查 ■■■■■</li>
          <li>✔ 系统日志：记录用户操作日志，查看系统执行日志记录</li>
          <li>✔ 数据监控：定制Druid信息，提供简洁有效的SQL监控</li>
          <li>✔ 聚合文档： ■■■■■</li>
          <li>× 备份还原： 前端未实现 ▢▢▢▢▢</li>
          <li>✔ 主题切换： 无法储存颜色设定 ■■▢▢▢</li>
          <li>✔ 服务治理：集成Spring Cloud，实现服务治理</li>
          <li>✔ 服务监控：集成Spring Boot Admin，实现微服务监控</li>
          <li></li>
        </ul>
      </el-carousel-item>
      <el-carousel-item class="carousel-item-env">
        <h2>运行环境</h2>
        <ul>
          <li>IDE：Eclipse  JDK：1.8-1.9</li>
          <li>请勿轻易在8G运存以下电脑调试，否则将产生内存交换</li>
        </ul>
        <h2>技术选型</h2>
        <ul>
          <li>核心框架：Spring Boot。  服务治理：Spring Cloud。</li>
          <li>视图框架：Spring MVC。   持久层框架：MyBatis。</li>
          <li>数据库连接池：阿里Druid。    安全框架：Shiro。</li>
          <li>前端框架：Vue2。       页面组件：饿了么UI。</li>
          <li>状态管理：Vuex2。      后台交互：axios。</li>
          <li>...</li>
        </ul>
      </el-carousel-item>
    </el-carousel>
  </div>
</template>

<script>
  export default {
    components:{
    },
    methods :{
    }
  }
</script>

<style>
  .carousel {
    padding-left: 20px;
    padding-right: 20px;
    margin-right: 20px;
  }
  .carousel h2 {
    color: #475669;
    font-size: 22px;
    opacity: 1.75;
    line-height: 100px;
    margin: 0;
  }
  .carousel ul {
    color: #475669;
    font-size: 15px;
    opacity: 1.75;
    line-height: 40px;
    margin: 0;
  }
  .carousel-item-intro h2 {
    color: #ffffff;
    font-size: 22px;
    opacity: 1.75;
    line-height: 80px;
    margin: 0;
  }
  .carousel-item-intro ul {
    color: #ffffff;
    font-size: 15px;
    opacity: 1.75;
    line-height: 65px;
    padding: 5px;
    margin: 0;
  }
   .carousel-item-func h2 {
    color: #3f393b;
    font-size: 22px;
    opacity: 1.75;
    line-height: 50px;
    margin: 0;
  }
  .carousel-item-func ul {
    color: #3f393b;
    font-size: 15px;
    opacity: 1.75;
    line-height: 30px;
    text-align: left;
    padding-left: 90px;
    margin: 0;
  }
  .carousel-item-env h2 {
    color: #475669;
    font-size: 22px;
    opacity: 1.75;
    line-height: 50px;
    margin: 0;
  }
  .carousel-item-env ul {
    color: #475669;
    font-size: 15px;
    opacity: 1.75;
    line-height: 35px;
    text-align: left;
    padding-left: 110px;
    margin: 0;
  }
  .carousel-item-intro {
    background-color: #19aaaf73;
    -webkit-border-radius: 25px;
    border-radius: 25px;
    -moz-border-radius: 15px;
    background-clip: padding-box;
    box-shadow: 0 0 25px #a3b3b965;
  }
  .carousel-item-func {
    background-color: #19aaaf73;
    -webkit-border-radius: 25px;
    border-radius: 25px;
    -moz-border-radius: 15px;
    background-clip: padding-box;
    box-shadow: 0 0 25px #a3b3b965;
  }
  .carousel-item-env {
    background-color: #19aaaf73;
    -webkit-border-radius: 25px;
    border-radius: 25px;
    -moz-border-radius: 15px;
    background-clip: padding-box;
    box-shadow: 0 0 25px #a3b3b965;
  }
  .carousel-item-intro {
    background-color: #7C4DFF;
  }
  .carousel-item-func {
    background-color: #4CAF50;
  }
  .carousel-item-env {
    background-color: #03A9F4;
  }
</style>