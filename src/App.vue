<template>

<div class="body">
 <div class="header">
    <link href="http://fonts.cdnfonts.com/css/poetsen-one" rel="stylesheet">

      <h1 id="titulo">LibretApp</h1>
        <!--<button>Gastos</button>-->
  </div>
  <div class="gastos">
    <div class="titulo_2">
      <h2>Gastos por pagar</h2> <!--Validar nombre-->
    </div>
    <h3>Nombre</h3>
    <h3>Valor</h3>
    <h3>Fecha de pago</h3>
    <h3>Vencido</h3>
  </div>

  <div class="gastos">
    <div class="titulo_2">
      <h2>Gastos Pagados</h2> <!--Validar nombre-->
    </div>
  </div>


  <div class="footer">
      <h3>Todos los derechos reservados 2020</h3> 
 
  </div>


</div>
</template>

<script>

</script>

<style>
@import url('http://fonts.cdnfonts.com/css/poetsen-one?styles=54169');
body{
  background-color: #FFFFFF;
  color:#000000;
  font-family: 'PoetsenOne';
  border-radius: 12px;
  width: 90%;
  box-shadow: 8px 8px 8px #999;
  margin: auto;
}
.header {
    background-color: #37B6FF;
    color:#000000;
    font-family: 'PoetsenOne';
    height: 50px;
    align-items: center;
    border-radius: 8px;
}

.header h1{
  text-align: center;
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
}

.gastos{
  background: rgba(165, 214, 223, 0.98);
  margin: auto;
  width: 45%;
  border-radius: 10px;
}
#titulo{
    color: #000;
    font-family: 'PoetsenOne';
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
    color: #000000;
    text-decoration: none;
    margin-top: 10px 5px 10 px;
} 

.gastos h3{
  margin-left: 10px;
  padding: 10px;
  color: rgba(18, 2, 48, 0.349);
}

</style>
