<template>
  <section class="first">
    <div class="allContent">
      <div class="header">
        <div id="left">
          <img src="./assets/logo.svg">
          <h2>devloper.</h2>
        </div>
        <div id="right">
          <a>Connexion</a>
          <a id="btn">Inscription</a>
        </div>
      </div>
      <div class="content">
        <img id="square" src="./assets/Composant1.svg">
        <div id="text">
          <h1 style="font-size: 25px; margin-bottom: 70px;"> Bienvenue sur <span id="devloper">DEVLOPER.</span></h1>
          <p><span>Devloper </span> est une plateforme de développeurs qui regroupe le savoir-<br>faire, le besoin ainsi que de la documentation pour ces derniers.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>


export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Montserrat;
}
.first{
  width: 100vw;
  height: 100vh;
  background-color: #E56A6A;
}
.allContent{
  margin: 0 10% 10%;
}
.header{
  display: flex;
  justify-content: space-between;
  padding-top: 2%;
}
#left{
  display: flex;
  color: #ffffff;
  align-items: center;
}
#left>img{
  margin-right: 15px;
}
#right{
  display: flex;
  align-items: center;
}
#btn{
  color: #ffffff !important;
  background-color: #3F3D56;
  padding: 10px 20px;
  border-radius: 55px;
  margin-left: 20px;
}
#right>a{
  font-weight: bold;
  font-size: 20px;
  color: #3F3D56;
  cursor: pointer;
}
#text{
  color: #3F3D56;
  position: relative;
   z-index: 2;
}
#text p{
  font-weight: bold;
}
span{
  color: #ffffff;
}
.content{
  margin-top: 15%;
  position: relative;
}
#square{
  position: absolute;
  bottom: 50px;
  left: -50px;
  z-index: 1;
}
</style>
