<template>
<div>
<h1>
娜娜🐷老婆，老公超级爱你😘
<span>老婆{{arr.length%2===0?'是':'不是'}}傻子
{{f?'🤣🥰'.repeat(10):'😎'}}
</h1>
<div v-if="w" style="color:red">等待10秒有奇迹😂</div>
<div style="text-align:center;" class="run">
<span v-for="(x,index) in arr" :key="index">❤️</span>
</div>
</div>
</template>
<script>
export default{
    data(){
        return{
            arr:[],
            f:false,
            w:false,
        }
    },
    mounted(){
        let s=10
        let i=setInterval(()=>{
            this.arr.push(1)
            s--
            if(s<=0){
                clearInterval(i)
                setTimeout(()=>{
                    this.arr.push(1)
                    this.f=true
                },10000)
                this.w=true
            }
        },1000)
    }
}
</script>
<style>
.run{
animation:run .5s infinite;
}

@keyframes run{
    0%{font-size:50px;}
    100%{font-size:60px;}
}
</style>
