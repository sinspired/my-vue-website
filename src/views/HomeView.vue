<!-- <script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template> -->
<template>
  <div class="home">
    <h1>欢迎来到我的个人网站</h1>
    <Card title="近期工作计划" content="完成项目A，开始项目B的调研..." />
    <Card title="近期健身计划" content="每天跑步5公里，周三和周六进行力量训练..." />
    <Card title="近期旅游计划" content="计划在下个月去云南旅游，体验当地文化..." />
  </div>
</template>

<script>
import Card from '../components/Card.vue';

export default {
  name: 'HomeView',
  components: {
    Card
  }
}
</script>

<style scoped>
.home {
  text-align: center;
}
</style>
