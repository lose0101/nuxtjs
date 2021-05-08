<template>
<div style="padding:10px">
<h1>浏览器编程教学</h1>
<h4>作者: 卷毛猪</h4>
<h2>vue文件描述</h2>
<h4 @click="to('/0')">0.vue ---- 在浏览器上显示 你好世界</h4>
<h4 @click="to('/1')">1.vue ---- 改变 你好世界 的颜色</h4>
<h4 @click="to('/2')">2.vue ---- 在浏览器上显示一个ok按钮</h4>
<h4 @click="to('/3')">3.vue ---- 点击ok按钮,弹出窗口并显示你好世界</h4>
<h4 @click="to('/4')">4.vue ---- 点击ok按钮,把你好世界改为你好中国</h4>
<h4 @click="to('/5')">5.vue ---- 在浏览器上显示一张图片</h4>
<h4 @click="to('/6')">6.vue ---- 在浏览器上显示一个视频</h4>
<h4 @click="to('/7')">7.vue ---- 在浏览器上显示一句话今天天气真好和一个视频，要求今天天气真好和视频为上下结构显示</h4>
<h2>到这就是学完了</h2>
</div>
</template>
<script>
export default{
    methods:{
      to(url){
        this.$router.push(url)
      }
    }
}
</script>
<style scoped>
h4{line-height:150%;}
</style>
