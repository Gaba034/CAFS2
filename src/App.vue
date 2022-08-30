<template>
  <router-view></router-view>
</template>

<script>

</script>
<style>
@viewport {
  user-zoom: fixed;
}
.sidebar-content{
  height: 100%;
}
.title{
  color: white;
  font-size: 40px;
  font-weight: 500;
}
.minor-title{
  color: white;
}
.container{
  height: 93vh;
  
}
.btn-container{
  display: flex;
  height: 100%;
  width: 100%;
  justify-content: right;
  padding: 10px;
  
}
.v-btn:before {
    content: "";
    display: block;
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    border-radius: inherit;
    box-shadow:none;
}

.cube:nth-child(3){
  background-color: #FFFFFF;
  width: 36vw;
  height: 70vh;
  border-radius: 30px;
  transform: rotate(45deg);
  position: fixed;
  left: 12vw;
  top:50vh;
  display:flex;
  box-shadow: 0px 10px 30px #3b3b3b57;
  border-right: rgba(0, 0, 0, 0.397) 1px solid;
  overflow:hidden;
  justify-content: center;
  align-content: center;
  align-items: center;
}
.cube:nth-child(2){
  background-color: #D9D9D9;
  width: 37vw;
  height: 70vh;
  border-radius: 40px;
  transform: rotate(45deg);
  position: fixed;
  left: 3vw;
  top: 45vh;
  box-shadow: 0px 10px 30px #3b3b3b57;
}
.sphere-cube{
  background-color: #5A8A9F; 
  width: 9vw;
  height: 9vw;
  border-radius: 100px;
  position:relative;
  left: -25vw;
  top: 5vh;
}
.sphere:nth-child(6){
  background-color: #5A8A9F; 
  width: 9vw;
  height: 9vw;
  border-radius: 100px;
  position:relative;
  right: 10vw;
  top: 67vh;
}
.sphere:nth-child(5){
  background-color: #5a8a9f81; 
  width: 6vw;
  height: 6vw;
  border-radius: 100px;
  position:relative;
  right: 8vw;
  top:73vh;
}
.sphere:nth-child(4){
  background-color: #5a8a9fb6; 
  width: 6vw;
  height: 6vw;
  border-radius: 100px;
  position:fixed;
  left: 350px;
  top: 65px;
}
.sphere:nth-child(3){
  background-color: #6e9eb2
  ; 
  width: 9vw;
  height: 9vw;
  border-radius: 100px;
  position:absolute;
  left: 3.7vw;
  top: 5vh;
  overflow: hidden;
  display: flex;
  padding-top: 1%;
  justify-content: space-around;
  align-content:space-around;
}
.sphere:nth-child(3) .image{
  background-image: url(assets/IMG-20220617-WA0011.jpg);
  width: 60%;
  height: auto;
  background-size: contain;
  border-radius: 10px;
}
.sphere:nth-child(2){
  background-color: #5a8a9f9f; 
  width: 6vw;
  height: 6vw;
  border-radius: 100px;
  position:absolute;
  left: 4vh;
  top: 11vh;
}
.sphere:nth-child(1){
  background-color: #5a8a9f81; 
  width: 6vw;
  height: 6vw;
  border-radius: 100px;
  position:absolute;
  left: 9vw;
  top: 6vh;
}
.spheres{
  width: 0;
  height: 0;
}
.text{
  width: 60vh;
  height: 26vh;
  background-color:#1d6482ea;
  border-radius: 20px 0px 10px 20px;
}
.text:nth-child(1){
  font-size: 3em;
  line-height: 100%;
  text-align:right;
  position: absolute;
  top: 30vh;
  right: 10vh;
}
.text:nth-child(2){
  font-size: 1.75em;
  line-height: 100%;
  text-align:right;
  position: absolute;
  right: 10vh;
  top: 50vh;
}
html{
  overflow: hidden;
}
.text{
  color: white;
}
.text-container{
  height: 100%;
  width: 100%;
  justify-content: flex-end;
  display: flex;
}
.sidebar{
  background-color: black;
}
</style>