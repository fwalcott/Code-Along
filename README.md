<!DOCTYPE html>
<html>
  <head>
    <title>Constructive &amp; Co.</title>
    <link rel="stylesheet" href="c0l.css /type="text/css" />
  </head>
  <body> 
    <h1> Constructive &amp Co.</h1>
    <script src="js/add-content.js"></script>  
    <script>document.write('<h3>Welcome</h3>'); 
    </script>
<p> For all orders and inquiries please call <em>555-3344 </em> </p> 
  </body>
</html>


var today = new Date (); 
var hourNow = today.getHours(); 
var greeting; 

if (hourNow > 18) {
  greeting = 'Good Evening!'; 
} else if (hourNow > 12) {
greeting = 'Good Afternoon!';
} else id (hourNow > 0) {
  greeting = 'Good Morning!';
} else {
  greeting = 'Welcome!';
} 
document.write ('<h3>' + greeting + '<h3>'); 
  
  
  
