<template>
<div>
{{msg}}
<button @click="f">ok</button>
</div>
</template>
<script>
export default{
  data(){
    return {
      msg:'你好世界'
    }
  },
  methods:{
    f(){
      this.msg='你好中国'
    }
  }
}
</script>
