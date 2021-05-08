<template>
{{msg}}
<button @click="点击事件">ok</button>
</template>
<script>
export default{
  data(){
    return {
      msg:'你好世界'
    }
  },
  methods:{
    点击事件(){
      this.msg='你好中国'
    }
  }
}
</script>
