

<template>
    <div class="character">
        <div class="char-1"> 
            <div class="box-holder">
                <img class="img-1" src="src/assets/img/Character/yellow-frame-s.png">
                <div class="box">
                    <div class="text-holder-1">XYZ XYZ XYZ XYZ XYZ XYZ</div>
                    <div class="text-holder-2">XYZ XYZ XYZ XYZ XYZ XYZ</div>    
                </div>
                <img src="src/assets/img/Character/yellow-frame-s.png">
            </div>
        </div>
        <div class="char-2"> 

        </div>
    </div>
</template>

<style scoped>

.character{
    width:100vw;
    height:50vw;
    background-color: #20202b;
    background-image: url('src/assets/img/Character/john.png'); 
    background-size: 8vw;
}

.char-1{
width:30vw;
height:100%;
float:left;
}

.char-2{
width:70vw;
height:100%;
float:left;
}

.box-holder{
    width:30vw;
    height:25vw;
    margin-top:12vw;
}

.box{
    width:30vw;
    height:20vw;
    background-color: #ffd000;

}

img{
    width:30vw;
}
.img-1{
  webkit-transform: scaleY(-1);
  transform: scaleY(-1);
  margin-bottom:-1vw;
}

.text-holder-1{
    width:28vw;
    height:7vw;
    padding:1vw;
    font-size: 1.5vw;
}

.text-holder-2{
    width:28vw;
    height:10vw;
    padding:1vw;
    padding-top: 0vw;
}


</style>

<script>

</script>