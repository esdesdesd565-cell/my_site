
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>اضغط هنا</title>

<style>
body{
    margin:0;
    overflow:hidden;
    font-family:Arial;
    background:black;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    color:white;
}

h1{
    position:absolute;
    text-align:center;
    font-size:35px;
    z-index:2;
}

a{
    color:white;
    text-decoration:none;
}

/* القلوب */

.heart{
    position:absolute;
    color:red;
    font-size:20px;
    animation:fall 5s linear infinite;
}

@keyframes fall{
    0%{
        transform:translateY(-100px);
        opacity:1;
    }
    100%{
        transform:translateY(100vh);
        opacity:0;
    }
}

</style>
</head>

<body>

<h1>
<a href="https://google.com" target="_blank">
اضغط هنا 🥺
</a>
</h1>

<script>

function createHeart(){
    const heart=document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML="❤️";
    heart.style.left=Math.random()*100+"vw";
    heart.style.fontSize=(Math.random()*20+10)+"px";
    heart.style.animationDuration=(Math.random()*3+2)+"s";

    document.body.appendChild(heart);

    setTimeout(()=>{
        heart.remove();
    },5000);
}

setInterval(createHeart,200);

</script>
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>اضغط هنا</title>

<style>
body{
    margin:0;
    overflow:hidden;
    font-family:Arial;
    background:black;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    color:white;
}

h1{
    position:absolute;
    text-align:center;
    font-size:35px;
    z-index:2;
}

a{
    color:white;
    text-decoration:none;
}

/* القلوب */

.heart{
    position:absolute;
    color:red;
    font-size:20px;
    animation:fall 5s linear infinite;
}

@keyframes fall{
    0%{
        transform:translateY(-100px);
        opacity:1;
    }
    100%{
        transform:translateY(100vh);
        opacity:0;
    }
}

</style>
</head>

<body>

<h1>
<a href="https://google.com" target="_blank">
اضغط هنا 🥺
</a>
</h1>

<script>

function createHeart(){
    const heart=document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML="❤️";
    heart.style.left=Math.random()*100+"vw";
    heart.style.fontSize=(Math.random()*20+10)+"px";
    heart.style.animationDuration=(Math.random()*3+2)+"s";

    document.body.appendChild(heart);

    setTimeout(()=>{
        heart.remove();
    },5000);
}

setInterval(createHeart,200);

</script>

</body>
</html>
</body>
</html>
