<!DOCTYPE html>
<head>
<style>

* {
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background:#E5E4E2;
  border:5px solid #DA0A0A;
  padding:10px;
}

h1 {
 color:#4CC417;
 text-align:center;
}

h2 {
 margin:10px;
 padding:10px;
 background-color: skyblue;
 display: inline-block;
 border: 2px solid skyblue;
 border-radius: 30px 15px;
 color: white;
 text-shadow: 2px 2px 4px #000000;
}

h3 {
  background-color:blue;
  margin:10px;
  padding:10px;
  display: inline-block;
  border: 2px solid blue; 
  border-radius: 30px 15px;
  text-shadow: 2px 2px 5px red;
}

.column {
  float: left;
  width: 25%;
  height: 300px;
} 

.row:after {
  content: "";
  margin:10px;
  padding:10px;
  display: table;
  clear: both;
}

@media only screen and (min-width: 500px) {
  body {
    background-color: #E5E4E2;
  }
}

@media only screen and (max-width: 1000px) {
  body {
    background-color: #D8CECF;
  }
}

</style>
</head>

<body>
<h1>RESUME</h1>

<dl>
<dt><b><u>Name:</u></b></dt>
<dd>*******</dd>
<dt><b><u>E-mail:</u></b></dt>
<dd>*******</dd>
<dt><b><u>Phone Number:</u></b></dt>
<dd>v</dd>
<dt><b><u>Location:</u></b></dt>
<dd>*******</dd>
<dt><b><u>Pincode:</u></b></dt>
<dd>*******</dd>
<dt><b><u>District:</u></b></dt>
<dd>*******</dd>
<dt><b><u>State:</u></b></dt>
<dd>*******</dd>
</dl>

<hr>

<h2>Education:</h2>
<ul>
<li>*******</li>
<li>*******</li>
<li>Krishna Univerty</li>
</ul>
<ul>
<li>*******</li>
<li>*******</li>
<li>*******</li>
</ul>
 
<hr>

<h2>Skills:</h2>
<div calss= "row">
<div class="column">
<h3>Known Languges:</h3>
<ul>
<li>HTML5</li>
<li>CSS3</li>
<li>JS</li>
</ul>
</div>

<div class="column">
<h3>Known Tools:</h3>
<ul>
<li>Notepad</li>
<li>Codepen</li>
<li>Visual Studio Coding</li>
<li>GitHub</li>
</ul>
</div>

<div class="column">
<h3>Known Frame Works:</h3>
<ul>
<li>SASS</li>
<li>Bootstrap</li>
</ul>
</div>

<div class="column">
<h3>Other Things:</h3>
<ul>
<li>Good Communication Skills</li>
<li>Problem solving Skills</li>
<li>Analytical Skills</li>
</ul>
 </div>
</div>

<hr>

<h2>Interests:</h2>
<p>Watching Movies,Tv Shows</p>
<p>Learning Things</p>



</body>
</html>
