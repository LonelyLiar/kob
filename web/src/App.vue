<template>
  <NavBar />
  <router-view></router-view>
</template>

<script>
import NavBar from './components/NavBar.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap"

//import $ from 'jquery'
export default{
  components:{
    NavBar
  },
  setup(){
    // $.ajax({
    //   url:"http://127.0.0.1:3000/user/account/token/",
    //   type:"post",
    //   data:{
    //     username:"fkh",
    //     password:"pfkh",
    //   },
    //   success(resp){
    //     console.log(resp);
    //   },
    //   error(resp){
    //     console.log(resp);
    //   }
    // });

    // $.ajax({
    //   url:"http://127.0.0.1:3000/user/account/info/",
    //   type:"get",
    //   headers:{
    //     Authorization:"Bearer "+"eyJhbGciOiJIUzI1NiJ9.eyJqdGkiOiI0ZTI1NzU3ZjBlZmE0ZmI0YTgzMTkwN2ZjYTQ5MzU0OSIsInN1YiI6IjEiLCJpc3MiOiJzZyIsImlhdCI6MTY1ODkxMDAxMiwiZXhwIjoxNjYwMTE5NjEyfQ.wLJ9iOewetSEwLfxCJFjW326OwyXhEFtGrWPVsq5wyY"
    //   },
    //   success(resp){
    //     console.log(resp);
    //   },
    //   error(resp){
    //     console.log(resp);
    //   }
    // });
    // $.ajax({
    //   url:"http://127.0.0.1:3000/user/account/register/",
    //   type:"post",
    //   data:{
    //     username:"fkh",
    //     password:"123",
    //     confirmedPassword:"123",
    //   },
    //   success(resp){
    //     console.log(resp);
    //   },
    //   error(resp){
    //     console.log(resp);
    //   }
    // })
  }
}
</script>


<style>
body{
  background-image: url("@/assets/images/background.png");
  background-size: cover;
}
</style>
