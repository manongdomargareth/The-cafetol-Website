home1.css

*{
    margin: 0;
    padding: 0;
    font-family: Century Gothic;

}

header{
    background-image:linear-gradient(rgba(0,0,0),rgba(0,0,0,0.5)), url("bg1.jpg");
    height: 100vh;
    background-size: cover;
    background-position: center;
    overflow: hidden;
        

}

ul{
    float: right;
    list-style-type: none;
    margin-top: 50px;
    margin-right: 5%;
    padding-right: 20px;
    font-size: larger;

}

ul li{
    display: inline-block;

}

ul li a{

<!DOCTYPE html>
<html>  
<head>
   <title>The cafetol</title>
   <link rel="stylesheet" type="text/css" href="home1.css">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<body>
   <header>
     <nav>
         <div class="logo">
            <img src="logo.jpg">
         </div>
        <ul>
           <li><a href="home.html">Home</a></li>
           <li><a href="top-products.html">Top products</a></li>
           <li><a href="menu.html">Menu</a></li>
           <li><a href="branches.html">Branches</a></li>
          </ul>
     </nav>
      <div class="card">
         <h1><big>Welcome to our Website</big></h1>
         <br>
         <p>Looking for a cozy and inviting place to relax with a hot and ice cup of coffee or shake's and some delicious menu?</p>
             <br>
             <p>From our signature dishes to our weekly specials, everything is made with love and care. </p>
             <br>
             <p>Whether you spend five minutes or five hours with us, our goal is to make you feel right at home. So why not treat yourself today and visit our local café! You won't regret!</p>
             <br>
             <h1>7am-7pm</h1> 
      </div> 
    </header>
</body>
<footer class="footer-distributed">

      <div class="footer-left">

        <h3>The<span>Cafe</span>tol</h3>

        <p class="footer-company-name">The Cafetol © 2023</p>
      </div>

      <div class="footer-center">

        <div>
          <i class="fa fa-map-marker"></i>
          <p><span>Corner Luna, Velez St.</span> Cagayan de Oro, Philippines</p>
        </div>

        <div>
          <h4>Contact us:</h4>
          <i class="fa fa-phone"></i>
          <p>0999 506 3978</p>
        </div>

      </div>

      <div class="footer-right">

        <p class="footer-company-about">
          <span>About the company:</span>
          Coffee shops provide a cozy and welcoming environment for people to relax, socialize, and enjoy a variety of coffee-based drinks and snacks.
        </p>

        <div class="footer-icons">
          <p>Other social media links:</p>
          <a href="https://www.facebook.com/search/top/?q=the%20caf%C3%A9tol"><span class="fa fa-facebook-f"></span></a>
          <a href="https://www.instagram.com/thecafetol/?fbclid=IwAR3shx0XrEhCBf7bapKSa2SR6IzciNNZsh-offwGl1JzuOK1Tby64-7weIA"><i class="fa fa-instagram"></i></a>

        </div>

      </div>

    </footer>
</html>
    text-decoration: none;
    color: #fff;
    padding: 5px 20px;
    border: 1px solid transparent;
    transition: 0.5s ease ;
 
}

ul li a:hover{
    background-color: #fff ;
    color: #000;
}


.logo img{
    float: left;
    width: 100px;
    height: 100px;
    margin-left: 20px;
    margin-top: 20px;
    border-radius: 100px;

}


.title {
    position: fixed;
    top: 20%;
    left: 60%;
}

.title h1{
    color: #fff;
    font-size: 40px;
    text-align: center;
}

.card {
    width: 550px;
    height: 400px;
    display: inline-block;
    border-radius: 10px;
    padding: 15px 25px;
    box-sizing:border-box;
    cursor: pointer;
    margin: 5px 5px;
    color: #fff;    
    background-image: transparent;
    background-position: center;
    background-size: cover;
    margin-top: 10%;
    margin-right: 70%;
    transition: transform 0.5s ;
    line-height: normal;
    
}

.card:hover{
    transform: translateX(10px);

}

* {
  font-family: Century Gothic;

}

.footer-distributed{
  background: #3b301b;
  box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
  box-sizing: border-box;
  width: 100%;
  text-align: left;
  font: bold 16px Century Gothic;
  padding: 55px 50px;

}

.footer-distributed .footer-left,
.footer-distributed .footer-center,
.footer-distributed .footer-right{
  display: inline-block;
  vertical-align: top;

}

.footer-distributed .footer-left{
  width: 35%;

}


.footer-distributed h3{
  color:  #ffffff;
  font:36px 'Century Gothic';
  margin: 0;

}

.footer-distributed h3 span{
  color:  rgba(223, 202, 133, 0.836);

}


.footer-distributed .footer-links{
  color:  #ffffff;
  margin: 20px 0 12px;
  padding: 0;

}

.footer-distributed .footer-links a{
  display:inline-block;
  line-height: 1.8;
  font-weight:400;
  text-decoration: none;
  color:  inherit;

}

.footer-distributed .footer-company-name{
  color:  #92999f;
  font-size: 15px;
  font-weight: normal;
  margin: 0;

}

.footer-distributed .footer-center{
  width: 40%;

}

.footer-distributed .footer-center i{
  background-color:  #92999f;
  color: #fff;
  font-size: 15px;
  width: 35px;
  height: 35px;
  border-radius: 50%;
  text-align: center;
  line-height: 35px;
  margin-top: 10px;
  margin-left: 10px;
  margin-bottom: 15px;
  vertical-align: middle;

}

.footer-distributed .footer-center h4 {
    color:rgba(223, 202, 133, 0.836);
    margin-top: 15px;
    margin-left: 50px;
}

.footer-distributed .footer-center p{
  display: inline-block;
  color: #ffffff;
  font-weight:400;
  vertical-align: middle;
  margin:0;

}

.footer-distributed .footer-center p span{
  display:block;
  font-weight: normal;
  font-size:15px;
  line-height:2;

}

.footer-distributed .footer-right{
  width: 20%;

}

.footer-distributed .footer-company-about{
  line-height: 20px;
  color:  #fff;
  font-size: 15px;
  font-weight: normal;
  margin: 0;

}

.footer-distributed .footer-company-about span{
  display: block;
  color: rgba(223, 202, 133, 0.836);
  font-size: 15px;
  font-weight: bold;
  margin-bottom: 20px;

}

.footer-distributed .footer-icons{
  margin-top: 15px;


}

.footer-distributed .footer-icons p{
    display: block;
    color: rgba(223, 202, 133, 0.836);
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 5px;
}

.footer-distributed .footer-icons a{
  display: inline-block;
  width: 35px;
  height: 35px;
  cursor: pointer;
  background-color: #92999f;
  border-radius: 50px;

  font-size: 20px;
  color: #ffffff;
  text-align: center;
  line-height: 35px;
  margin-top: 10px;
  margin-right: 3px;
  margin-bottom: 5px;

}

top-products1.css

*{
    margin: 0;
    padding: 0;
    font-family: Century Gothic;
    
}

header{
    background-image:linear-gradient(rgba(0,0,0),rgba(0,0,0,0.5)), url("bg2.jpg");
    height: 100vh;
    background-size: cover;
    background-position: center;
    
}

ul{
    float: right;
    list-style-type: none;
    margin-top: 50px;
    margin-right: 5%;
    padding-right: 20px;
    font-size: larger;

}

ul li{
    display: inline-block;

}

ul li a{
    text-decoration: none;
    color: #fff;
    padding: 5px 20px;
    border: 1px solid transparent;
    transition: 0.5s ease ;
 
}

ul li a:hover{
    background-color: #fff ;
    color: #000;

}

ul li.active a{
    background-color: #fff;
    color: #000;

}

.logo img{
    float: left;
    width: 100px;
    height: 100px;
    margin-left: 20px;
    margin-top: 20px;
    border-radius: 100px;

}

.container {
    float: left;
    display: inline-block;
    box-sizing: border-box;
    cursor: pointer;
    background-position: center;
    background-size: cover;
    transition: transform 0.7s ;
    padding-top: 30px;
    padding-right: 30px;


}

.card1 {
    height: 500px;
    width: 300px;
    margin-top: 120px;
    box-shadow:  0px 0px 40px 0px #fff;
    background-color: #fff;
    background-position: center;
    background-size: cover;
    border-radius: 10px;
    background-image: url(snacks.jpg);   

}

.card2 {
    height: 500px;
    width: 300px;
    margin-top: 120px;
    box-shadow: 0px 0px 40px 0px  #fff;
    background-position: center ;
    background-size: cover;
    border-radius: 10px;
    background-image: url(meaal.jpg);

}

.card3 {
    height: 500px;
    width: 300px;
    margin-top: 47px;
    box-shadow: 0px 0px 40px 0px  #fff;
    background-position: center ;
    background-size: cover;
    border-radius: 10px;
    background-image: url(coffeee.jpg);

}

.card4 {
    height: 500px;
    width: 300px;
    margin-top: 47px;
    box-shadow: 0px 0px 40px 0px #fff;
    background-position: center ;
    background-size: cover;
    border-radius: 10px;
    background-image: url(fruitdrink.jpg);

}

.container:hover{
    transform: translateY(-10px);

}

* {
    font-family: Century Gothic;
  
  }
  
  .footer-distributed{
    background: #3b301b;
    box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
    box-sizing: border-box;
    width: 100%;
    text-align: left;
    font: bold 16px Century Gothic;
    padding: 55px 50px;
  
  }
  
  .footer-distributed .footer-left,
  .footer-distributed .footer-center,
  .footer-distributed .footer-right{
    display: inline-block;
    vertical-align: top;
  
  }
  
  .footer-distributed .footer-left{
    width: 35%;
  
  }
  
  
  .footer-distributed h3{
    color:  #ffffff;
    font:36px 'Century Gothic';
    margin: 0;
  
  }
  
  .footer-distributed h3 span{
    color:  rgba(223, 202, 133, 0.836);
  
  }
  
  
  .footer-distributed .footer-links{
    color:  #ffffff;
    margin: 20px 0 12px;
    padding: 0;
  
  }
  
  .footer-distributed .footer-links a{
    display:inline-block;
    line-height: 1.8;
    font-weight:400;
    text-decoration: none;
    color:  inherit;
  
  }
  
  .footer-distributed .footer-company-name{
    color:  #92999f;
    font-size: 15px;
    font-weight: normal;
    margin: 0;
  
  }
  
  .footer-distributed .footer-center{
    width: 40%;
  
  }
  
  .footer-distributed .footer-center i{
    background-color:  #92999f;
    color: #fff;
    font-size: 15px;
    width: 35px;
    height: 35px;
    border-radius: 50%;
    text-align: center;
    line-height: 35px;
    margin-top: 10px;
    margin-left: 10px;
    margin-bottom: 15px;
    vertical-align: middle;
  
  }
  
  .footer-distributed .footer-center h4 {
      color:rgba(223, 202, 133, 0.836);
      margin-top: 15px;
      margin-left: 50px;
  }
  
  .footer-distributed .footer-center p{
    display: inline-block;
    color: #ffffff;
    font-weight:400;
    vertical-align: middle;
    margin:0;
  
  }
  
  .footer-distributed .footer-center p span{
    display:block;
    font-weight: normal;
    font-size:15px;
    line-height:2;
  
  }
  
  .footer-distributed .footer-right{
    width: 20%;
  
  }
  
  .footer-distributed .footer-company-about{
    line-height: 20px;
    color:  #fff;
    font-size: 15px;
    font-weight: normal;
    margin: 0;
  
  }
  
  .footer-distributed .footer-company-about span{
    display: block;
    color: rgba(223, 202, 133, 0.836);
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 20px;
  
  }
  
  .footer-distributed .footer-icons{
    margin-top: 15px;
  
  
  }
  
  .footer-distributed .footer-icons p{
      display: block;
      color: rgba(223, 202, 133, 0.836);
      font-size: 15px;
      font-weight: bold;
      margin-bottom: 5px;
  }
  
  .footer-distributed .footer-icons a{
    display: inline-block;
    width: 35px;
    height: 35px;
    cursor: pointer;
    background-color: #92999f;
    border-radius: 50px;
  
    font-size: 20px;
    color: #ffffff;
    text-align: center;
    line-height: 35px;
    margin-top: 10px;
    margin-right: 3px;
    margin-bottom: 5px;
  
  }
  
  menu1.css
  
  *{
    margin: 0;
    padding: 0;
    font-family: Century Gothic;

}

header{
    background-image:linear-gradient(rgb(0, 0, 0),rgb(0, 0, 0, 0.5)), url("bg3.jpg");
    height: 100vh;
    background-size: cover;
    background-position: center;

}

ul{
    float: right;
    list-style-type: none;
    margin-top: 50px;
    margin-right: 5%;
    padding-right: 20px;
    font-size: larger;

}

ul li{
    display: inline-block;

}

ul li a{
    text-decoration: none;
    color: #fff;
    padding: 5px 20px;
    border: 1px solid transparent;
    transition: 0.5s ease ;
 
}

ul li a:hover{
    background-color: #fff ;
    color: #000;

}

ul li.active a{
    background-color: #fff;
    color: #000;

}

.logo img{
    float: left;
    width: 100px;
    height: 100px;
    margin-left: 20px;
    margin-top: 20px;
    border-radius: 100px;

}

.container {
    float: left;
    display: inline-block;
    box-sizing: border-box;
    cursor: pointer;
    background-position: center;
    background-size: cover;
    transition: transform 0.5s ;
    padding-left: 10px;
    padding-top: 30px;
    

    
}

.card1 {
    height: 465px;
    width: 300px;
    margin-top: 129px;
    border-radius: 10px;
    box-shadow: 0px 0px 20px 0px #fff;
    background-position: center;
    background-size: cover;
    background-image: url(menu1.jpg);

}

.card2 {
    height: 465px;
    width: 300px;
    margin-top: 100px;
    border-radius: 10px;
    box-shadow: 0px 0px 20px 0px#fff;
    background-position: center ;
    background-size: cover;
    background-image: url(menu2.jpg);

}

.card3 {
    height: 465px;
    width: 300px;
    margin-top: 54px;
    border-radius: 10px;
    box-shadow: 0px 0px 20px 0px #fff;
    background-position: center ;
    background-size: cover;
    background-image: url(menu3.jpg);

}

.card4 {
    height: 465px;
    width: 300px;
    border-radius: 10px;
    margin-top: 26px;
    padding-right: 10px;
    box-shadow: 0px 0px 10px 0px #fff;
    background-position: center ;
    background-size: cover;
    background-image: url(menu4.jpg);

}

.container:hover{
    transform: translateY(-10px);

}

* {
    font-family: Century Gothic;
  
  }
  
  .footer-distributed{
    background: #3b301b;
    box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
    box-sizing: border-box;
    width: 100%;
    text-align: left;
    font: bold 16px Century Gothic;
    padding: 55px 50px;
  
  }
  
  .footer-distributed .footer-left,
  .footer-distributed .footer-center,
  .footer-distributed .footer-right{
    display: inline-block;
    vertical-align: top;
  
  }
  
  .footer-distributed .footer-left{
    width: 35%;
  
  }
  
  
  .footer-distributed h3{
    color:  #ffffff;
    font:36px 'Century Gothic';
    margin: 0;
  
  }
  
  .footer-distributed h3 span{
    color:  rgba(223, 202, 133, 0.836);
  
  }
  
  
  .footer-distributed .footer-links{
    color:  #ffffff;
    margin: 20px 0 12px;
    padding: 0;
  
  }
  
  .footer-distributed .footer-links a{
    display:inline-block;
    line-height: 1.8;
    font-weight:400;
    text-decoration: none;
    color:  inherit;
  
  }
  
  .footer-distributed .footer-company-name{
    color:  #92999f;
    font-size: 15px;
    font-weight: normal;
    margin: 0;
  
  }
  
  .footer-distributed .footer-center{
    width: 40%;
  
  }
  
  .footer-distributed .footer-center i{
    background-color:  #92999f;
    color: #fff;
    font-size: 15px;
    width: 35px;
    height: 35px;
    border-radius: 50%;
    text-align: center;
    line-height: 35px;
    margin-top: 10px;
    margin-left: 10px;
    margin-bottom: 15px;
    vertical-align: middle;
  
  }
  
  .footer-distributed .footer-center h4 {
      color:rgba(223, 202, 133, 0.836);
      margin-top: 15px;
      margin-left: 50px;
  }
  
  .footer-distributed .footer-center p{
    display: inline-block;
    color: #ffffff;
    font-weight:400;
    vertical-align: middle;
    margin:0;
  
  }
  
  .footer-distributed .footer-center p span{
    display:block;
    font-weight: normal;
    font-size:15px;
    line-height:2;
  
  }
  
  .footer-distributed .footer-right{
    width: 20%;
  
  }
  
  .footer-distributed .footer-company-about{
    line-height: 20px;
    color:  #fff;
    font-size: 15px;
    font-weight: normal;
    margin: 0;
  
  }
  
  .footer-distributed .footer-company-about span{
    display: block;
    color: rgba(223, 202, 133, 0.836);
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 20px;
  
  }
  
  .footer-distributed .footer-icons{
    margin-top: 15px;
  
  
  }
  
  .footer-distributed .footer-icons p{
      display: block;
      color: rgba(223, 202, 133, 0.836);
      font-size: 15px;
      font-weight: bold;
      margin-bottom: 5px;
  }
  
  .footer-distributed .footer-icons a{
    display: inline-block;
    width: 35px;
    height: 35px;
    cursor: pointer;
    background-color: #92999f;
    border-radius: 50px;
  
    font-size: 20px;
    color: #ffffff;
    text-align: center;
    line-height: 35px;
    margin-top: 10px;
    margin-right: 3px;
    margin-bottom: 5px;
  
  }
  
  branches1.css
  
  *{
    margin: 0;
    padding: 0;
    font-family: Century Gothic;

}

header{
    background-image:linear-gradient(rgba(0,0,0),rgba(0,0,0,0.5)), url("bgimage1.jpg");
    height: 100vh;
    background-size: cover ;
    background-position: center;

}

ul{
    float: right;
    list-style-type: none;
    margin-top: 50px;
    margin-right: 5%;
    padding-right: 20px;
    font-size: larger;
    
}

ul li{
    display: inline-block;

}

ul li a{
    text-decoration: none;
    color: #fff;
    padding: 5px 20px;
    border: 1px solid transparent;
    transition: 0.5s ease ;
 
}

ul li a:hover{
    background-color: #fff ;
    color: #000;

}

ul li.active a{
    background-color: #fff;
    color: #000;

}

.logo img{
    float: left;
    width: 100px;
    height: 100px;
    margin-left: 20px;
    margin-top: 20px;
    border-radius: 100px;

}

* {
    font-family: 'Century Gothic';
}

.container {
   float:left;
   box-sizing: border-box;
   cursor: pointer;
   transition: transform 0.5s ;
   padding-top: 50px;
   padding-left: 160px;

}

.card1 {
    height: 400px;
    width: 300px;
    padding-left: 100px;
    border-radius: 10px;
    margin-top: 100px;
    background-color: #fff;
    box-shadow: 0px 0px 20px 0px #fff;
    background-size: cover;
    background-position: center;
    background-image: url(malasag.png);
    transform: translateY(25px);

}

.card2 {
    height: 400px;
    width: 300px;
    padding-left: 100px;
    border-radius: 10px;
    margin-top: 51px;
    box-shadow: 0px 0px 20px 0px #fff;
    background-size: cover;
    background-position: center;
    background-image: url(citihomes.png);
    

}

.card3 {
    height: 60px;
    width: 400px;
    padding-left: 130px;
    border-radius: 10px;
    color:#fff;

}

.card3 h2 {
    font-family: 'Century Gothic';

}

.card4 {
    height: 60px;
    width: 400px;
    border-radius: 10px;    
    color: #fff;

}

.card4 h2 {
    font-family: 'Century Gothic';

}

.container:hover{
    transform: translateY(-10px);

}

* {
    font-family: Century Gothic;
  
  }
  
  .footer-distributed{
    background: #3b301b;
    box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
    box-sizing: border-box;
    width: 100%;
    text-align: left;
    font: bold 16px Century Gothic;
    padding: 55px 50px;
  
  }
  
  .footer-distributed .footer-left,
  .footer-distributed .footer-center,
  .footer-distributed .footer-right{
    display: inline-block;
    vertical-align: top;
  
  }
  
  .footer-distributed .footer-left{
    width: 35%;
  
  }
  
  
  .footer-distributed h3{
    color:  #ffffff;
    font:36px 'Century Gothic';
    margin: 0;
  
  }
  
  .footer-distributed h3 span{
    color:  rgba(223, 202, 133, 0.836);
  
  }
  
  
  .footer-distributed .footer-links{
    color:  #ffffff;
    margin: 20px 0 12px;
    padding: 0;
  
  }
  
  .footer-distributed .footer-links a{
    display:inline-block;
    line-height: 1.8;
    font-weight:400;
    text-decoration: none;
    color:  inherit;
  
  }
  
  .footer-distributed .footer-company-name{
    color:  #92999f;
    font-size: 15px;
    font-weight: normal;
    margin: 0;
  
  }
  
  .footer-distributed .footer-center{
    width: 40%;
  
  }
  
  .footer-distributed .footer-center i{
    background-color:  #92999f;
    color: #fff;
    font-size: 15px;
    width: 35px;
    height: 35px;
    border-radius: 50%;
    text-align: center;
    line-height: 35px;
    margin-top: 10px;
    margin-left: 10px;
    margin-bottom: 15px;
    vertical-align: middle;
  
  }
  
  .footer-distributed .footer-center h4 {
      color:rgba(223, 202, 133, 0.836);
      margin-top: 15px;
      margin-left: 50px;
  }
  
  .footer-distributed .footer-center p{
    display: inline-block;
    color: #ffffff;
    font-weight:400;
    vertical-align: middle;
    margin:0;
  
  }
  
  .footer-distributed .footer-center p span{
    display:block;
    font-weight: normal;
    font-size:15px;
    line-height:2;
  
  }
  
  .footer-distributed .footer-right{
    width: 20%;
  
  }
  
  .footer-distributed .footer-company-about{
    line-height: 20px;
    color:  #fff;
    font-size: 15px;
    font-weight: normal;
    margin: 0;
  
  }
  
  .footer-distributed .footer-company-about span{
    display: block;
    color: rgba(223, 202, 133, 0.836);
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 20px;
  
  }
  
  .footer-distributed .footer-icons{
    margin-top: 15px;
  
  
  }
  
  .footer-distributed .footer-icons p{
      display: block;
      color: rgba(223, 202, 133, 0.836);
      font-size: 15px;
      font-weight: bold;
      margin-bottom: 5px;
  }
  
  .footer-distributed .footer-icons a{
    display: inline-block;
    width: 35px;
    height: 35px;
    cursor: pointer;
    background-color: #92999f;
    border-radius: 50px;
  
    font-size: 20px;
    color: #ffffff;
    text-align: center;
    line-height: 35px;
    margin-top: 10px;
    margin-right: 3px;
    margin-bottom: 5px;
  
  }
  
 <!DOCTYPE html>
<html>  
<head>
   <title>The cafetol</title>
   <link rel="stylesheet" type="text/css" href="home1.css">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<body>
   <header>
     <nav>
         <div class="logo">
            <img src="logo.jpg">
         </div>
        <ul>
           <li><a href="home.html">Home</a></li>
           <li><a href="top-products.html">Top products</a></li>
           <li><a href="menu.html">Menu</a></li>
           <li><a href="branches.html">Branches</a></li>
          </ul>
     </nav>
      <div class="card">
         <h1><big>Welcome to our Website</big></h1>
         <br>
         <p>Looking for a cozy and inviting place to relax with a hot and ice cup of coffee or shake's and some delicious menu?</p>
             <br>
             <p>From our signature dishes to our weekly specials, everything is made with love and care. </p>
             <br>
             <p>Whether you spend five minutes or five hours with us, our goal is to make you feel right at home. So why not treat yourself today and visit our local café! You won't regret!</p>
             <br>
             <h1>7am-7pm</h1> 
      </div> 
    </header>
</body>
<footer class="footer-distributed">

      <div class="footer-left">

        <h3>The<span>Cafe</span>tol</h3>

        <p class="footer-company-name">The Cafetol © 2023</p>
      </div>

      <div class="footer-center">

        <div>
          <i class="fa fa-map-marker"></i>
          <p><span>Corner Luna, Velez St.</span> Cagayan de Oro, Philippines</p>
        </div>

        <div>
          <h4>Contact us:</h4>
          <i class="fa fa-phone"></i>
          <p>0999 506 3978</p>
        </div>

      </div>

      <div class="footer-right">

        <p class="footer-company-about">
          <span>About the company:</span>
          Coffee shops provide a cozy and welcoming environment for people to relax, socialize, and enjoy a variety of coffee-based drinks and snacks.
        </p>

        <div class="footer-icons">
          <p>Other social media links:</p>
          <a href="https://www.facebook.com/search/top/?q=the%20caf%C3%A9tol"><span class="fa fa-facebook-f"></span></a>
          <a href="https://www.instagram.com/thecafetol/?fbclid=IwAR3shx0XrEhCBf7bapKSa2SR6IzciNNZsh-offwGl1JzuOK1Tby64-7weIA"><i class="fa fa-instagram"></i></a>

        </div>

      </div>

    </footer>
</html>


<!DOCTYPE html>
<html>
<head>
   <title>The cafetol</title>
   <link rel="stylesheet" type="text/css" href="top-products1.css">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<body>
   <header>
      <nav>
         <div class="logo">
            <img src="logo.jpg">
         </div>
        <ul>
           <li><a href="home.html">Home</a></li>
           <li><a href="top-products.html">Top products</a></li>
           <li><a href="menu.html">Menu</a></li>
           <li><a href="branches.html">Branches</a></li>
        </ul>
      </nav> 
      <div class="container">
         <div class="card card1">

         </div>
      </div>

      <div class="container">
         <div class="card card2">
           
         </div>
      </div>

      <div class="container">
         <div class="card card3">
         
         </div>
      </div>
      
      <div class="container">
         <div class="card card4">
         
        </div>
      </div>    
   </header>
   <footer class="footer-distributed">

      <div class="footer-left">

        <h3>The<span>Cafe</span>tol</h3>

        <p class="footer-company-name">The Cafetol © 2023</p>
      </div>

      <div class="footer-center">

        <div>
          <i class="fa fa-map-marker"></i>
          <p><span>Corner Luna, Velez St.</span> Cagayan de Oro, Philippines</p>
        </div>

        <div>
          <h4>Contact us:</h4>
          <i class="fa fa-phone"></i>
          <p>0999 506 3978</p>
        </div>

      </div>

      <div class="footer-right">

        <p class="footer-company-about">
          <span>About the company</span>
          Coffee shops provide a cozy and welcoming environment for people to relax, socialize, and enjoy a variety of coffee-based drinks and snacks.
        </p>

        <div class="footer-icons">
          <p>Other social media links:</p>
          <a href="https://www.facebook.com/search/top/?q=the%20caf%C3%A9tol"><span class="fa fa-facebook-f"></span></a>
          <a href="https://www.instagram.com/thecafetol/?fbclid=IwAR3shx0XrEhCBf7bapKSa2SR6IzciNNZsh-offwGl1JzuOK1Tby64-7weIA"><i class="fa fa-instagram"></i></a>

        </div>

      </div>

    </footer>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
   <title>The cafetol</title>
   <link rel="stylesheet" type="text/css" href="branches1.css">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<body>
   <header>
    <div>
      <nav>
        <div class="logo">
          <img src="logo.jpg">
       </div>
        <ul>
         <li><a href="home.html">Home</a></li>
         <li><a href="top-products.html">Top products</a></li>
         <li><a href="menu.html">Menu</a></li>
         <li><a href="branches.html">Branches</a></li>
        </ul>
      </nav> 
    </nav> 
    <div class="container">
           <div class="card card1">
            
           </div>
    </div>
    <div class="container">
      <div class="card card2">
         
      </div>
    </div>
    <div class="container">
           <div class="card card3">
            <h2>Malasag, Cugman, Cagayan de Oro City</h2>
           </div>       
    </div> 
    <div class="container">
      <div class="card card4">
        <h2>Citihomes, Malang Opol, Misamis Oriental</h2>
      </div>
    </div>
   </header>
   <footer class="footer-distributed">

    <div class="footer-left">

      <h3>The<span>Cafe</span>tol</h3>

      <p class="footer-company-name">The Cafetol © 2023</p>
    </div>

    <div class="footer-center">

      <div>
        <i class="fa fa-map-marker"></i>
        <p><span>Corner Luna, Velez St.</span> Cagayan de Oro, Philippines</p>
      </div>

      <div>
        <h4>Contact us:</h4>
        <i class="fa fa-phone"></i>
        <p>0999 506 3978</p>
      </div>

    </div>

    <div class="footer-right">

      <p class="footer-company-about">
        <span>About the company</span>
        Coffee shops provide a cozy and welcoming environment for people to relax, socialize, and enjoy a variety of coffee-based drinks and snacks.
      </p>

      <div class="footer-icons">
        <p>Other social media links:</p>
        <a href="https://www.facebook.com/search/top/?q=the%20caf%C3%A9tol"><span class="fa fa-facebook-f"></span></a>
        <a href="https://www.instagram.com/thecafetol/?fbclid=IwAR3shx0XrEhCBf7bapKSa2SR6IzciNNZsh-offwGl1JzuOK1Tby64-7weIA"><i class="fa fa-instagram"></i></a>

      </div>

    </div>

  </footer>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
   <title>The cafetol</title>
   <link rel="stylesheet" type="text/css" href="menus1.css">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">


</head>
<body>
   <header>
      <nav>
         <div class="logo">
            <img src="logo.jpg">
         </div>
        <ul>
           <li><a href="home.html">Home</a></li>
           <li><a href="top-products.html">Top products</a></li>
           <li><a href="menu.html">Menu</a></li>
           <li><a href="branches.html">Branches</a></li>
        </ul>
      </nav> 
      <div class="container">
             <div class="card card1">
                <h1></h1>
             </div>
      </div>
      <div class="container">
             <div class="card card2">
               <h1></h1>
             </div>
      </div>       
      <div class="container">
             <div class="card card3">
                <h1></h1>
             </div>
      </div>
      <div class="container">
             <div class="card card4">
                <h1></h1>
             </div>

      </div>
   </header>
   <footer class="footer-distributed">

      <div class="footer-left">

        <h3>The<span>Cafe</span>tol</h3>

        <p class="footer-company-name">The Cafetol © 2023</p>
      </div>

      <div class="footer-center">

        <div>
          <i class="fa fa-map-marker"></i>
          <p><span>Corner Luna, Velez St.</span> Cagayan de Oro, Philippines</p>
        </div>

        <div>
          <h4>Contact us:</h4>
          <i class="fa fa-phone"></i>
          <p>0999 506 3978</p>
        </div>

      </div>

      <div class="footer-right">

        <p class="footer-company-about">
          <span>About the company</span>
          Coffee shops provide a cozy and welcoming environment for people to relax, socialize, and enjoy a variety of coffee-based drinks and snacks.
        </p>

        <div class="footer-icons">
         <p>Other social media links:</p>
          <a href="https://www.facebook.com/search/top/?q=the%20caf%C3%A9tol"><span class="fa fa-facebook-f"></span></a>
          <a href="https://www.instagram.com/thecafetol/?fbclid=IwAR3shx0XrEhCBf7bapKSa2SR6IzciNNZsh-offwGl1JzuOK1Tby64-7weIA"><i class="fa fa-instagram"></i></a>

        </div>

      </div>

    </footer>
</body>
</html>
