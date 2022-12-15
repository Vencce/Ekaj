<script setup></script>

<template>
  <main>
    <header class="heroimg">
      <div class="Titulo">
        <h1>Coffee Unity</h1>
      </div>
    </header>
      <div class="box-cafe">
        <div class="nada4"></div>
        <div class="all-cafe">
          <div class="box-txt">
            <div class="box-hs">
              <h2 class="hs">Curios Facts</h2>
            </div>
            <div class="box-r">
              <img src="@/assets/img/Café.jpg" alt="" class="cafe1">
            </div>
        </div>

        <div class="box-txt">
          <h2 class="hr">Recipes</h2>
          <div class="box-r">
            <img src="@/assets/img/cafe2.jpg" alt="" class="cafe1">
          </div>
        </div>
        
        <div class="box-txt">
          <h2 class="hf">History</h2>
          <div class="box-r">
            <img src="@/assets/img/cafe3.jpeg" alt="" class="cafe1">
          </div>
        </div>
      </div>
        <div class="nada3"></div>
      </div>
      <div class="nada"></div>
      <div class="nada2"></div>
  </main>
</template>

<style scoped>
/*------------------------------------------HEADER--------------------------------------------------------------------- */

.heroimg {
  width: 250vh;
  height: 314px;
  background-image: url("@/assets/img/cafebanner.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}


/*------------------------------------------BOX CIRCULAR--------------------------------------------------------------------- */

.box-r {
  width: 290px;
  height: 300px;
  border-radius: 50%;
  background-color: #be5418;
  border: 4px solid black;
}

/*------------------------------------------CARDS DAS ESCRITAS--------------------------------------------------------------------- */
.hs {
  background-color: #6f3e1a;
  border: 4px solid black;
  text-align: center;
  font-size: 3em;
  color: white;
}

.hr {
  background-color: #6f3e1a;
  border: 4px solid black;
  text-align: center;
  font-size: 3em;
  color: white;
}

.hf {
  background-color: #6f3e1a;
  border: 4px solid black;
  text-align: center;
  font-size: 3em;
  color: white;
}


/*------------------------------------------NADAS--------------------------------------------------------------------- */

.nada4 {
  height: 80px ;
  width: 190vh;
  background-color: #c39b65;
  border-top: solid 4px black;
}
.nada3 {
  height: 80px ;
  width: 190vh;
  background-color: #c39b65;
  margin-top: 100px;
}
.nada2 {
  background-color: #925424;
  width: 201.3vh;
  height: 99px;
  border-top: solid 4px black;
}
.nada {
  background-color: #9b622e;
  width: 201.3vh;
  height: 92px;
  border-top: solid 4px black;
}

/*------------------------------------------CAFES--------------------------------------------------------------------- */
.box-txt {
  margin-left: 400px;
  margin-top: 10px;
}
.cafe1 {
  width: 250px;
  height: 20vh;
  border-radius: 50%;
  margin: 20px;
}

.all-cafe {
  align-items: center;
  display: flex;
}

.box-cafe {
  align-items: center;
  background-color: #fde9cb;
  height: 55vh;
  width: 190vh;
  margin-left: 70px;
  margin-top: 80px;
  border-left: 4px solid black;
  border-right: 4px solid black;
}

/*------------------------------------------PARTE DE CIMA--------------------------------------------------------------------- */

.Titulo{
  padding: 5px;
  color: white;
  margin-left: -50vh;
}

h1 {
  text-align: center;
  font-size: 7em;
  margin: 5px;
  font-family: 'EB Garamond', serif;
  margin-top: 100px;
}
</style>
