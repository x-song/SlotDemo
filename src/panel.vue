<template>
  <div class="alterbox">
      <slot name="k0"></slot>
      <slot name="k1"></slot>
      <slot name="k2"></slot>
      
  </div>
</template>
<script>
    export default{
        data(){
            return {
              msg:"合并分支slot1.0"
            }
        }
    }
</script>
<style>
    .alterbox{
        width: 400px;
        height: 400px;
        border: 1px  solid #000;
        margin: 200px auto;
    }
    p{
        margin-top: 150px;
    }
</style>
