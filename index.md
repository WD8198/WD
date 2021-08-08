

<html>

<head>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

<style type="text/css">

.one{color:#0000FF;}

.two{color:#00FF00;}

.three{color:#FFFF00;}

.four{color:#00FFFF;}

.five{color:#CC9933;}

.six{ color:#FF66CC;}

.seven{color:#00FF00;}

</style>

<script type="text/javascript">

  var i=0;

  var color = ["one","two","three","four","five","six","seven"];

  function changeColor(){

  var n = document.getElementById("one");

  n.className = color[i];

  if(i<color.length-1){

  	i++;

}

else{

i=0;

}

  }

  setInterval(changeColor,500);

  window.onload = changeColor;

</script>

<title>无标题文档</title>

</head>

<body>

<h1 id="one" class="">诚信立足 创新致远
