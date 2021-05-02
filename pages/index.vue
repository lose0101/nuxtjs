<template>
<div>hello world，尚硅6
<el-button>ok</el-button>
{{msg}}
<el-input v-model="msg" placeholder="请输入内容"></el-input>
{{number}}
<el-slider v-model="number"></el-slider>
</div>
</template>
<script>
export default{
    data(){
        return {
            msg:'hello world',
            number:5,
        }
    }
}
</script>
