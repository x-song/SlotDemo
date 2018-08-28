<template>
  <div id="app">
    <panel v-show="vshow">
      <p slot="k0">{{ msg }}</p>
      <a slot="k1" href="javascript:;" @click="fn1">确定</a>  
      <a slot="k2" href="javascript:;">取消</a>  
    </panel>
  </div>
</template>

<script>
import panel from "./panel.vue"  ;


export default {
  name: 'App',
  data(){
    return {
      msg:"弹窗提示的文字",
      vshow:true
    }
  },
  methods:{
    fn1(){
     this.vshow = false;
    }
    
  },
  components:{
    panel
   
  }
}
</script>

<style>


</style>
