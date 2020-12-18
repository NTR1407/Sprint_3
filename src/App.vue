<template>

<div class="body">
 <div class="header">
      <h1 id="titulo">LibretApp</h1>
        <!--<button>Gastos</button>-->
  </div>
  <div class="gastos">
    <div class="titulo_2">
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
<!--
  <div class="gastos">
    <div class="titulo_2">
      <h2>Gastos Pagados</h2> Validar nombre
    </div>
  </div>
-->

  <div class="footer">
      <h3>Todos los derechos reservados 2020</h3> 
 
  </div>


</div>
</template>

<script>

</script>

<style>

#envio{
  width: 100px;
  background: rgb(205, 223, 226);
}
.body{
  background-color: darkgrey;
  border-radius: 12px;
  width: 90%;
  box-shadow: 8px 8px 8px #999;
  margin: auto;
}
.header {
    height: 50px;
    background: rgba(30, 75, 83, 0.98);
    color: #fff;    
    align-items: center;
    border-radius: 8px;
}

.header h1{
  text-align: center;
}



.footer{
    height: 50px;
    background: rgba(30, 75, 83, 0.98);
    color: #fff;
    text-align: center;
    border-radius: 8px;
}

.footer h3{
  padding: 10px;
  text-align: center;
}

.titulo_2 h2{
  text-align: center;
}

.gastos{
  background: rgba(165, 214, 223, 0.98);
  margin: auto;
  width: 45%;
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
    color: #fff;
    margin-right: auto;
    padding: 10px;
    border-color: #747d8c;
  }
.button button:hover{
  background: rgba(158, 215, 232, 0.79)
}

.button button{
  background: rgba(30, 75, 83, 0.98);
}
.button{
    /*display: block;*/
    padding: 15px 20px;
    color: #fff;
    text-decoration: none;
    margin-top: 10px 5px 10 px;
} 

.gastos h3{
  margin-left: 10px;
  padding: 10px;
  color: rgba(18, 2, 48, 0.349);
}

</style>
