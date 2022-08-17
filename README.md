# menu.css
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,500;1,200;1,300;1,400&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
nav{
    display: flex;
    height: 80px;
    width: 100%;
    background-color: #01282e;
    align-items: center;
    justify-content: space-between;
    padding: 0 50px 0 100px;
    flex-wrap: wrap;
}
nav .logo{
    color: white;
    font-size: 35px;
    font-weight: 600;
}
nav ul{
    display: flex;
    flex-wrap: wrap;
    list-style: none;
}

nav ul li{
    margin: 0 5px;
    
}

nav ul li a{
    color: #f2f2f2;
    text-decoration: none;
    font-size: 18px;
    font-weight: 500;
    padding: 8px 15px;
    border-radius: 5px;
    letter-spacing: 1px;
    transition:all 0.3s ease;
}
nav ul li a.active,
nav ul li a:hover{
    background: #f88f06;
}

nav .menu-btn i{
    color: #fff;
    cursor: pointer;
    display: none;
}
@media (max-width: 920px) {
    nav .menu-btn i{
        display: block;
    }
    nav ul{
        position: fixed;
        top: 80px;
        left: -100%;
        background-color: #003840;
        height: 100vh;
        width: 100%;
        text-align: center;
        display: block;
        transition: all 0.3s ease;
    }
    nav ul.open{
        left: 0;
    }
    nav ul li{
        width: 100%;
        margin: 50px 0;
    }
    nav ul li a {
        font-size: 23px;
    }
    nav ul li a.active,
    nav ul li a:hover{
        background: none;
        color: #f88f06;
    }   
}

body{
	margin: 0; 
	width: 100%; 
}

* { margin: 0; padding: 0; }

#total{
	width: 100%; 
	height: auto;  
	margin: auto;  
}

#logo{
	width: auto;
	height: auto;
    float: left; 
	margin-left: 2%;
    margin-top: 16px;	
}
#menu{
	width: 100%; 
	height: 97px;
    float: left;	
	background-color: #fff;
	opacity:.9;
	position: fixed;
	z-index: 1;	
}

#links{
	float: left;
	height: auto;
	width: auto;
	margin-left: 55%;
	margin-top: 2%;
}
#links a{
	
	text-decoration: none;
	color: #363636;
	display: inline-block;
	padding: 10px 0px 5px 0px;
	font-family: 'Roboto', sans-serif;
	font-size: 14px;
	font-weight: bold;
	margin-left: 33px;
	margin-top: 5px;
}

#links a:hover{
	color:#6B8E23;
	border-bottom: solid #6b8e23 3px;
}

#banner {
	width: 100%;
	height: auto;
	float: left;
	margin-top: 97px;
}

.slider {
    display: block;
    height: 293px;
    width: 600px;
    margin: auto;
    margin-top: 20px;
    position: relative;
	float: left;
	border: solid 1px red;
 }

.slider li{
    list-style: none;
    position: absolute;
}

.slider img {
    margin: auto;
    height: auto;
    width: 100%;
	vertical-align: top;
 } 



#conteudo {
	width: 100%;
	height: auto;
	float: left;
	
}
#teste{
	width: 90%; 
	height: 250px; 
	float: left; 	
	margin-left: 5%; 
	margin-top: 4%; 
	margin-bottom: 5%;	
}

#teste img{ 
	float: left; 
	border-radius: 15px;
}

#c1{
	float: right;
	width: auto;
	height: auto;
	font-family:'Roboto', sans-serif;
	margin-right: 6%;
}



#c2{
	float: left;
	width: 70%;
	height: auto;
	font-family:'Roboto', sans-serif;
	margin-left: 14%;
	margin-top: 2%;
	margin-bottom: 2.5%;
}

#c2 h1{
	height: auto;
	float:left ;
	margin-left: 40%;
}

#c2 p{
	width: auto;
	height: auto;
	float: left ;
}
#c3 {
	width: auto;
	height: auto;
	margin-left: 23%;
}
#c3 img{
	margin-top: 15%;
	border-radius: 15px;
}
	* {box-sizing: border-box}

/* Container needed to position the overlay. Adjust the width as needed */
.QS {
  position: relative;
  width: 50%;
  max-width: 300px;
  
 
}

/* Make the image to responsive */
.image {
  width: 300px;
  height: 200px;
  border-radius: 15px;
}

/* The overlay effect - lays on top of the container and over the image */
.overlay {
  position: absolute; 
  bottom: 0; 
  background:rgb(176, 174, 174, 0.5);
  width: 300px;
  height: 25%;
  opacity: 0.8;
  transition: .5s ease;
  color: white;
  font-size: 20px;
  text-align: center;
  font-family:'Roboto', sans-serif;
  margin-top:20%;
  border-radius: 15px;
 
}

.overlay1 {
 position: absolute; 
  bottom: 0; 
  background:rgb(176, 174, 174, 0.5);
  width:700px;
  height: 7%;
  opacity: 0.8;
  transition: .5s ease;
  color: white;
  font-size: 20px;
  text-align: center;
  font-family:'Roboto', sans-serif;
  margin-top:20%;
  border-radius: 15px;
 
}

/* When you mouse over the container, fade in the overlay title */
.QS:hover .overlay1 {
  opacity: 1;
  background: #6B8E23;
  color: #f1f1f1;
}



* {box-sizing: border-box}

/* Container needed to position the overlay. Adjust the width as needed */
.container {
  position: relative;
  width: 50%;
  max-width: 300px;
  margin-bottom:18%;
}

/* Make the image to responsive */
.image {
  width: 300px;
  height: 200px;
  border-radius: 15px;

}

/* The overlay effect - lays on top of the container and over the image */
.overlay {
  position: absolute; 
  bottom: 0; 
  background:rgb(176, 174, 174, 0.5);
  width: 300px;
  height: 25%;
  opacity: 0.8;
  transition: .5s ease;
  color: white;
  font-size: 20px;
  text-align: center;
  padding: 12px;
  
 
}

/* When you mouse over the container, fade in the overlay title */
.container:hover .overlay {
  opacity: 1;
  background: #6B8E23;
  color: #f1f1f1;
}

#rodape{
	width: 100%;
	height: auto;
	float: left;
}
#r1{
	width: 100%;
	height: 100px;
	float: left;
	background-color: #6B8E23;
	margin-top: 3%;
}

#r2{
	width: 100%;
	height: 200px;
	float: left;
	background-color: #333333;
}

#r2 li{
	width: auto;
	height: auto;
	margin-bottom: 3%;
	display: inline-block;
	margin-left: 5%;
}

#r2 img{
 padding-right: 3px;
}

#r2 h3{
	color: #808080;
	font-size: 15px;
	margin-left: 0.2px;
	margin-top: 20px;	
}
#txt{
	float: left;
	font-size: 17px;
	color:  #fff;
	width: 94%;
	height: auto;
	margin-left: 5%;
	margin-top: 2%;
	font-family: 'Roboto', sans-serif;
}

#r3{
	width: 100%;
	height: 60px ;
	float: left;
	background-color:#222222;
}
#r3 p{
	width: auto;
	height: auto;
	line-height: 20px;
	text-align: center;
	font-family: 'Roboto', sans-serif;
	color: #808080;
	font-size: 13px;
	margin-top: 24px;		
}

.div-dog{
	width:50%;
	height: auto;
	background-color: rgba(255, 255, 255);
	float: left; 
	list-style:none;
	text-align: center;
	margin-top: 2%;
	margin-bottom: 3%;
}

.div-dog ul li{
	display:inline-block;
	margin: 2% 3% 2% 3%;
}
.div-dog ul li a{
	text-decoration: none;
}
.div-cat{
	width:50%;
	height: auto;
	background-color: rgba(255, 255, 255);
	float: left; 
	list-style:none;
	text-align: center;
	margin-top: 2%;
	margin-bottom: 2%;

}
.div-cat ul li{
	display:inline-block;
	margin:2% 3% 2% 3%;
}
.div-cat ul li a{
	text-decoration: none;
}
li.dog-img-1 h1{
	font-family: 'Roboto', sans-serif;
	font-size: 18px;
	margin-left: -24%;
	z-index: 1000;
	}
li.dog-img-1 img{
	border-radius:500px; 
	border: 3px solid rgb(107, 142, 35);
	padding: 5px;
	margin-left: -25%;
}

.hr{
	border: 0;
	height: 1px;
	width: 100%;
	background-image: linear-gradient(to right, rgba(0, 0, 0, 0), #D8D8D8, rgba(0, 0, 0, 0));
}
.mapa{
	float:left;
	width: 50%;
	height: auto;
	font-family: 'Roboto', sans-serif;
	margin-left: 6%;
	margin-top: 2%;
	color: #808080;
	
}

.doacoes{
	float:left;
	width: 100%;
	height: auto;
	font-family: 'Roboto', sans-serif;
	text-align: center;
	margin-top:3%;
}
#form{
	margin-top: 3%;
	margin-left: 12%;
	margin-bottom: 4%;
	width: auto;
	height: auto;
	float: left;
	font-family: 'Roboto', sans-serif;
}
#icons{
	width: 365px; 
	height: auto; 
	float: left;
	margin-left: 12%;
	margin-top: 4%; 
	-webkit-box-shadow: 10px 10px 17px 0px rgba(0,0,0,0.15);
	-moz-box-shadow: 10px 10px 17px 0px rgba(0,0,0,0.15);
	box-shadow: 10px 10px 17px 0px rgba(0,0,0,0.15);	
}
#icons2{
	width: auto; 
	height: 60px; 
	float: left;
	margin-top: 13px;
	margin-bottom: 13px;
	margin-left: 13px;
}
#icons2 img{
	float: left;
	width: 60px;
	height: 60px;
}
#icons2 p{
	font-size: 25px;
	font-family: 'Roboto', sans-serif;
	float: right;
	width: 260px;
	height: auto;
	color: #828282;
	margin-left: 13px;
	margin-top: 12px;
}
#map{
	float: left;
	margin-left: 7.5%;
	margin-top: 4%;
	margin-bottom: 4%;
}
#contato_t{
	font-family: 'Roboto', sans-serif;
	margin-left: 43%;
	width: auto;
	margin-top: 2%;
}
#titulo_servicos{
	float: left;
	font-family: 'Roboto', sans-serif;
	margin-left: 43%;
	width: auto;
	height: auto;
	margin-top: 2%;
}
#servicos{
	width: 270px; 
	height: auto; 
	float: left; 	 
	margin-left: 8%;

	/*background-color: rgb(220,220,220);*/
}
#servicos img{ 
	width: 260px; 
	height: 250px; 
	float: left;
	border-radius: 500px;
	border: 3px solid rgb(107, 142, 35);
	padding: 5px;
}
#titulo_petshop{
	float: left;
	font-family: 'Roboto', sans-serif;
	margin: 3% 0 0 45%;
	width: auto;
	height: auto;
}
#petshop{
	width: 90%; 
	height: 250px; 
	float: left; 	
	margin: 3% 0 5% 10%; 
}

#ps1 img{
	width: 260px; 
	height: 250px;  
	float: left;
	border-radius: 500px;
	border: 3px solid rgb(107, 142, 35);
	padding: 5px;
	margin-bottom: 5%;	
}
#ps1{
	float: left;
	width: 261px;
	height: auto;
	margin-left: 6%;
}

#ps1 h2{
	color: #828282;
	font-family: 'Roboto', sans-serif;
}
#descricoes{
	width: 100%;
	height: 250px;
	float: left;
	margin: 2% 0 2% 0;
}
#descricoes img{
	width: 260px; 
	height: 250px; 
	float: left;
	border-radius: 500px;
	border: 3px solid rgb(107, 142, 35);
	padding: 5px;
	margin-left: 5%;
}
#descricoes p{
	width: 68%;
	height: auto;
	float: left;
	font-family: 'Roboto', sans-serif;
	margin: 2% 0 0 3%;
}
#descricoes h2{
	width: auto;
	height: auto;
	float: left;
	color: #828282;
	font-family: 'Roboto', sans-serif;
	margin: 4% 0 0 3%;
}
#pet{
	width: auto;
	height: auto;
}
::-webkit-scrollbar{
	width: 10px;
}
::-webkit-scrollbar-track-piece{
	background-color: #ebebeb;
}
::-webkit-scrollbar-thumb{
	background-color:#828282;
	outline: 2px solid #ebebeb;
	outline-offset: -2px;
	border: .1px solid #828282;
}
::-webkit-scrollbar-thumb:hover{
    background-color:rgb(107, 142, 35);
    border: .1px solid rgb(107, 142, 35);
}
