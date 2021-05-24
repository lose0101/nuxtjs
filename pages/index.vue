<template>
<div>
<h1>
娜娜🐷老婆，老公超级爱你😘
</h1>
<div v-for="(x,index) in arr" :key="index"  style="text-align:center;" class="run">❤️</div>
</div>
</template>
<script>
export default{
    data(){
        return{
            arr:[]
        }
    },
    mounted(){
        setInterval(()=>{
            this.arr.push(1)
        },300)
    }
}
</scipt>
<style>
.run{
animation:run all .5s infinite;
}

@keyframes run{
    0%{font-size:50px;}
    100%{font-size:150px;}
}
</style>
