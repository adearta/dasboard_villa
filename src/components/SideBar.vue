<template>
<!-- topbar -->

<!-- side bar -->
      <div class="sidenav">
          <img alt="Vue logo" src="./../assets/logo.jpg">
       <p>Main Menu</p>
       
       <a href="#">Menu A</a>
       <a href="#">Menu B</a>
       <a href="#">Menu C</a>
       <a href="#">Menu D</a>
   </div>

<!-- title -->
<div>
    <div class="row">
        <div class="coloumn">
            <h1 class="title">{{ title }}</h1>
            <p class="col-b">{{ title }}/{{ title }}</p>
        </div>
    </div>
</div>




<!-- cardview -->

</template>

<script>
// import Image from './assets/logo.jpg'

export default {
data(){
    return{
        title: 'dashboard'
    }
}
}
</script>

<style>
.coloumn{
    clear: both;
}
.col-b{
margin-top: 25px;
margin-right: 10px;
float: right;
font-size: 16px;
text-transform: uppercase;
}
.dashboard{
    text-align: right;
}
img{
    height: 100px;
    width: 100px;
    border-radius: 10px;
    margin-bottom: 20px;
}
.title{
float: left;
font-weight: 400;
font-size: 20px;
text-transform: uppercase;
color: #273240;
padding-top: 10px;
padding-left: 190px;
text-align: left;
}

p{
    font-size: 1.2vw;
    color: #737BBB;
    text-align: left;
    margin-left: 20px;
    font-weight: 400;
    padding-left: 10px;
    /* margin */
}
body{
    background: #f1f6f9;
    overflow: auto;
}
.sidenav {
  height: 100%;
  width: 10%;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: white;
  overflow-x: hidden;
  padding-top: 20px;
  border-right: #737BBB 2px;
}
.sidenav a{
  text-align: left;
  padding: 6px 1px 6px 25px;
  text-decoration: none;
  font-size: 16px;
  color: #737BBB;
  display: block;
  margin-left: 5px;
}
</style>