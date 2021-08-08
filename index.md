 <!DOCTYPE html>
<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
 
<body>
    <p>文字</p>
</body>
<script>
    let randomNum = (min, max) => Math.round(Math.random() * (max - min + 1)) + min
    setInterval(()=>{
        document.querySelector("p").style.color = "rgb("+randomNum(0,255)+","+randomNum(0,255)+","+randomNum(0,255)+")"
    })
</script>
 
</html>
