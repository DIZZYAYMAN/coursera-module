<!DOCTYPE html>
<html>
<head>

<title>module 2</title>
<link rel="stylesheet" type="text/css" href="style.css">
<style>
* {
    box-sizing: border-box;
  }
  
  body{
      margin: 0;
      padding: 0;
    font-family: "Comic Sans MS", cursive, sans-serif;
  }
  
  .row{
    margin-top: 5%;
    margin-bottom: 5%;
  }
  
  h1 {
    margin-bottom: 15px;
    text-align: center;
    color: #ff4532;
    font-size: 50px;
  }
  
  
  .box{
    width: 100%;
    overflow: none;
  }
  
  
  .content-name{
    overflow: none;
    text-align: center;
    border: 4px solid rgb(0, 0, 0);
    width: 100px;
    height: 40px;
    padding: 5px;
    float: right;
    margin-right: 36px;
    margin-top: 0px;
    font-weight: bold;
    position: relative;
  }
  
  .content{
    border: 5px solid rgb(85, 14, 14);
    width: 90%;
    height: auto;
    margin: 2.5%;
    color: black
  }
  
  .name1{
    background-color: #3cff00;
  }
  
  .name2{
    color: white;
    background-color: #085bf5;
  }
  .name3{
    background-color: #FFFF00;
  }
  
  
  /********** big devices only **********/
  @media screen and (min-width: 992px) {
    .col-lg-4 {
        float: left;
      width: 33.33%;
    }
  }

  /************ small devices only ***********/
  @media screen and (min-width: 0px) and (max-width: 700px) {
    .col-sm-12 {
        float: left;
        width: 100%;
        
    }
  }
  /********** Medium devices only **********/
@media screen and (min-width: 768px) and (max-width: 991px) {
  .col-md-6,.col-md-12 {
    float: left;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-12 {
    margin-left: -10px;
    width: 100%;
  }    
  .name3 {
    margin-right: 65px;
    width: 100px;
  }
}</style>
</head>
<body>
<h1>Our Menu</h1>



<div class="col-lg-4 col-md-6 col-sm-12">
  	<div class="box">
  		<p class="content-name name1">Chicken</p>
  		<p class="content">Le client doit être très content, c'est un bon client. La bonne fortune d'Énée a besoin de douleur. Masse de jasmin. Avec leurs compagnons, les montagnes donneront naissance à des plumes et à de grandes poussées, et une souris ridicule naîtra. Jusque-là, combien de chats, d'ultricies et pas, les gamins du foot, à qui le prix, la salade. Il n'y a d'effet de masse pour personne.</p>
  	</div>
  </div>

  <div class="col-lg-4 col-md-6 col-sm-12">
  	<div class="box">
   		<p class="content-name name2">Beef</p>
   		<p class="content">Le client doit être très content, c'est un bon client. La bonne fortune d'Énée a besoin de douleur. Masse de jasmin. Avec leurs compagnons, les montagnes donneront naissance à des plumes et à de grandes poussées, et une souris ridicule naîtra. Jusque-là, combien de chats, d'ultricies et pas, les gamins du foot, à qui le prix, la salade. Il n'y a d'effet de masse pour personne.</p>
  	</div>
  </div>

  <div class="col-lg-4 col-md-12 col-sm-12">
  	<div class="box">
  		<p class="content-name name3">Sushi</p>
  		<p class="content">Le client doit être très content, c'est un bon client. La bonne fortune d'Énée a besoin de douleur. Masse de jasmin. Avec leurs compagnons, les montagnes donneront naissance à des plumes et à de grandes poussées, et une souris ridicule naîtra. Jusque-là, combien de chats, d'ultricies et pas, les gamins du foot, à qui le prix, la salade. Il n'y a d'effet de masse pour personne.</p>
  	</div>	
  </div>

</body>
</html>
