# 2018440101_-
소프트웨어시스템실습 과제를 올리는 사이트입니다.


<!DOCTYPE html>
<html>
<head>
    <title>웹 페이지의 구성 요소</title>
<style>
    body 
    {    
        background-color:linen;
        color:green;
        margin-left:40px;
        margin-right:40px 
    }
    h3
    {    
        text-align:center;
        color:darkred;
    }
    hr
    {    height:5px;
        border:solid grey;
        background-color:grey;
    }
    span
    {    
        color:pink;
        font-size:20px;
    }
</style>
<script>
    function show() { // <img>에 이미지 달기
        document.getElementById("fig").src = "apple.png";
    }
    function hide() { // <img>에 이미지 제거
        document.getElementById("fig").src= "";
    }
</script>   

</head>
<body>
    <h3>Elvis Presley</h3>
<hr>
    <div><img id="fig" src""></div>
    He was an American singer and actor. In November 1956,
    he made his film debut in <span onmouseover="show()" onmouseout="hide()">Love Me Tender</span>.
    He is often referred to as "<span>the King of Rock and Roll</span>"
 
</body>
</html>

