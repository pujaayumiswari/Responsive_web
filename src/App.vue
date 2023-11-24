<script setup lang="ts">



</script>

<template>
  <div class="bgWhite">
    <div class="BlueBorderBlack">
      <div class="satu">1</div>
      <div class="flexrow">
        <div class="flexcolumn">2</div>
        <div class="flexcolumn">3</div>
      </div>
      <div class="split70">
        <div class="flexcolumnsplit">
          <div class="pertama BlueBorderBlack">
            <div class="four bgRed">4</div>
          </div>
          <div class="manamju">
            <div class="five">5</div>
            <div class="six">6</div>
            <div class="seven">7</div>
          </div>
        </div>
        <div class="kedua BlueBorderBlack">
          <div class="bgRed eight">8</div>
          <div class="bgRed nine">9</div>
          <div class="bgRed ten">10</div>
        </div>
      </div>
    </div>
    <Bottom/>
    <div class="primaryContainer">
  <div class="whole">
    <div class="container">
        <div class="dotred">.
            <div class="dotwhite">.
                <div class="lastdotred">.</div>
            </div>
        </div>
    </div>
    <div class="anotherContainer">
        <div class="anotherRed">.</div>
    </div>
  </div>
  <div class="blankWhite">.
    <div class="goRow">
        <div class="justred">
            red
        </div>
        <img class="image" src="./assets/star.png" />
    </div>
    <div class="whiteRed">.</div>
  </div>
</div>
  </div>
</template>

<style scoped>

.four{
  height: 100px;
}

.manamju .five {
  border: 2px solid black;
  width: 100%;
  padding: 1em;
}

.manamju .six {
  border: 2px solid black;
  width: 100%;
  padding: 1em;
}

.manamju .seven {
  border: 2px solid black;
  width: 100%;
  padding: 1em;
}

.manamju {
  display: flex;
  flex-direction: row;
  border: 2px solid black;
  justify-content: space-around;
  text-align: center;
  align-items: center;
}

.flexcolumnsplit {
  display: flex;
  flex-direction: column;
  width: 70%;
}

.split70 {
  display: flex;
  flex-direction: row;
  width: 100%;
}

.split70 .pertama {
  text-align: center;
}

.split70 .kedua {
  width: 30%;
  text-align: center;
  max-height: fit-content;}

.satu {
  background-color: blue;
  border: 3px solid black;
  text-align: center;
  padding: 1em;
}

.flexrow {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  width: 100%;
}

.flexrow div {
  text-align: center;
  padding: 1em;
  border: 3px solid black;
  width: 50%;
}

.bgRed {
  background-color: red;
  border: 2px solid black;
  padding: 5px;
  margin: 5px;
}

.bgWhite {
  background-color: white;
  border: 4px solid gray;
  padding: 1em;
  margin: 1em;
  margin-bottom: 8em;
}

.BlueBorderBlack {
  background-color: blue;
  border: 3px solid black;
  padding: 1em;
}

.image {
    width: 60px;
    height: 60px;
    margin-left: 180px;
    margin-top: -1em;
    margin-right: -4em;
    
}

.goRow {
    display: flex;
    flex-direction: row;
}

.justred {
    color: red;
    background-color: red;
    width: 20px;
    height: 21px;
}
.primaryContainer {
    display: flex;
    flex-direction: row;
}
.whiteRed {
    background-color: red;
    color: red;
    margin-left: 2em;
    width: 40px;
}
.blankWhite {
    display: flex;
    flex-direction: column;
    color: white;
    background-color: white;
}
.anotherContainer {
    display: flex;
    flex-direction: column;
    background-color: blue;
}
.anotherRed {
    color: red;
    background-color: red;
    width: 40px;
    height: 20px;
    margin-right: -20px;
}
.lastdotred {
    color: red;
    background-color: red;
    margin-left: 10px;
    width: 40px;
}
.dotwhite {
    color: white;
    background-color: white;
    width: 20px;
    height: 30px;
    margin-left: 1em;
}
.dotred {
    color: red;
    background-color: red;
    width: 35px;
    height: 25px;
}
.whole {
    display: flex;
    width: 65%;
    margin-top: 1em;
    border: 3px solid black;
    height: 54px;
    flex-direction: row;
    background-color: blue;
}
.container {
    background-color: blue;
    width: 100%;
    display: flex;
    flex-direction: column;
}

@media only screen and (max-width: 400px) {
  .flexrow {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}


.split70 {
  display: flex;
  flex-direction: column;
  width: 100%;
  background-color: yellow;
}

.split70 .kedua {
  display: flex;
  flex-direction: row;
  width: 84%;
  text-align: center;
  max-height: fit-content;
  justify-content: space-around;

}


.flexcolumnsplit {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.kedua .bgRed {
  height: 50px;
  width: 50px;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.four {
  height: 80px;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}
.flexrow div {
  text-align: center;
  padding: 1em;
  border: 3px solid black;
  width: 83%;
  height: 8px;
}
}
.image {
    width: 60px;
    height: 60px;
    margin-left: 140px;
    margin-top: -1em;
    margin-right: -4em;
}


@media only screen and (max-width: 730px) {
    .primaryContainer {
    display: none;
}
}
</style>