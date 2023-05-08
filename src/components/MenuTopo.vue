<template>
  <div>
    <nav class="navegacao">
      <img class="logo" src="../assets/logop.png" alt="logo">      
      <a @click="acessarApresentacao()">Home</a>
      <a @click="acessarConhecimentos()">Conhecimentos Técnicos</a>
      <a @click="acessarExperiencia()">Experiência</a>
      <a @click="acessarContato()">Contato</a>
      <a @click="acessarSobre()">Sobre</a>   
      <button>Linkedin</button>   
    </nav>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>

.logo{
  width: 48px;
  height: 48px;

}
.navegacao{
   background: white;
   padding: 36px ;
   color: rgb(159, 162, 163);
   display: flex;
   align-items: center;
   justify-content: center;
   gap: 48px   
}

button{
  color: white;
  background: #4a6cf7;
  border-radius: 50px;
}

a {
  font-weight: 500;
  color: #494f5b;
  text-decoration: inherit;
}
a:hover {
  color: #535bf2;
}
</style>