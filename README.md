<!DOCTYPE html>
<html>
    <head>
        <title> Welcome to VED! </title>     
        <link href="css" rel="stylesheet" type="text/css">
        <link href="https://fonts.googleapis.com/css?family=Playfair+Display" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet">
                <style>
        
                * {
                    font-family: 'Raleway', sans-serif;
                    color: #333333;
                }
                
                body {
                    height: 100%;
                }
                
                header {
                    line-height: 5rem;
                    padding: 5px;
                }
                
                a {
                    text-decoration: none;
                    color: #500B4E;
                }
                
                a:hover {
                    color: #2B5E79;
                }
                
                .green {
                    color: #669966;
                }
                
                #hgreen, #green {
                    color: #669966;
                    font-weight: bold;
                }
                
                
                a:hover#green, a:hover#hgreen  {
                    color: #FFCC00;
                }
                
                .yellow {
                    color: #FFCC00;
                }
                
                #hyellow, #yellow {
                    color: #FFCC00;
                    font-weight: bold;
                }
                
                .brown {
                    color: #333333;
                }
                
                #home {
                    font-weight: bold;
                }
                
                .nav {
                    width: 100%;
                    text-align: center;
                    background-color: #333333;
                    line-height: 3.5rem; 
                    position: sticky;/*This value for position fails validation even though it works fine and is on the w3schools website.*/
                    top: 0;
                }
                
                .nav ul {
                    list-style-type: none;
                    margin: 0;
                    padding: 0;
                    overflow: hidden;
                }
                .nav li {
                    display: inline;
                }
                
                .nav a {
                    text-decoration: none;
                    text-align: center;
                    padding: 14px 16px;
                    color: white;
                }
                  
                .nav a:hover {
                    color: #B7BEC6;
					font-weight: bold;
                 }
                 
                 #hnav {
                     background-color: #FFCC00;
                 }
                
                #gnav {
                    background-color: #669966;
                }
                
                h1.heading {
                    display: inline;
                }
                
                .mheading {
                    font-family: 'Playfair Display', serif;
                    font-size: 2.5rem;
                    margin-top: 10px;
                }
                
                .heading, .mpheading {
                    font-family: 'Playfair Display', serif;
                    font-size: 2rem;
                }
                
                .content, .mpcontent {
                    font-size: 1.15rem;
                }
                
                .mpcontent {
                    padding: 5px;
                    margin-bottom: 15px;
                }
                
                li {
                    margin-bottom: 0.5rem;
                    width: 75%;
                }
                
                .list ul {
                    border-left: 1px solid #333333;
                }
                
                table {
                    width: 100%;
                }
                
                .home {
                    width: 50%;
                    vertical-align: top;
                    padding: 5px;
                }
                
                td {
                    width: 33%;
                    margin: 10px;
                    padding: 5px;
                    vertical-align: top;
                }
                
                
                .search {
                    float: right;
                }
                
                input {
                    border: 1px solid #333333;
                    padding: 10px;
                }
                
                button {
                    background-color: #333333;
                    color: white;
                    padding: 9px;
                    border: 2px solid #333333; /*The validator shows a warning for the border color and background color being the same. But it is the way I want it to be styled so that the button looks good.*/
                }
                
                .backgroundimage {
                    background-image: url("./images/pic2.jpg");
                    background-repeat: no-repeat;
                    background-size: cover;
                    width: 100%;
                    height: 430px;
                    text-align: right;
                    margin-bottom: 10px;
                }
                
                #heading {
                    font-size: 3rem;
                    position: relative;
                    top: 250px;
                    color: white;
                    background-color: rgb(50,50,55);opacity:0.6;
                }
                
                #content {
                    font-size: 1.5rem;
                    position: relative;
                    top: 250px;
                    color: white;
                    background-color: rgb(50,50,55);opacity:0.6;
                }
                
                footer {
                    background-color: #333333;
                    color: white;
                    font-size: 0.75rem;
                    text-align: center;
                    line-height: 1.5rem;
                    position: relative;
                    bottom: 0;
                    width: 100%;
                }
                
                .whitespace {
                    height: 30px;
                }
                
                .footer a {
                    color: white;
                }
                
                .footer a:hover {
                    color: #B7BEC6;
					font-weight: bold;
                }
				
				.purple {
					color: #500B4E;
				}
				
				.dblue {
					color: #2B5E79;
				}
				
				.lblue {
					color: #0A7587;
				}
				
				#logo {
					display: inline-block;
					float: left;
					height: 5rem;
					width: 5rem;
					vertical-align: middle;
					margin-right: 1rem;
				}
        </style>
    </head>
    <body>
        <header>
		
			<img src="./images/logo.png" alt="logo" id="logo"/>
            <a href="./index.html"><h1 class="heading"> <span class="purple">venus</span><span class="dblue">events</span><span class="purple">and</span><span class="dblue">design</span><span class="brown">.com</span> </h1></a>
            
        <div class="search">
            <input type="search" placeholder="Search..."/> 
            <button type="submit"> Search </button>
        </div>
        
        </header>

        <div class="nav">
        <ul>
            <li> <a href="./index.html" id="home"> Home </a> </li>
            <li> <a href="./services.html"> Services </a> </li>
            <li> <a href="./gallery.html"> Gallery </a> </li>
            <li> <a href="./getaquote.html"> Get A Quote </a> </li>
            <li> <a href="./aboutus.html"> About Us </a> </li>
            <li> <a href="./contactus.html"> Contact Us </a> </li>
        </ul>
        </div>

        <div class="backgroundimage">
            <div class="middle"> 
                <div id="heading" class="heading">Welcome to Venus Events and Design!</div>
                <div id="content">Looking for a party planner? You've come to the right place!</div>
            </div>
            
        </div>
        
        <table>
            
            <tr>
            <td colspan="2">
                <div class="mpheading"> Lorem Ipsum. </div>
            </td>
            </tr>
            
            <tr>
            <td class="home">
                <div class="mpcontent">
                    <p>Welcome to Venus Events and Design! Party planning can be a struggle, but we are here to help. Venus Events and Design is a party and event planning business ready to step in when you need an amazing event that pleases all your guests and assures that everyone has a good time!</p>
                    
                    <div class="heading"> Why VED? </div>
                    <p>Venus Events and Design offers great deals and reasonable prices. We also provide easy-to-contact staff that will make sure all you party planning needs get answered.</p>
        
                </div>
            </td>
            
            <td class="home">
                <div class="list">
                         <p>Here are some of the services we provide:</p>
                        <ul>
                            <li>Lorem Ipsum</li>
                            <li>Lorem Ipsum</li>
                            <li>Lorem Ipsum</li>
                            <li>Lorem Ipsum</li>
                            <li>Lorem Ipsum</li>
                            <li>Lorem Ipsum</li>
                            <li>Lorem Ipsum</li>
                            <li>Lorem Ipsum <a href="./services.html">More...</a></li>
                        </ul>
                </div>
            </td>
            </tr>
        </table>
        
        <div class="whitespace"></div>
        
        <footer class="footer"> 
            <a href="./index.html">Home</a> | <a href="./services.html">Services</a> | <a href="./gallery.html">Gallery</a> | <a href="./getaquote.html">Get A Quote</a> | <a href="./aboutus.html">About Us</a>  | <a href="./contactus.html">Contact Us</a>
            <br/>
            
            &copy;2018 venuseventsanddesign.com by j.a.c.k. All rights reserved.
        </footer>
        
    </body>
</html>
