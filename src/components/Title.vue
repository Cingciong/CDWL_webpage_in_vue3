<script></script>


<template>
     <div class="moj1">
        <div class="header">
        <a href="https://discord.gg/D8D5vCdAzx"><button class="button-1"
                style= "margin-right:15vw; background-image: url('src/assets/icons/facebook.svg');"></button></a>
        <a href="https://discord.gg/D8D5vCdAzx"><button class="button-1"
                style="background-image: url('src/assets/icons/youtube.svg');"></button></a>
        <a href="https://discord.gg/D8D5vCdAzx"><button class="button-1"
                style="background-image: url('src/assets/icons/patreon.svg');"></button></a>
        <a href="https://discord.gg/D8D5vCdAzx"><button class="button-1"
                style="background-image: url('src/assets/icons/discord.svg');"></button></a>

                <div class="always-on-screen">Nie gwarantujemy jakości, ani zwrotu
            pieniędzy.</div>        
     </div>

       <div class="title-button">
            <div class="half-title-button"></div>
            <div class="half-title-button">
                <h1 class="h1">Zobacz co ma do zaoferowania
premiera pre-pre-alfa na Steam </h1>
                <button class="button-cdwl"  href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"></button>
                
            </div>    
       </div>
     <div class="black-frame"></div>  

    </div>
</template>


<style>
.moj1 {
      margin: auto;
      height: 50vw;
      background-image: url("src/assets/img/jojo.png"),
        url("src/assets/img/cdwl_napis.png"), url("src/assets/img/city.png");
      background-position: 5% 100%, 90% 30%, bottom center;
      background-size: 50vw, 50vw, cover;
      background-repeat: no-repeat, no-repeat, no-repeat;
      z-index: -5;
    }

.header{
    width:100vw;
    height:10vw
}

.title-button{
    width:100vw;
    height:35vw;
}

.half-title-button{
    width:50vw;
    height:35vw;
    float:left;
}



.black-frame {
      width: 100vw;
      background-image: url("src/assets/img/black-frame.png");
      transform: rotate(180deg);
      background-position: bottom left;
      background-size: 100%;
      background-repeat: no-repeat;
      height: 7vw;
      z-index: -1;
    }

.always-on-screen {
      margin-top: 5%;
      position: fixed;
      font-size: 1.2vw;
      width: 30vh;
      padding-top: 5vh;
      height: 17vh;
      z-index: 9999;
      background-color: #00f0ff;
      text-align: center;
      -webkit-clip-path: polygon(
        69% 0,
        100% 25%,
        100% 100%,
        50% 100%,
        0 100%,
        0 0
      );
      clip-path: polygon(69% 0, 100% 25%, 100% 100%, 50% 100%, 0 100%, 0 0);
    }

    .h1{
        margin-top: 19vw;
      margin-left: 0vw;
      color:#00f0ff;
      font-size: 1.5vw;
    }

    .button-cdwl {
      margin-top: 0vw;
      margin-left: 7vw;
      float: bottom;
      height: 14vw;
      width: 30vw;
      background-size: 30vw;
      border: none;
      background-color: transparent;
      background-image: url("src/assets/img/demo.png");
    }

    .button-1 {
      background-size: 3vw;
      float: right;
      margin-top: 3vw;
      height:3vw;
      width:3vw;
      border: none;
      background-repeat: no-repeat;
      background-color: transparent;
      margin-right: 1vw;
    }
</style>