<template lang="">
    <div>
        <header class="header">
    <h1 class="logo"><a href="#">JV Bicalho</a></h1>
    <ul class="main-nav">
      <li><a href="#home">Home</a></li>
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#projetos">Projetos</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>
  </header>
    </div>
</template>
<script>
export default {

}
</script>
<style >
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
  /* border: 1px solid #a2a2a2; */
  /* background-color: #f4f4f4;
  -webkit-box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75); */
  /* -webkit-border-radius: 5px; */
  /* -moz-border-radius: 5px; */
  /* border-radius: 5px; */
  /* border-radius: 50px; */
background: #e0e0e0;
box-shadow:  20px 20px 60px #bebebe,
             -20px -20px 60px #ffffff;
}
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