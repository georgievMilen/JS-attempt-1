# JS-attempt-1
 My first js 
 <!DOCTYPE html>
 <html>
 	<body>

 		<h1>My First JavaScript</h1>

 		<p id="demo">JavaScript can change the style of an HTML element.</p>

 		<script>
 		function myFunction() {
 		  document.getElementById("demo").style.fontSize = "25px";
 		  document.getElementById("demo").style.color = "red";
 		  document.getElementById("demo").style.backgroundColor = "yellow";        
 		}
 		</script>
 		<button type="button" onclick="myFunction()">Click Me!</button>
 		<br>
 		<script>
 			function showImage(sw) {
 			  var pic;
 			  if (sw == 1 ) {
 				pic = "DCD.jpg"
 			  } else {
 				pic = "progressive.jpg"
 			  }
 			  document.getElementById('myImage').src = pic;
 			}
 		</script>

 		<img id="myImage" src="DCD.jpg" width="400" height="300">

 		<p>
 			<button type="button" onclick="showImage(1)">One</button>
 			<button type="button" onclick="showImage(0)">Two</button>
 		</p>

 	</body>
 </html>
