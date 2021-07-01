<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Vote Corso</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css">

</head>
<body>

<style>
    body{
        background-color: black;
    }

    #thescript, #thescript2 , #thescript3, #thescript4{
        color:white;
        font-size: 15px;


    }

    #bruh {
        width: 40%;
        height: auto;
        padding-left: 30px;
    }

    #thecontainer{
        color:rgb(171,143,0);
        justify-content: center;
        padding: 20px 20px 20px 20px;
    }

    #subtitle, #subtitle2, #subtitle3, #subtitle4, #subtitle5{
        color:rgb(171,143,0);
        justify-content: center;
        padding: 20px 20px 20px 20px;
        font-family: serif;
        font-weight: bold;
        font-style: italic;
        font-size: 150px;
    }
</style>


<nav class="navbar navbar-expand-md navbar-light " style="background-color: rgb(171,143,0)">
    <a href="home.html" class="navbar-brand">
        <img src="votecorsogod.png" height="70" alt="Vote Corso">
    </a>
    <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarCollapse">
        <div class="navbar-nav">
            <a href="home.html" class="nav-item nav-link active">Home</a>
            <a href="aboutme.html" class="nav-item nav-link active">About Me</a>
            <a href="achieve.html" class="nav-item nav-link active">Achievements</a>
            <a href="news.html" class="nav-item nav-link active">News</a>
        </div>
        <div class="navbar-nav ml-auto">
            <a href="login.html" class="nav-item nav-link active">Login</a>
        </div>
    </div>
</nav>
<div id="subtitle" class="d-flex justify-content-center" style="color: rgb(171,143,0)" style="padding-left: 50%"  style="padding-right: 50%">
    <h1 id="tezt" onclick="cooler()">Vote Corso For Class President</h1>

</div>


<div id="subtitle2" class="d-flex justify-content-center" style="color: rgb(171,143,0)">
    <h2 id="tezt2" onclick="cooler2()">Participating</h2>
</div>

<div id="thescript" class="d-flex justify-content-center">
    <p>During the 2020-2021 school year I was a part of the most involved student council ever.</p>
</div>


<div id="subtitle3" class="d-flex justify-content-center">
    <h2> Pioneering</h2>
</div>

<div id="thescript2" class="d-flex justify-content-center">
    <p>During this school year I helped create new student council activities and fundraisers.</p>
</div>


<div id="subtitle4" class="d-flex justify-content-center">
    <h2>Collaborating</h2>
</div>

<div id="thescript3" class="d-flex justify-content-center">
    <p>This school year I worked with other members of student council to achieve a greater goal. </p>
</div>


<div id="subtitle5" class="d-flex justify-content-center">
    <h2>Philanthropy</h2>
</div>

<div id="thescript4" class="d-flex justify-content-center ">
    <p>This student council raised thousands of dollars for charitable acts.</p>
</div>


<nav class="navbar navbar-expand-md navbar-light navbar-fixed-bottom" style="background-color: rgb(171,143,0)">

    <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarCollapse2">
        <div class="navbar-nav">
            <a href="home.html" class="nav-item nav-link active">Vote Corso For Class President</a>
        </div>
        <div class="navbar-nav ml-auto">
            <a href="login.html" class="nav-item nav-link active">Sophomore Edition</a>
        </div>
    </div>
</nav>



<script>
    function cooler() {
        document.getElementById('subtitle').style.color = "black"
    }

    function num1() {
        Math.floor(Math.random() * 256);
    }

    function num2() {
        Math.floor(Math.random() * 256);
    }

    function num3() {
        Math.floor(Math.random() * 256);
    }

    function cooler2() {
        document.getElementById('subtitle2').style.color = "rgb(num1 + num2 + num3)"
    }
</script>
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
