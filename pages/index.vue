<template>
<div>
<div>
<button v-for="x in list">{{x}}</button>
</div>
</div>
</template>
<script>
export default{
    data(){
        return {
          list:[1,2,3,4]
        }
    }
}
</script>
