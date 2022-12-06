<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header class="header">
    <h1 class="logo"><a href="#">JV Bicalho</a></h1>
    <ul class="main-nav">
      <li><a href="#">Home</a></li>
      <li><a href="#">Sobre</a></li>
      <li><a href="#">Projetos</a></li>
      <li><a href="#">Contato</a></li>
    </ul>
  </header>
  <main>
    <section id="#home">
      <div>

        <img id="gato" src="./assets/img/jv2.jpg" alt="" srcset="">
      </div>
      <div id="texto">

        <h2>Front-end Dev</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora ab omnis voluptatem ipsum aperiam enim
          pariatur eveniet magni inventore. Voluptatibus amet quis consequatur dolorem aut iste ex quaerat excepturi
          adipisci.</p>
      </div>
    </section>
    
    <section id="#sobre">
      
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
    <section id="projetos">
    
        <h2>Projetos</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora ab omnis voluptatem ipsum aperiam enim
          pariatur eveniet magni inventore. Voluptatibus amet quis consequatur dolorem aut iste ex quaerat excepturi
          adipisci.</p>
      
    </section>
    <section id="contato">
      <div>

        <img id="gato" src="./assets/img/jv2.jpg" alt="" srcset="">
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
ul {
  margin: 0;
  padding: 0;
  list-style: none;
}


h2,
h3,
a {
  color: #34495e;
}

a {
  text-decoration: none;
}



.logo {
  margin: 0;
  font-size: 1.45em;
}

.main-nav {
  margin-top: 5px;

}

.logo a,
.main-nav a {
  padding: 10px 15px;
  text-transform: uppercase;
  text-align: center;
  display: block;
}

.main-nav a {
  color: #34495e;
  font-size: .99em;
}

.main-nav a:hover {
  color: #718daa;
}



.header {
  height: 7vh;
  padding-left: 2em;
  padding-right: 4em;
  padding-top: .5em;
  padding-bottom: .5em;
  border: 1px solid #a2a2a2;
  background-color: #f4f4f4;
  -webkit-box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
  /* -webkit-border-radius: 5px; */
  /* -moz-border-radius: 5px; */
  /* border-radius: 5px; */
}

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
  overflow: hidden;
}

/* section::before {
  content: ' ';
  position: absolute;
  right: 40vw;
  left: 40vw;
  bottom: -4vh;
  height: 4em;
  border-radius: 100%;
  background-color: rgb(0, 0, 0);
} */
svg{
  width: 100%;
}
section:nth-child(3) {
  background-color: black;
}

section:nth-child(2)::after {
  background-color: white;
}

#gato {
  width: 20vw;
  min-width: 330px;
}

#foto {
  width: 25vw;
  min-width: 330px;
  border-radius: 50%;
  border: 1em solid rgba(230, 227, 227, 0.699);
}

#texto {
  width: 40vw;
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

    .header {
      width: 80%;
      margin: 0 auto;
      max-width: 1150px;
    }
  }

}

@media (min-width: 1025px) {
  .header {
    flex-direction: row;
    justify-content: space-between;
  }

}
</style>
