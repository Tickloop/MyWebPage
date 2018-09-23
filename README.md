<!DOCTYPE html>
<html>
<head>
<title>MyWebPage</title>
<style>
.Heading{
	border : 0px;
	width = 350px;
	font-family:Segoe UI;
	font-size:80px;
}
.text{
	//border-left:5px solid red;
	padding:10px;
	margin:10px;
	font-family:Segoe UI;
	color:green;
}
.list{
	font-family:Segoe UI;
	list-style-type:circle;
	color:red;
}
.sublist{
	font-family:Segoe UI;
	color:skyblue;
}
table,th{
	border:2px solid DeepSkyBlue;
	margin :10px;
	padding : 4px;
	font-family:Segoe UI;
	color:green;
}
td{
	border:1px solid DeepSkyBlue;
	margin :10px;
	padding:10px;
	font-family:Segoe UI;
	color:Gold;
}
a{
 	color:rgb(255, 140, 0);
	text-decoration:none;
}
a:hover{
	color:rgba(255, 140,0,0.5);
	
}	
div#myText{
	position: absolute; 
	width: 500px;
	height : 550px;
	padding: 10px;
	margin: 10px;
	top: 0 px; 
	left: 0 px; 
	
}
div#myTable{
	position: absolute; 
	width : 400px;
	height : 550px;
	margin-left : 450px;
	margin-top:10px ;
	padding : 10px;
	 
}
div#myImageGallery{
	position:absolute;
	margin-left:950px;
	padding:10px;
}
div#myImage1{
	position:absolute;
	//border:2px dashed tomato;
	padding:5px;
}
div#myImage2{
	position:absolute;
	//border:2px dashed tomato;
	margin-left:170px;
	padding:5px;
}
div#myImage3{
	position:absolute;
	//border:2px dashed tomato;
	margin-top:170px;
	padding:5px;
}
div#myImage4{
	position:absolute;
	//border:2px dashed tomato;
	margin-top:170px;
	margin-left:170px;
	padding:5px;
}
div#myImage6{
	position:absolute;
	//border:2px dashed tomato;
	margin-top:340px;
	margin-left:170px;
	padding:5px;
}
div#myImage5{
	position:absolute;
	//border:2px dashed tomato;
	margin-top:340px;
	padding:5px;
}
img:hover{
	border:5px solid green;
}
	
</style>
</head>

<body>
<p style="float:left"><img src="logo.jpg" style="width:60px;height:60px"></P>
<p style="float:right"><img src="logo.jpg" style="width:60px;height:60px"></P>
<h1 class ="Heading" align=center><span style="color:grey">PULKIT </span><span style="color:red">ARYA</span></h1>

<div id = "myText">
<p class = "text">
I am the author of this page. I am a CSE major at Ohio State University. My skills are:
</p>

<br>
<ol class = "list">
<li>CODING LANGUAGES KNOWN (order of fimiliarity)-</li>
	<ol class = "sublist">
	<li>C++</li>
	<li>HTML,SQL</li>
	<li>Java,PHP</li>
	<li>CSS</li>
	</ol>
<li>SQL database management</li>
<li>Manage & set up Microsoft server</li>
<li>Team player</li>
<li>Obscessive learner</li>
<li>Disciplined</li>
<li>Determined</li>
</ol>
</div>
<div id = "myTable">
<p class = "text">I also have the knowldge of the following courses:<br>
I did these courses at <a href="https://iantindia.com/" title="link to website" target = "_blank" >IANT </a></p>
<table>
<tr>
	<th>Course name</th>
	<th>Experience</th>
</tr>
<tr>
	<td><a href="https://certification.comptia.org/certifications/network" title = "link to website" target="_blank">CompTIA N+</a></td>
	<td>Excellenct</td>
</tr>
<tr>
	<td><a href="https://certification.comptia.org/certifications/a" title = "link to website" target="_blank">CompTIA A+</a></td>
	<td>Excellenct</td>
</tr>
<tr>
	<td><a href="https://certification.comptia.org/certifications/cloud" title = "link to website" target="_blank">CompTIA Cloud+</a></td>
	<td>Good</td>
</tr>

<tr>
	<td><a href="https://www.starcertification.org/Certifications/Certificate/Ethical-Hacking-Expert" title ="link to website" target="_blank">STAR EHE</a></td>
	<td>Good</td>
</tr>
<tr>
	<td><a href="https://www.microsoft.com/en-us/learning/mcsa-windows-server-certification.aspx" title="link to website" target="_blank">MCSA Server-1 & 2</a></td>
	<td>Good</td>
</tr>
<tr>
	<td><a href="https://www.redhat.com/en/services/certification/rhcsa" title="link to website" target="_blank">RHCSA</td>
	<td>Good</td>
</tr>
<tr>
	<td><a href="https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/ccna-routing-switching.html" title="link to website" target="_blank">CCNA</td>
	<td>Good</td>
</tr>
</table>
</div>
<div id="myImageGallery">
<div id="myImage1">
<a href="https://en.wikipedia.org/wiki/C%2B%2B" target ="_blank"><img src = "Slideshow_1.png" alt="C++ logo" style="width:150px;height=150px" ></a>
</div>
<div id="myImage2">
<a href="https://en.wikipedia.org/wiki/HTML5" target="_blank"><img src = "Slideshow_2.png" alt="HTML5 logo" style="width:150px;height=150px"></a>
</div>
<div id="myImage3">
<a href="https://en.wikipedia.org/wiki/Java_(programming_language)" target="_blank"><img src = "Slideshow_3.png" alt="JAVA logo" style="width:150px;height=150px"></a>
</div>
<div id="myImage4">
<a href="https://en.wikipedia.org/wiki/Cascading_Style_Sheets" target="_blank"><img src = "Slideshow_4.png" alt="CSS3 logo" style="width:150px;height=150px"></a>
</div>
<div id="myImage5">
<a href="https://en.wikipedia.org/wiki/PHP" target="_blank"><img src = "Slideshow_5.jpg" alt="PHP logo" style="width:150px;height=150px"></a>
</div>
<div id="myImage6">
<a href="https://en.m.wikipedia.org/wiki/SQL" target="_blank"><img src = "Slideshow_6.png" alt="SQL logo" style="width:150px;height=150px"></a>
</div>
</div>
</body>
</html>
