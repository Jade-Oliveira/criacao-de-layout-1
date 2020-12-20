<template>
  <body>
    <div id="div1">HEADER</div>

    <div id="div2">
        <div class="menu-esquerdo">MENU <br>Esquerdo</div>
        <div class="conteudo">CONTEÚDO</div>
        <div class="menu-direito"> MENU <br> Direito</div>
    </div>

</body>
</template>

<script>
export default {
  
}
</script>

<style>


  body{
            font-size: 62.5%;
            width: 750px;
            max-width: 100%;
            padding: 2px;
            color: white;
            font-family:sans-serif;
            margin: 0 auto;
        }

        #div1{
            background-color: blue;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: left;
            padding-left: 30px;
            margin-bottom: 2px;
            font-size: 18px;
            
            
        }

        #div2{
            display: flex;
            justify-content: space-between;
            font-size: 15px;
            
        }

        #div2 div{
            height: 12vh;

        }

        #div2 div.menu-esquerdo{
            background-color: rgb(134, 18, 18);
            width: 150px;
            height: 105px;
            padding-left: 15px;
            padding-top: 12px;

        }

        #div2 div.conteudo{
            background-color: rgb(30, 159, 163);
            width: 450px;
            display: flex;
            align-items: top;
            justify-content: center;
            height: 170px;
            padding-top: 12px;
        }

        #div2 div.menu-direito{
            background-color: rgb(79, 139, 79);
            width: 150px;
            height: 105px;
            display: flex;
            padding-left: 15px;
            padding-top: 12px;
        }



</style>