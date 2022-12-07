<script setup>
import Navbar from './components/Navbar.vue'
import Projetos from './components/Projetos.vue'
import Home from './components/Home.vue'

</script>

<template>
  <Navbar/>
  <main>
    <Home/>
    
    <section id="sobre">
      
      <div>

        <img id="foto" src="./assets/img/jv-foto.jpg" alt="" srcset="">
      </div>
      <div id="texto">

        <h2>Front-end Dev</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora ab omnis voluptatem ipsum aperiam enim
          pariatur eveniet magni inventore. Voluptatibus amet quis consequatur dolorem aut iste ex quaerat excepturi
          adipisci.</p>
      </div>
    </section>
    <Projetos/>
    <section id="contato">
      <div>

        <img id="gato" src="./assets/img/jv1.png" alt="" srcset="">
      </div>
      <div id="texto">

        <h2>Front-end Dev</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora ab omnis voluptatem ipsum aperiam enim
          pariatur eveniet magni inventore. Voluptatibus amet quis consequatur dolorem aut iste ex quaerat excepturi
          adipisci.</p>
      </div>
    </section>
  </main>
  <footer></footer>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
  align-items: center;

}

section {
  width: 99vw;
  height: 87vh;
  display: flex;
  align-items: center;
  justify-content: space-around;
  /* overflow: hidden; */


}


section:nth-child(3) {
  background-color: black;
}

section:nth-child(2)::after {
  background-color: white;
}




#foto {
  width: 25vw;
  min-width: 330px;
  border-radius: 50%;
  border: 1em solid rgba(230, 227, 227, 0.699);
 
background: linear-gradient(145deg, #f0f0f0, #cacaca);
box-shadow:  31px 31px 61px #bebebe,
             -31px -31px 61px #ffffff;
  
}




#projetos{
  
background: #515151;
flex-flow: column;

}
#projetos h2{
  font-family: Bentham, serif;
    text-transform: uppercase;
    text-align: center;
    font-size: 45px;
    letter-spacing: 15px;
    color: rgb(212, 206, 206);
}

/* ================================= 
  Media Queries
==================================== */




@media (min-width: 769px) {

.header,
.main-nav {
  display: flex;
}

.header {
  flex-direction: column;
  align-items: center;

 
    width: 80%;
    margin: 0 auto;
    max-width: 1150px;
  }
}



@media (min-width: 1025px) {
.header {
  flex-direction: row;
  justify-content: space-between;
}
}

</style>
