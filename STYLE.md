###############################

version 1.0
- bad #wrap position (text goes above divs height)
- 3 wraps included


###############################






body {
  background-color:#000;
  color:#333;
  font: normal 14px "Open Sans", sans-serif;
  margin:0;
}

h1,h2,h3,p,li {
  text-align:left;	
}

a {
  background-color:inherit;
  color:#333;
  text-decoration:none; 
}

a:hover {
  text-decoration:underline; 
}	

#desno {
  float:right;
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 35%;
}

blockquote {
font: italic 18px "Times New Roman",serif;
width: 70%;
margin: 5px auto;
padding: 10px 50px;
position: relative;
color: red;
}
	

blockquote:before {
display: block;
content: "\201c";
font: bold 120px "Times New Roman", serif;
position: absolute;
left: -20px;
top: -10px;
color: #690;
}

/* odavde */
/* Container holding the image and the text 
.container {
  width: 1500px;
  display: flex;
  position: relative;
  text-align: center;
  color: white;
}

/* Centered text 
.centered {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: black;
}

/* dovde */

#pseudo-wrap1 {
background: red;
background: -moz-linear-gradient(top,  #bc0000 1%, #c80000 78%);
background: -webkit-linear-gradient(top,  #bc0000 1%,#c80000 78%);
background: linear-gradient(to bottom,  #bc0000 1%,#c80000 78%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#80bc00', endColorstr='#8fc800',GradientType=0 );
height: 210px;
margin:0;
width:100%;
z-index:-100;
position:absolute;
top:0px; left:0; right:0;
}

#pseudo-wrap2 {
background: #b50303;
background: -moz-linear-gradient(top,  #b50303 0%, #000000 98%);
background: -webkit-linear-gradient(top,  #b50303 0%,#000000 98%);
background: linear-gradient(to bottom,  #b50303 0%,#000000 98%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#88b503', endColorstr='#000000',GradientType=0 );
height: 300px;
margin:0;
width:100%;
z-index:-100;
position:absolute;
top:211px; left:0; right:0;
}
/* height and width of blank page */
#wrap {
  height:1300px;
  width:80%;
  background-color:#fff;
  color:inherit;
  padding:0;
  margin:30px auto 30px auto; 
}

#wrap2 {
  height:1400px;
  width:80%;
  background-color:#fff;
  color:inherit;
  padding:0;
  margin:30px auto 30px auto;
}

#wrap3 {
  height:5000px;
  width:80%;
  background-color:#fff;
  color:inherit;
  padding:0;
  margin:30px auto 30px auto;
}

#header {
  background: #b50c0c;
  background: -moz-linear-gradient(top,  #b50c0c 0%, #a81010 50%, #a80000 51%, #8e0707 100%);
  background: -webkit-linear-gradient(top,  #b50c0c 0%,#a81010 50%,#a80000 51%,#8e0707 100%);
  background: linear-gradient(to bottom,  #ec0c0c 0%,#a81010 50%,#a80000 51%,#7a0202 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#7fb50c', endColorstr='#568e07',GradientType=0 );
  color:#fff;
  height:200px;
  -webkit-box-shadow: 0px 40px 20px -15px #202020;
  -moz-box-shadow: 0px 40px 20px -15px #333333;
  box-shadow: 0px 40px 20px -15px #5c5c5c;
  border:5px solid #fff;
  border-bottom:0px solid #fff;
}

#header h1 {	
  text-align:center;
  padding:0;
  margin:60px auto 0 auto; 
}

#header a
{	background-color:inherit;
	color:#fff;
	text-decoration:none; }
	
#header p
{	text-align:center;
	margin:0 auto; }

nav {
  text-align:center;
  margin:15px auto;
}
	
ul#menu {
    list-style-type: none;
    margin: 0 auto;
    display: table;
    padding: 0;
    overflow: hidden;
    width:50%;

    }

ul#menu li  
 { 	display: table-cell;
    text-align:center;  }
   
ul#menu li a {
    background-color:inherit;
    color: #000;
    /*display:block;*/
    padding:10px;
    text-decoration:none;
    font-weight:bold;
    margin:0 1px;
}

ul#menu li a:hover,ul#menu li a.current
{	background-color:#fff;
	color:#000;	}
	
/* Content */
#content
{	text-align:left;
	width:90%;
	padding:0 25px 10px 25px;
	margin:0 auto;	}
	
#content h2
{	
	padding:0;
	margin:0 auto; }	

#content h3
{	background-color:inherit;
	color:rgb(153, 0, 0);
	font:bold 12pt Arial,sans-serif;	
	padding:0;	}

#content span.author
{	font:normal 8pt Arial,Helvetica,sans-serif;
	background-color:inherit;
	color:#666;	}

#content span.author a
{	background-color:inherit;
	color:#999;
	text-decoration:none;
	padding:0 3px; }

#content span.author a:hover
{	background-color:#690;
	color:#fff;	}

#content p a
{	background-color:inherit;
	color:rgb(153, 0, 0);
	text-decoration:underline;	} 	
	
#content p
{	text-align:justify;
	line-height:24px; }

#content p.center { text-align: center; }
	
#content li
{	line-height:24px;	}

#content li a
{	background-color:inherit;
	color:rgb(153, 0, 0);
	text-decoration:none;	}

#content li a:hover
{	text-decoration:underline; }

#content ul {
  list-style:none;
  padding:0;
}
	
#content ul li
{	list-style-position:inside;
    text-indent: 0px;
	padding-left:20px;
	margin:0; }	
	
#content ul li:before {
  content: "\27a1 \00a0 \00a0";
  background-color:inherit;
  color:rgb(153, 0, 0);
  font-size:16px;
}

#content .post
{ font-size: 16px;	
  padding:0px;
  margin:auto auto auto auto;
  text-align: center;	}
/*
#saint_pic {
  width:auto;
  height:auto;
}
*/
#content img.photo
{
   display: block;
   height:480x;
   width: 720px;
   margin-left: auto;
   margin-right: auto;}

/* Footer */	
#footer {
  background: #b50c0c;
  background: -moz-linear-gradient(top,  #b50c0c 0%, #a81010 50%, #a80000 51%, #8e0707 100%);
  background: -webkit-linear-gradient(top,  #b50c0c 0%,#a81010 50%,#a80000 51%,#8e0707 100%);
  background: linear-gradient(to bottom,  #b50c0c 0%,#a81010 50%,#a80000 51%,#8e0707 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#7fb50c', endColorstr='#568e07',GradientType=0 );
  color:rgb(255, 255, 255);
  height:40px;
  text-align:center;
  font-size:12px;
  padding:0;
  margin:35px auto;	
  border:3px solid #fff;
}

#footer a
{	background-color:inherit;
	color:rgb(255, 255, 255);	
	text-decoration:none;	}
	
#footer .notice
{	background-color:brown;
	color: rgb(255, 255, 255);
	padding:0;
  line-height:40px;
}

/* Attribution: Under Creative Commons, Attribution should not be removed or hidden */
#attribution {	
  background-color:inherit;
  color:#8e0707;
  text-align:center;
  font-size:11px;
  padding:5px 0;
  margin:0 auto;	
}

#attribution a
{	background-color:inherit;
	color:#8e0707;
	text-decoration:none;	}
	
#attribution a:hover
{	color:#999;	}

/* Responsive Styles */

#show-menu {display: none;}
.responsive { text-align:left; font-weight:bold; font-size:18px; font-style:underline; padding: 0; display:none; margin-left:20px;}

@media screen and (max-width : 700px){

body { font-size:12px; }
blockquote { font-size:16px; }
blockquote:before { font-size:80px;}
#footer { font-size: 11px; }
#attribution { font-size: 10px; }

ul#menu {display:none;}
.responsive { display:block;}
#show-menu:checked ~ ul#menu {display: block; position: absolute;  width:50%; margin:1% 0 0 -8%; overflow:visible; z-index:100;}
ul#menu li { display: block; text-align:left; margin:0 0 0 20%;}
ul#menu li a { display: block; background-color:#fff;}
ul#menu li a:hover { background-color:rgb(153, 0, 0); color:#fff;}
ul#menu li a.current, ul#menu li a.active:hover {    background-color:#eee;  color: #000;}

