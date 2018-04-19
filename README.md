<html>

<style>
body {
	font-family: courier;
	font-weight: bold;
	font-size: 28px;
	color: #ffe200;
	text-align: center;
	background: black;
	position: relative;
	top: 50px;
	left: auto;
	right: auto;
}

#yes {
	text-decoration: underline #00abff;
	font-size: 25px;
	color: hotpink;
    animation: blinker 0.8s linear infinite;

}

#no {
	text-decoration: underline hotpink;
	font-size: 25px;
	color: #00abff;
    animation: blinker 0.8s linear infinite;
}

@keyframes blinker {
  100% {
    opacity: 0;
	}
  }

</style>

<body>

<p>Hey, you wanna go for a drink ?</p><br><br><br>
<div class="line"></div>
<a id="yes"href="yes.html">
    YES</a><br><br><br><br>
<a id="no"href="no.html">
    NO</a>
</body>

</html>
