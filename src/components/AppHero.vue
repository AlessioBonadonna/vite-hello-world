<script>
export default {
        data(){
            return{
                titoloJumbo: 'Ciao sono un Hero'
            }
        }
    }


</script>
<template>
<div class="hero">
<h2>{{titoloJumbo}}</h2>
</div>
</template>
<style scoped lang="css">
.hero{
  position:relative;
  height: 70vh;
  width: 100%;
  margin:0 auto;
  background-image: url(../../public/img/sfondo.jpeg);

}

.hero h2{
position:absolute;
bottom:0;
right: 30px;
color:cornflowerblue;
font-size: 3em;
}
</style>