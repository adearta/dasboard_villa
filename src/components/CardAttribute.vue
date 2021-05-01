<template>
  <div class="row">
    <div class="col">
        <div class="cardA">
            <p class="titlecard">xxxx</p>
        </div>
    </div>

    <div class="col">
        <div class="cardA">
            <p class="titlecard">xxxx</p>
        </div>
    </div>
    <div class="col">
        <div class="cardA">
            <p class="titlecard">xxxx</p>
        </div>
    </div>
    <div class="col">
        <div class="cardA">
            <p class="titlecard">xxxx</p>
        </div>
    </div>
</div>
<!-- ro -->
<div class="rowA">
    <div class="colA">
        <div class="card">
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.</p>
        </div>
    </div>

    <div class="colB">
        <div class="cardB">
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even  </p>
        </div>
    </div>
</div>

<div class="rowC">
<div class="colC">
        <div class="cardC">
            <img class="diagram" alt="Vue logo" src="./../assets/diagram.png">
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc  </p>
        </div>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
img.diagram{
    height: 100%;
    width: 100%;
}
.rowA {margin: 0 -5px;}
.rowA:after {
  content: "";
  display: table;
  clear: both;
}
.colA {
  float: left;
  width: 59.5%;
  padding: 0 10px;
}
@media screen and (max-width: 600px) {
  .colA {
  float: left;
  width: 62%;
  padding: 0 10px;
  margin-right:2.5%;
 }
 .colC {
  float: left;
  width: 90%;
  padding: 0 10px;
}
/* .cardB{
    text-align: left;
    padding: 10px 20px 20px 20px;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    width: 0%;
    border-radius: 10px;
    background: white;
    margin-left: 180px;
    margin-top: 25px;

} */
}
.colB {
  float: left;
  width: 16%;
  padding: 0 10px;
  margin-left: 3.8%;
}
.card{
    text-align: left;
    padding: 10px 20px 20px 20px;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    width: 100%;
    border-radius: 10px;
    background: white;
    margin-left: 180px;
    margin-top: 25px;

}
.cardB{
    text-align: left;
    padding: 10px 20px 20px 20px;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    width: 100%;
    border-radius: 10px;
    background: white;
    margin-left: 180px;
    margin-top: 25px;

}
.rowC {margin: 0 -5px;}
.rowC:after {
  content: "";
  display: table;
  clear: both;
}
.colC {
  float: left;
  width: 81%;
  padding: 0 10px;
}
.cardC:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}
.cardC{
    text-align: left;
    padding: 10px 20px 20px 20px;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    width: 100%;
    border-radius: 10px;
    background: white;
    margin-left: 180px;
    margin-top: 25px;

}
.row {margin: 0 -5px;}
.row:after {
  content: "";
  display: table;
  clear: both;
}
.col {
  float: left;
  width: 20%;
  padding: 0 10px;
}
.cardA{
    text-align: left;
    padding: 10px 0 20px 20px;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    width: 90%;
    border-radius: 10px;
    background: white;
    margin-left: 180px;

}
.cardA:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}
p{
    font-size: 1.2vw;
    color: #737BBB;
    text-align: left;
    margin-left: 20px;
    font-weight: 400;
    /* margin */
}
.titlecard{
    font-weight: 400;
}
</style>