electronicapp
=============

electronic goods app
<!DOCTYPE html> 
<html>
<head>
<meta charset="UTF-8">
<title>jQuery Mobile Web App</title>
<link href="jquery.mobile-1.0a3.min.css" rel="stylesheet" type="text/css"/>
<script src="jquery-1.5.min.js" type="text/javascript"></script>
<!--Include file for button handlers -->
<script src="js/buttonHandlers.js" type="text/javascript"></script>
<!--END OF Include file for button handlers -->

<!--START OF custom event handlers for JQuery Handlers -->
<script type="text/javascript">
<!--
//global variable for question 4, type is inferred from declaration
var page4ListCounter = 0;

//call setup pages to add event handlers to buttons (called from buttonHandlers.js)
 setupPages();
--!>
</script>
<!--END OF custom event handlers for JQuery Handlers -->

<!--always add the mobile library AFTER any JQuery custom code -->
<script src="jquery.mobile-1.0a3.min.js" type="text/javascript"></script>
<!-- This reference to phonegap.js will allow for code hints as long as the current site has been configured as a mobile application. 
	 To configure the site as a mobile application, go to Site -> Mobile Applications -> Configure Application Framework... -->
<script src="/phonegap.js" type="text/javascript"></script>

</head> 
<body onLoad="setupPages();"> 

<div data-role="page" id="Construct">
	<div data-role="header">
		<h1>Consctruct</h1>
	</div>
	
	   <div data-role="content">
		<ul data-role="listview">
			<li><a href="#start">Start</a></li>
			<li><a href="#decide">Decide</a></li>
			<li><a href="#vision">Televission</a></li>
            <li><a href="#dvd">DVD player's</a></li>
            <li><a href="#extras">Extras</a></li>
            <li><a href="#login">Log In</a></li>
            <li><a href="#register">Register</a></li>
            <li><a href="#payment">Payment</a></li>
			<li><a href="#review">Review</a></li>
		</ul>		
	</div>
	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

	<div data-role="page" id="start">
	<div data-role="header" id="page2Header">
		<h1>Start</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				<div class="ui-grid-b">
    <div id="wrapper">

    <div id="content">Put your img tag here</div>

</div>


        <img src="http://www.myukcompetitions.co.uk/wp-content/uploads/2011/08/Win-The-LG-Optimus-3D-%2B-%C2%A34000-of-LG-electronic-Goods.jpg">
				<p> <!--this link is logging out-->
					 <center> <a href="#decide">	
        			 <input type="submit" class="btn" value="Decide what you want to buy"> </center>
				</p>	
				

	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

	<div data-role="page" id="decide">
	<div data-role="header" id="page3Header">
		<h1>Decide</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
				
				<p> <!--this link is logging out-->
					 <center>  <a href="#vision"> <input type="submit" class="btn" value="Television"> </center>
				</p>	
				
				<p> <!--this link is logging out-->
					 <center> <a href="#dvd"> <input type="submit" class="btn" value="DVD Player's"> </center>
				</p>	

				<p> <!--this link is logging out-->
					 <center> <a href="#extras"> <input type="submit" class="btn" value="Extras"> </center>
				</p>	
	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

<div data-role="page" id="vision">
	<div data-role="header" id="page4Header">
		<h1>Television</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Television Screen Type</label>
    <select name="day" id="day">
      <option value="Select">Select Television Screen Type</option>	
      <option value="LCD">LCD</option>
      <option value="Plasma">Plasma</option>
    </select>
  </fieldset>
</form><br>

<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Television Screen Size</label>
    <select name="day" id="day">
      <option value="Select">Do You Want A 3D Television</option>	
      <option value="YES">YES</option>
      <option value="NO">NO</option>
   </select>
  </fieldset>
</form><br>						
				
<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Television Brand Type</label>
    <select name="day" id="day">
      <option value="Select">Select Television Brand Type</option>	
      <option value="Sony">Sony</option>
      <option value="Philips">Philips</option>
      <option value="Samsung">Sansung</option>
      <option value="Panasonic">Panasonic</option>
      <option value="Toshiba">Toshiba</option>
      <option value="LG">LG</option>
      <option value="Sharp">Sharp</option>
    </select>
  </fieldset>
</form><br>		
				
<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Television Screen Size</label>
    <select name="day" id="day">
      <option value="Select">Select Television Screen Size</option>	
      <option value="19">19</option>
      <option value="22">22</option>
      <option value="28">28</option>
      <option value="32">32</option>
      <option value="46">46</option>
      <option value="58">58</option>
      <option value="76">76</option>
    </select>
  </fieldset>
</form><br>	
</div>

				<p> <!--this link is logging out-->
					 <center> <a href="#dvd"> <input type="submit" class="btn" value="DVD Player's"> </center>
				</p>	

				<p> <!--this link is logging out-->
					 <center> <a href="#extras"> <input type="submit" class="btn" value="Extras"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#login"> <input type="submit" class="btn" value="Log In"> </center>
				</p>
				<p> <!--this link is logging out-->
					 <center>  <a href="#register"> <input type="submit" class="btn" value="Register"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#payment"> <input type="submit" class="btn" value="Payent"> </center>
				</p>	
	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

<div data-role="page" id="dvd">
	<div data-role="header" id="page5Header">
		<h1>DVD Player's</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Your Player Type</label>
    <select name="day" id="day">
      <option value="Select">Select Your Player Type</option>	
      <option value="DVD">DVD</option>
      <option value="Blu Ray">Blu Ray</option>
    </select>
  </fieldset>
</form><br>

<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Blu Ray Player feature</label>
    <select name="day" id="day">
      <option value="Select">Do You Want Your Blu Ray Player To Have A 3D Player</option>	
      <option value="YES">YES</option>
      <option value="NO">NO</option>
   </select>
  </fieldset>
</form><br>						
				
<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Television Brand Type</label>
    <select name="day" id="day">
      <option value="Select">Select Television Brand Type</option>	
      <option value="Sony">Sony</option>
      <option value="Philips">Philips</option>
      <option value="Samsung">Sansung</option>
      <option value="Panasonic">Panasonic</option>
      <option value="Toshiba">Toshiba</option>
      <option value="LG">LG</option>
      <option value="Sharp">Sharp</option>
    </select>
  </fieldset>
</form><br>	
				

				<p> <!--this link is logging out-->
					 <center>  <a href="#vision"> <input type="submit" class="btn" value="Television"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center> <a href="#extras"> <input type="submit" class="btn" value="Extras"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#login"> <input type="submit" class="btn" value="Log In"> </center>
				</p>
				<p> <!--this link is logging out-->
					 <center>  <a href="#register"> <input type="submit" class="btn" value="Register"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#payment"> <input type="submit" class="btn" value="Payent"> </center>
				</p>	
	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

<div data-role="page" id="extras">
	<div data-role="header" id="page3Header">
		<h1>Extras</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
				
<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Extras</label>
    <select name="day" id="day">
      <option value="Select">Select Extras</option>
      <option value="HDMI">HDMI Cable</option>
      <option value="Scart Cable">Scart Cable</option>
      <option value="3D">3D Glasses</option>
      <option value="Cables">Cables</option>
    </select>
  </fieldset>
</form><br>			
				

<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Extras</label>
    <select name="day" id="day">
      <option value="Select">Select Extras</option>
      <option value="SSS">5.1 Suround Sound System</option>
      <option value="SSS">7.1 Suround Sound System</option>
      <option value="TV">Black Glass TV Table</option>
      <option value="TV">Clear Glass TV Table</option>
    </select>
  </fieldset>
</form><br>					

<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Extras</label>
    <select name="day" id="day">
      <option value="Select">Select Extras</option>
      <option value="DVD">Kids Asourted DVDs</option>
      <option value="DVD">Regular Asorted DVDs</option>
      <option value="BRD">Asourted Blu Ray Disks</option>
      <option value="BRD">Asourted 3D Blu Ray Disks</option>
    </select>
  </fieldset>
</form><br>		

				<p> <!--this link is logging out-->
					 <center>  <a href="#vision"> <input type="submit" class="btn" value="Television"> </center>
				</p>	
				
				<p> <!--this link is logging out-->
					 <center> <a href="#dvd"> <input type="submit" class="btn" value="DVD Player's"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#login"> <input type="submit" class="btn" value="Log In"> </center>
				</p>
				<p> <!--this link is logging out-->
					 <center>  <a href="#register"> <input type="submit" class="btn" value="Register"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#payment"> <input type="submit" class="btn" value="Payent"> </center>
				</p>			
	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

<div data-role="page" id="login">
	<div data-role="header" id="page6Header">
		<h1>Log In</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
				
	<p>
 		<form action="information.html" autocomplete="off"> <!--information taken from http://www.w3schools.com/-->
   		<label for="username">Username</label> <!--&  http://www.raymondcamden.com/index.cfm/2012/3/16/A-look-at-HTML5-Form-Validition-->
    	<input id="username" name="lecturar@dsa" required><br>

    	<label for="password">Password</label>
    	<input id="password" name="password" type="password" required><br>
    					
    					
    	Encryption: <keygen name="security"><br>
    					
    	<p> <!--this link is logging out-->
		<p>Click the link to login</p>
		<a href="#payment">	
        <input type="submit" class="btn" value="Login">
		</p>	
		
		<p> <!--this link is logging out-->
					 <center>  <a href="#vision"> <input type="submit" class="btn" value="Television"> </center>
				</p>	
				
				<p> <!--this link is logging out-->
					 <center> <a href="#dvd"> <input type="submit" class="btn" value="DVD Player's"> </center>
				</p>	

				<p> <!--this link is logging out-->
					 <center> <a href="#extras"> <input type="submit" class="btn" value="Extras"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#register"> <input type="submit" class="btn" value="Register"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#payment"> <input type="submit" class="btn" value="Payent"> </center>
				</p>
		
	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

<div data-role="page" id="register">
	<div data-role="header" id="page7Header">
		<h1>Register</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
 	<div data-role="fieldcontainer">
        <label for="fname" data-theme="d">First Name:</label>
        <input type="text" id="fname" name="fname" data-theme="d" placeholder="Enter First Name" required>
        <br />
    </div>           
    <div data-role="fieldcontainer">
        <label for="lname" data-theme="d">Last Name:</label>
        <input type="text" id="lname" name="lname" data-theme="d" placeholder="Enter Last Name" required>
    </div>
    <div data-role="fieldcontainer">
        <label for="email" data-theme="d">Address:</label>
        <input type="email" id="email" name="email" data-theme="d" placeholder="Enter Address" required>
    </div>
	<div data-role="fieldcontainer">
        <label for="fname" data-theme="d">Home Number:</label>
        <input type="text" id="fname" name="fname" data-theme="d" placeholder="Enter Home Number" required>
        <br />
    </div>           
    <div data-role="fieldcontainer">
        <label for="lname" data-theme="d">Mobile Number:</label>
        <input type="text" id="lname" name="lname" data-theme="d" placeholder="Enter Mobile Number" required>
    </div>
    <div data-role="fieldcontainer">
        <label for="email" data-theme="d">E-mail Address:</label>
        <input type="email" id="email" name="email" data-theme="d" placeholder="Enter Email" required>
    </div>
    <div data-role="fieldcontainer">
        <label for="fname" data-theme="d">Confirm E-mail Address:</label>
        <input type="text" id="fname" name="fname" data-theme="d" placeholder="Confirm Email" required>
        <br />
    </div>           
    <div data-role="fieldcontainer">
        <label for="lname" data-theme="d">Password:</label>
        <input type="text" id="lname" name="lname" data-theme="d" placeholder="Enter Password" required>
    </div>
    <div data-role="fieldcontainer">
        <label for="email" data-theme="d">Confirm Password:</label>
        <input type="email" id="email" name="email" data-theme="d" placeholder="Confirm Passwordl" required>
    </div>
</a>		
	</div>
	
	<p> <!--this link is logging out-->
					 <center>  <a href="#vision"> <input type="submit" class="btn" value="Television"> </center>
				</p>	
				
				<p> <!--this link is logging out-->
					 <center> <a href="#dvd"> <input type="submit" class="btn" value="DVD Player's"> </center>
				</p>	

				<p> <!--this link is logging out-->
					 <center> <a href="#extras"> <input type="submit" class="btn" value="Extras"> </center>
				</p>	
				<p> <!--this link is logging out-->
					 <center>  <a href="#login"> <input type="submit" class="btn" value="Log In"> </center>
				</p>
				<p> <!--this link is logging out-->
					 <center>  <a href="#payment"> <input type="submit" class="btn" value="Payent"> </center>
				</p>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

	
	<div data-role="page" id="payment">
	<div data-role="header" id="page8Header">
		<h1>Payment</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
		<label for="username">Name on Card:</label>
<input type="text" name="username" id="username" value="" placeholder="Name on Card"/><br>

<form method="post" action="demoform.asp">
  <fieldset data-role="fieldcontain">
    <label for="day">Select Card Type:</label>
    <select name="day" id="day">
      <option value="Select">Select card type</option>
      <option value="Visa">Visa</option>
      <option value="Mastercard">Mastercard</option>
      <option value="Lazer">Lazer</option>
      <option value="Amex">Amex</option>
    </select>
  </fieldset>
</form><br>
<label for="username">Card Number:</label>
<input type="text" name="username" id="username" value="" placeholder="Card Number"/><br>
<label for="username">Expiary Date:</label>
<input type="text" name="username" id="username" value="" placeholder="Expiary Date"/><br>
<label for="username">CCV:</label>
<input type="text" name="username" id="username" value="" placeholder="CCV"/><br>

			
				
				

				<p> <!--this link is logging out-->
					 <center> <a href="#review"> <input type="submit" class="btn" value="Review"> </center>
				</p>	
	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

	

<div data-role="page" id="review">
	<div data-role="header" id="page2Header">
		<h1>Review</h1>
	</div>
	<div data-role="content">
	<a id="page2HeaderButton" data-role="button">
		 		<!--The following code asks you the user to input the your login detailsto proceed-->
 	<center><h2 style="text-shadow: 5px 5px 5px #CC6600;">The Online Electronic Store</h2></center><br>
				
				
				<h2>Your Television brand type is:</h2>
				<h2>Your Television screen size is:</h2>
				<h2>Your Television screen type is:</h2>
				<h2>Your Television type has 3D:</h2>
				<h2>Your Player type is a:</h2>
				<h2>Your Player brand type is:</h2>
				<h2>Your Player type has 3D:</h2>
				<h2>Your Extras are:</h2>
				<h2>Total Price:</h2>

				<p> <!--this link is logging out-->
					 <center> <a href="#decide"> <input type="submit" class="btn" value="Click here to restart"> </center>
				</p>	
	</a>		
	</div>

	<div data-role="footer">
		<h4>Page Footer</h4>
	</div>
</div>

</body>
</html>
