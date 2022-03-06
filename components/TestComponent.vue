<template>
  <div>
    <h3>테스트 입니다.</h3>
    <h3>{{number}}</h3>
  </div>
</template>
<script>
  export default {
    data(){
      return{
        number: 0
      }
    },
    mounted(){
      this.number = 30;
    }
  }
</script>
<style>

</style>