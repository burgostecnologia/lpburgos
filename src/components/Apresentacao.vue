<template>
  <div class="conteudo">
    <div class="esquerda">
        <p>Olá, Eu sou o</p>
        <p>Roberto Burgos</p>
        <p>Consultor Full-Stack</p>
        <p>Há mais de 20 anos trabalhando tando em ambientes de grande porte como plataforma Alta</p>
    </div>
    <div class="direita">     
      <div class="forma"></div>
      <img src="../assets/hero-image6.png" alt="minhaFoto">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.conteudo{
  background: white;
  color: black;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  
}

.direita{
 
  
  
}
.forma{
  background: #4668f1;
  width: 600px;
  height: 450px;
  border-radius: 500px 300px 0px 100px;
  
}
img{
  width: 550px;
  height: 550px;
  position: relative;
  top: -551px;
  right: -50px;
  
}
</style>