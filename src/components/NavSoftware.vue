<template>
  <div class="global">
<ul class="list_categories_main" id="main">
  <li class="list_categories"><h3 class="logo_text"><img class="logo" src="../../src/assets/navsvg/logo.svg"></h3></li>
  <li class="list_categories first_list"><h3><img class="logo_categories" src="../../src/assets/navsvg/home.svg">Home</h3></li>
  <li class="list_categories"><h3><img class="logo_categories" src="../../src/assets/navsvg/software.svg">Software</h3></li>
  <li class="list_categories"><h3><img class="logo_categories" src="../../src/assets/navsvg/game.svg">Game</h3></li>
  <li class="list_categories"><h3><img class="logo_categories" src="../../src/assets/navsvg/learn.svg">Learn</h3></li>
  <li class="list_categories"><h3><img class="logo_categories" src="../../src/assets/navsvg/graphic.svg">Graphic</h3></li>
  <li class="list_categories list_last"><h3><img class="logo_categories" src="../../src/assets/navsvg/about.svg">About</h3></li>
  <hr>
  <li class="credits">
    <h4>Made with ❤</h4>
    <p><a href="https://eiio.dev">Par <strong>eiio.dev</strong></a></p>
  </li>
</ul>
  </div>
</template>

<script>


export default {
  name: "NavSoftware",
  data: function () {
    return {
      CategoriesNameOne: "Home"

    }
 }
}
</script>

<style scoped>
.first_list{
}

.logo{
  height: 130px;
}
.logo_text{
  padding-left: 30px;
}

#main{
  height: 100%;
}

.first_list{
  margin-top: 0px;
}
.global{
  background-color: #211d37;
  width: 18%;
  height: 100%;
  position: absolute;
}

.logo_categories{
  height: 1em;
  width: 1em;
  padding-right: 12%;
}

.list_last{
  margin-top: 58%;
}

.list_categories{
  color: #656285;
  transition: 0.2s;
  list-style-type: none;
  position: relative;
  left: calc(100% / 2 - 22%);
  padding-top: 12%;
}

.list_categories:hover{
  color: #fd4577;
;
}

hr{
  margin-top: 10%;
  color: #2c3e50;
  border-width: 3px;
  border-style: solid;
}

.credits, a{
  padding-top: 10%;
  text-align: center;
  color: white;
}

a{
  position: relative;
  top: 13px;
}

</style>