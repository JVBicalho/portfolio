<template >
    <div>
        <section id="home">
      <div id="texto">
        
        <h2>Front-end Developer</h2>
        
        </div>
        <div>
  
          <img id="gato" src="../assets/img/jv1.png" alt="" srcset="">
        </div>
      <div class="arrow-down">
        <span>Sobre mim</span>    
      </div>
    </section>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="css">
#home{

    border-bottom: #bebebe solid 5px;
}
.arrow-down {
    display: flex;
align-items: center;
justify-content: center;
content: ' ';
position: absolute;
right: 40vw;
left: 40vw;
bottom: -4vh;
height: 4em;
border-radius: 10px;
background: linear-gradient(145deg, #cacaca, #f0f0f0);
box-shadow:  20px 20px 60px #bebebe,
           -20px -20px 60px #ffffff;


} 
.arrow-down span {
    font-family: Bentham, serif;
    text-transform: uppercase;
    text-align: center;
    font-size: 24px;
    letter-spacing: 2px;
    word-spacing: 3px;
    color: rgb(0, 0, 0);
   
    
}
svg{
width: 100%;
}
#gato {
  width: 20vw;
  min-width: 330px;
  
}
#home #texto h2 {

font-family: Bentham, serif;
text-transform: uppercase;
text-align: center;
font-size: 69px;
letter-spacing: 15px;
color: rgb(6, 26, 26);

/* text-shadow: rgb(0, 0, 0) 2px 2px 2px; */
}
#texto {
  width: 40vw;
  padding: 1em;
  border-radius: 20px;
  background: #e0e0e0;
  box-shadow:  20px 20px 60px #bebebe,
              -20px -20px 60px #ffffff;
}
</style>