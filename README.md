<html>
<head><title>Home Page</title>
<style>


@keyframes slider {

0% {
	left: 0;
}

20% {
	left: 0;
}

25% {
	left: -100%;
}

45% {
    left: -100%;

}

50% {
		left: -200%;

}

70% {
	left: -200%;
}

75% {
	left: -300%;
}

95% {
	left: -300%;
}

100% {
	left: -400%;

}

}

#slider {
	overflow: hidden;
}

#slider figure img {
	width: 20%;
	float: left;
}

#slider figure {
	position: relative;
	width: 500%;
	margin: 0;
	left: 0;
	text-align: left;
	font-size: 0;
	animation: 20s slider infinite; 

}
	.d3 {
	color:blue;
font-family:"Khmer OS Muol Light";
  text-shadow: 0 1px 0 #ccc,
               0 2px 0 #c9c9c9,
               0 3px 0 #bbb,
               0 4px 0 #b9b9b9,
               0 5px 0 #aaa,
               0 6px 1px rgba(0,0,0,.1),
               0 0 5px rgba(0,0,0,.1),
               0 1px 3px rgba(0,0,0,.3),
               0 3px 5px rgba(0,0,0,.2),
               0 5px 10px rgba(0,0,0,.25),
               0 10px 10px rgba(0,0,0,.2),
               0 20px 20px rgba(0,0,0,.15);
}
</style> 
</head>
<body>
	<table width="100%" border="0" >
		<tr>
			<td style="background-color:#cc99ff" width="19%"><a href="D:\Project\homepage.html" target="show"><img src="..\Project\Photos\logo.png" width="70%" height="19%"></a>
		</td>
		<td width="50%">
	<div id="slider" >
	<figure>
		<img src="..\Project\Photos\logo2016.png" width="70%" height="40%" >
		<img src="..\Project\Photos\11.jpg" width="70%" height="40%" >
		<img src="..\Project\Photos\22.jpg" width="70%" height="40%" >
		<img src="..\Project\Photos\33.jpg" width="70%" height="40%" >
		<img src="..\Project\Photos\44.jpg" width="70%" height="40%" >
	</figure>	
</td>
	<td bgcolor="#cc99ff"class="d3" width="30%">
	<marquee align="right" direction="down"width="100%" height="70%" behavior="alternate">
		<marquee behavior="alternate">គម្រោងអាជីវកម្មសេវាកម្មអ៊ិធើណេត<br>
	</marquee>
</marquee>
</td>
</tr>
</table>
</body>
</html>
