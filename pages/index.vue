<template>
<div>
<div>
<button v-for="(x,index) in list" @click="c(index)>{{x}}</button>
</div>
<el-row v-if="index%2==0">
<el-col :span="6" style="background:red">
a
</el-col>
<el-col :span="18" style="background:green">
b
</el-col>
</el-row>
<el-row v-else>
<el-col :span="18" style="background:green">
b
</el-col>
<el-col :span="6" style="background:red">
a
</el-col>
</el-row>
</div>
</template>
<script>
export default{
    data(){
        return {
          index:0,
          list:[1,2,3,4]
        }
    },
    methods:{
        c(index){
             this.index=index
        }
}
</script>
