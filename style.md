*
{
	padding: 0;
	margin: 0;
}

html
{
	scroll-behavior: smooth;
}

.header1
{
	width:100%;
	height:100vh;
	background-image:linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,0.1));
	background-repeat:no-repeat;
	background-size:cover;
}

/*-----Header Section-----*/

nav
{
	display: flex;
	width: 100% !important;
	height: 100px !important;
	margin-top: -30px !important;
	background:rgba(0,0,0,0.2);
	background: #0000000;
	color:white;
	display:flex;
	justify-content:space-between;
	align-items:center;
/*	text-transform:uppercase;*/
}

.main-nav li
{
	display: inline-block;
	list-style: none;
	margin-left: 40px;
	margin-top: 40px;
}

.main-nav li a
{
	padding: 5px 0;
	text-decoration: none;
	color: #fff;
	font-size: 20px;
}

.main-nav li a:hover
{
     border-bottom: 2px solid #00b894;

}

.header
{
	height: 100vh;
	width: 100%;
	display: flex;
	background-image: linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,0.1)),url(images/banner.jpg);
	background-size: cover;
	background-position: center;
	background-attachment: fixed;
	padding-top: 30px;
	text-align: center;
	color: #fff;
}

.header img
{
	width: 250px;
	margin-top: -10px;
	margin-left: -100px;
	float: left;
}

.login-btn
{
	width: 100px;
	padding: 8px 0;
	margin-top: 30px;
	outline: none !important;
	border: 2px solid #fff;
	border-radius: 50px;
	background: transparent;
	margin-right: -80px;
	color: #fff;
	float: right;
}

.header h1
{
	padding-top: 250px;
	padding-bottom: 0;
	font-size: 55px;
}

.header p
{
	margin: 18px 0;
}

.input-group
{
	width: 90% !important;
	max-width: 500px;
	border-radius: 30px;
	background: #fff;
	margin: auto;
	padding: 2px;
}

.form-control
{
	border: 0 !important;
	border-radius: 30px !important;
	margin: 2px;
	box-shadow: none !important;
}

.input-group-text
{
	width: 100px;
	background-image: linear-gradient(#00ff7e,#1f3d90);
	border: 0 !important;
	color: #fff !important;
	padding: 0 25px !important;
	border-radius: 30px !important;
	box-shadow: none !important;
}

.section1
{
	padding: 50px 0;
	background: #efefef;
}

/*-----About Us Section-----*/

.btn1
{
  color:black;
  display: inline-block;
  background:none;
  text-transform: uppercase;
  padding: 13px 20px;
  font-weight: bold;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  outline: 2.4px solid #6610f2;
  cursor: pointer;
  margin-top: 32px;
  transition: 0.5s;
}

.btn1:hover
{
  color: white;
  background-color: #6610f2;
  opacity:1;
  box-shadow: 0 14px 18px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
}

.about-picture 
{
  width: 100%;
  display: block;
  transition: 0.5s;
  border-radius: 16px;
}

.picture-container: hover .about-picture 
{
     opacity: 0.8;
}

.section-subtitle
{
	color: #bd1220;
    font-family: Sketchimport;
    word-spacing: 5px;
}

.section-title
{
	font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    margin: 0;
    padding: 30px solid #6610f2;
    box-sizing: border-box;
}

.about-text 
{
     margin: 16px 0;
     max-width: 416px;
     color: black;
}

.about-img,
.about-info
{
     margin-top: 30px;
     float: left;
     width: 50%;
     padding: 32px;
}

/*-----Discover-Destination Banner-----*/

.banner
{
	height: 50vh; 
	background-image: url(images/banner2.jpg);
	background-position: center;
	position: relative;
	background-size: cover;
	background-attachment: fixed;
}

.banner-highlights
{
	padding: 50px 0;
	background: rgba(0,0,0,0.60);
	color: #fff;
}

.menu-title 
{
    font-family: Oraqleimport;
    color: #bd1220;
    margin-top: 40px;
    line-height: 1.3;
    padding-top: 6.5%;
    text-align: justify;
    font-size: 65px;
}

.menu-subtitle 
{
    text-transform: uppercase;
    text-align: center;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: #fff;
    font-size: 40px;
}

/*-----Features-----*/

.features
{
	padding: 100px 0;
}

h1
{
	text-align: center;
	padding-bottom: 30px;
}

.feature-img img
{
	width: 100%;
}

.price
{
	width: 50px;
	height: 50px;
	background: #ff5722;
	color: #fff;
	font-weight: 600px;
	border-radius: 50%;
	padding: 10px;
	box-shadow: 0 0 10px 1px rgba(37,73,214,0.18);
	position: absolute;
	left: 20px;
	bottom: -25px;
}

.feature-img
{
	position: relative;
}

.rating
{
	padding: 3px;
	float: right;
	background: #fff;
	bottom: -1px;
	right: 0;
	position: absolute;
}

.features .fa
{
	font-size: 15px;
	color: #ff5722;
}

.feature-details 
{
	padding: 20px;
    text-align: justify;
}

.feature-details h4
{
	font-weight: 600;
	margin-top: 20px;
	text-align: justify;
}

.feature-details .fa
{
	margin-right: 5px;
}

.feature-box
{
	box-shadow: 0 0 20px 6px rgba(37,73,214,0.18);
	margin-bottom: 30px;
	cursor: pointer;
    border-radius: 20px;
    transition: 1s;
}

.feature-box:hover
{
    transform: scale(1.1);
}

/*-----Travelling Gallery-----*/

.gallery
{
	padding: 100px 0;
	background: #efefef;
}

.gallery-box img
{
	width: 100%;
	border-radius: 10px;
	cursor: pointer;
	transition: 1s;
	cursor: zoom-in;
}

.gallery-box img:hover
{
	transform: scale(1.1);
}

.gallery-box h4
{
    display: block;
	color: #fff;
	text-shadow: -2px 2px 2px #000;
	font-weight: 600;
	font-size: 20px;
	position: absolute;
	top: 50%;
	left: 50%; 
	transform: translate(-50%, -50%);
	cursor: pointer;
}

.gallery-box
{
	position: relative;
	margin-bottom: 30px;
}

/*-----Offer Banner-----*/

.banner1
{
	height: 80vh;
	background-image: url(images/banner1.jpg);
	background-position: center;
	background-size: cover;
	background-attachment: fixed;
	padding-top: 14%;
}

.banner1-highlights
{
	padding: 70px 0;
	background: rgba(0,0,0,0.85);
	text-align: center;
	color: #fff;
}

.booking-btn
{
	width: 120px;
	padding: 8px 0;
	outline: none !important;
	border: 2px solid #fff;
	border-radius: 50px;
	background: transparent;
	color: #fff;
	margin-top: 20px;
}

/*-----Our Services-----*/

.new 
{
	
	padding: 80px 0;
	margin-left: 50px;
	margin-right: 50px;
	font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
}

@import url('https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900');

body
{
	margin: 0;
	padding: 0;
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 100vh;
	background: #060c21;
	font-family: 'Poppins', sans-serif;
}

.container11
{
	position: relative;
	width: 100%;
	display: grid;
	grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
	grid-template-rows: auto;
	grid-gap: 0 40px;
}

.container11 .box
{
	margin-top: 30px;
	position: relative;
	height: 400px;
	background: #060c21;
	display: flex;
	justify-content: center;
	align-items: center;
	border: 1px solid #000;
}

.container11 .box:before
{
	content: '';
	position: absolute;
	top: -2px;
	left: -2px;
	right: -2px;
	bottom: -2px;
	background: #fff;
	transform: skew(2deg,2deg);
	z-index: -1;
}

.container11 .box:nth-child(1):before
{
	background: linear-gradient(315deg,#ff0057,#e64a19);
}

.container11 .box:nth-child(2):before
{
	background: linear-gradient(315deg,#89ff00,#00bcd4)	
}

.container11 .box:nth-child(3):before
{
	background: linear-gradient(315deg,#e91e63,#5d02ff)
}

.container11 .box:nth-child(4):before
{
	background: linear-gradient(315deg,#ff0000,#ffc107)
}

.container11 .box:after
{
	content: '';
	position: absolute;
	top: 0;
	left: 0;
	width: 50%;
	height: 100%;
	background: rgba(255,255,255,0.05);
	pointer-events: none;
}

.content
{
	position: relative;
	padding: 20px;
	transform: translateY(40px);
}

.box .content h2
{
	position: absolute;
	top: -60px;
	right: 20px;
	margin: 0;
	padding: 0;
	font-size: 10em;
	color: rgba(255,255,255,.05);
	transition: 0.5s;
}

.box:hover .content h2
{
	top: -140px;
}

.box .content h3
{
	margin: 0 0 10px;
	padding: 0;
	font-size: 24px;
	font-weight: 500;
	color: #fff;
}

.box .content p
{
	margin: 0;
	padding: 0;
	color: #fff;
	font-size: 16px;
}

.box .content a
{
	position: relative;
	margin: 20px 0 0;
	padding: 10px 20px;
	text-decoration: none;
	border: 1px solid #fff;
	display: inline-block;
	color: #fff;
	transition: 0.5s;
	transform: translateY(-40px);
	opacity: 0;
	visibility: hidden;
}

.box:hover .content a
{
	transform: translateY(0);
	opacity: 1;
	visibility: visible;
}

.box .content a:hover
{
	color: #000;
	background: #fff;
}

/*-----User Feedback-----*/

.users-feedback
{
	padding: 100px 0;
	text-align: justify;
	background: #efefef;
}

.user-review
{
	box-shadow: 0 0 10px 0 rgba(0, 0, 100, 0.2);
	padding-bottom: 50px;
	border-radius: 20px;
	text-align: center;
}

.user-review p
{
	padding: 50px 10px 10px 10px;
}

.users-feedback img
{
	width: 60px;
	height: 60px;
	border-radius: 50px;
	position: relative;
	margin: -30px 0 20px 40%;
}

.user-review p::before
{
	content: '\201d';
	display: block;
	position: absolute;
	font-size: 100px;
	color: #6495ed;
	font-family: sans-serif;
	left: 44%;
	top: -20px;
}

/*-----Footer-----*/

.footer
{
	padding: 60px 20px 4px;
	background-image: linear-gradient(#2d517d,#9500fd);
	color: #fff;
}

.footer-logo
{
	width: 170px;
	margin-bottom: 50px;
}

.footer .text
{
	text-align: justify-all;
	margin-top: -40px;
}

.footer h4
{
	text-align: left;
	margin-top: 5px;
	margin-bottom: 25px;
}

.footer p
{
	font-size: 12px;
	text-align: justify;
	padding-right: 30px;
	cursor: pointer;
}

.footer .row .fa
{
	padding-right: 20px;
	font-size: 15px;
}

.footer hr
{
	margin-top: 20px;
	background: #efefef;
}
