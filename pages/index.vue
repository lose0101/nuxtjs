<template>
<div>hello world，尚硅6
<el-button>ok</el-button>
{{msg}}
<el-input v-model="msg"></el-input>
{{number}}

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
