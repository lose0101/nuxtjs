<template>
<div style="padding:10px">
<h1>《1分钟学会浏览器编程(2021年)》</h1>
<h4>作者:卷毛猪 开始写作日期:2021-5-8 完成写作日期:持续编写中...</h4>

<h2>一、疑惑解答</h2>
<h4>小黄 问: “浏览器编程能干什么？”</h4>
<h4>卷毛猪🐷 答：“能干好多有趣的事情，比如制作小游戏和挣钱。
<a href="https://nuxtjs-lose0101.vercel.app/03-%E8%B9%A6%E8%B9%A6%E8%B7%B3%E7%9F%B3%E5%A4%B4/%E8%B9%A6%E8%B9%A6%E8%B7%B3.html">
点击体验游戏</a>”</h4>
<h4>小明 问：“谁可以学会浏览器编程？”</h4>
<h4>卷毛猪🐷 答：“小学、初中、高中以上的同学都可以学会。”</h4>
<h4>小红 问：“学习编程难吗？”</h4>
<h4>卷毛猪🐷 答：“不难，编程就像写作文和画画一样简单，每节课都尽可能保证1分钟学完、1分钟后你自己都可以亲自做实验啦~”</h4>

<h2>二、训练场课程(0到7关)，点击下方关卡进入游戏</h2>
<div class="item">
<h4 @click="to('/0')">第0关 ---- 在浏览器上显示 你好世界</h4>
<h4 @click="to('/1')">第1关 ---- 改变 你好世界 的颜色</h4>
<h4 @click="to('/2')">第2关 ---- 在浏览器上显示一个ok按钮</h4>
<h4 @click="to('/3')">第3关 ---- 点击ok按钮,弹出窗口并显示你好世界</h4>
<h4 @click="to('/4')">第4关 ---- 点击ok按钮,把你好世界改为你好中国</h4>
<h4 @click="to('/5')">第5关 ---- 在浏览器上显示一张图片</h4>
<h4 @click="to('/6')">第6关 ---- 在浏览器上显示一个视频</h4>
<h4 @click="to('/7')">第7关 ---- 在浏览器上显示一句话今天天气真好和一个视频，要求今天天气真好和视频为上下结构显示</h4>
</div>

<h3>--------到这就是学完了，不明白的可以加我微信问哦～--------</h3>
<el-row style="text-align:center;">
<img style="width:80%;" src="卷毛猪.png">
</el-row>
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
.item{font-weight:normal;color:blue;}
</style>
