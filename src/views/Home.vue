<template>
  <div class="home"  >
    <h3 >首页</h3>
    <router-link to="/login" @click="changedis" :class="{acticve: ac}">登录界面</router-link>
  </div>
</template>
<script>

// import { ref,reactive } from 'vue';
export default {
  name: "Home",
  components: {},
  data(){
    return{
      ac:false
    }
  },
  methods:{
    changedis(){
      this.ac=true
      console.log(ac);
    }
  }
  // setup(){
  //   const ac = ref<boolean>(false);
  //   const changedis =reactive(()=>{
  //     this.ac=!this.ac
  //     console.log(ac);
  //   })
  // }
 
};
</script>
<style scoped>
</style>>