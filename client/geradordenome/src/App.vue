<template>
  <div >
    <div  id="slogan" class="text-center">
        <h1>Gerador de Nomes </h1>
        <br/>
        <h6 class="text-secondary"> Gerador de nomes utilizando Node.Js , Vue.Js e Graphql</h6>
    </div>
    <div id="main">
     <router-view></router-view>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainList from "./components/DomainList";


export default {
  name: "app",
  components: {
   DomainList
  } 
};

</script>

<style>
  #slogan {
      margin-top: 130px;
      margin-bottom: 30px;
  }

  #main { 
      background-color: #f1f1f1;
      padding-top: 30px;
      padding-bottom: 30px;
  }
</style>
