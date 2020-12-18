<template>

<div class="body">
  <div class="header">
    
    <a href="#">Inicio</a>
    <a href="#">Ingresos</a>
    <a href="#">Ayuda</a>

    
   
      
        <!--<button>Gastos</button>-->
  </div>
   
  <div class="gastos">
    <div class="titulo_2">
      <img id="logo" src="./assets/logo.png" alt="Logo: Libretapp">
      <h2>Gastos por pagar</h2> <!--Validar nombre-->
    </div>        
      Nombre: <input type="text" placeholder="Ej: Francisco">
      <br>
      Valor: &nbsp;&nbsp; <input type="text" placeholder="Ej: 150000">
      <br>
      Fecha: &nbsp; <input type="date">
      <br>
      Estado: <input type="text" placeholder="Al dia - Atrasado">
      <br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input id="envio" type="submit">
    
  </div>
  <div class="footer">
      <h3>Todos los derechos reservados 2020</h3> 
  </div>


</div>
</template>

<script>

export default{
  name: 'libretapp',
}


</script>

<style>

#envio{
  width: 100px;
  background: rgb(205, 223, 226);
  cursor: pointer;
}

.body{
  width: 95%;
  height: 100%;
  margin: auto;
  margin-top: 85px;
  border-radius: 5px;
  background: rgb(255, 255, 255);
}
body{
  background-color: #ffffff50;
  color:#000000;
  font-family: 'PoetsenOne';
  border-radius: 12px;
  width: 98%;
  height: 98%;
  /*box-shadow: 8px 8px 8px #999;*/
  margin: auto;
}
.header {
    background-color: #37B6FF;
    color:#000000;
    border-radius: 8px;
    padding: 1.3em;
}

.header a{
  text-decoration: none;
  border: rgb(148, 214, 224);
  color: rgb(255, 255, 255);
  background: #1874a8;
  border-radius: 10px;
  text-align: justify;
  margin: 5px 5px 5px 5px; 
  padding: 0.75em;
}


.header a:hover{
  background: rgba(158, 215, 232, 0.79);
  cursor: no-drop;
}

.footer{
    height: 50px;
    background: #37B6FF;
    color: #000000;
    text-align: center;
    border-radius: 8px;
}

.footer h3{
  padding: 10px;
  text-align: center;
}

.titulo_2 h2{
  text-align: center;
  margin-bottom: 40px;
}
#logo{
  width: 150px;
  height: 150px;
}
.gastos{
  background: rgba(255, 255, 255, 0.98);
  margin: auto;
  margin-top: 15px;
  width: 25%;
  height: 80%;
  border-radius: 10px;
  text-align: center;
}

.gastos input{
  border-radius: 5px;
  box-shadow: 3px 3px 3px #999;
  margin-bottom: 10px;
  text-align: center;
  border-color: #999;
}
#titulo{
    color: #000;
    font-family: 'PoetsenOne';
    margin-right: auto;
    padding: 10px;
    border-color: #747d8c;
  }

.gastos h3{
  margin-left: 10px;
  padding: 10px;
  color: rgba(18, 2, 48, 0.349);
}

</style>
