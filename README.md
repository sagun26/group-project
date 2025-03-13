# group-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Learning Portal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: lightblue; 
            color: darkslategray;
            text-align: center;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            box-sizing: fixed;
        }

.navbar{
    background-color: #5eb1c4;
    padding: 20px ;
    margin-bottom: 0.8rem;
    width:100%;
    height:20px;
    display: inline-flex;
    justify-content: space-between;
    box-shadow: 0 0 4px #bbd0e2;
    position:fixed;
    top:0;
    z-index:99;
    left:0;
    right:0;
    box-decoration-break: initial;
    }
    nav a {
        color: rgb(18, 2, 2);
        text-decoration: none;
        margin: 1px 20px;
        font-size: 18px;
        padding: 0 10px;
        border-radius: 5px;
        gap:50px;
       
    }  nav a:hover { 
            color: red;
        }
    .d-flex{
        height:1px;
        gap:20px;
        margin-top:2px;
    }
input{
    height:30px;
    width: 500px;
    padding-inline:1px;
    border-radius: 5px;
    border: 2px solid #010508;
    font-family: "Roboto",sans-serif;
   
}
.search-button{
    background-color: var(--accent-color);
    color:white;
    padding: 8px 24px;
    border:none;
    border-radius:4px;
    cursor: pointer;
    font-family: "Roboto",sans-serif;
}

.search-button:hover{
    background-color: var(--accent-color-dark);
}
 form{
        margin: 0 15px;
        padding: 0px;
        justify-items:auto ;
 }
.login{

    text-decoration: none;
    margin-right:50px;
}
      
        .hero {
            background-color:lightblue;
            color: #333;
            padding: 50px 0;
            margin-top: 100px;
        }
        .hero h1 {
            font-size: 50px;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 20px;
            margin-bottom: 20px;
        }
        .hero a {
            display: inline-block;
            text-decoration: none;
            background-color: #333;
            color: #efe8e8;
            padding: 10px 20px;
            margin-top: 20px;
            border-radius: 5px;
        }
        .hero a:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Navbar -->
        <nav class="navbar" width="100%" height="20px">
            <a href="index.html">Home</a>
            <a href="courses.html">Courses</a>
            <a href="game.html">Games</a>
            <a href="about.html">About</a>
        
           
            <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" class="search-bar" aria-label="Search">
                <button class="btn-outline-success" type="submit" class="search-button">Search</button>
              </form>
            <a href="login.html" name="login" class="login">Login</a>
        </nav>
<hr>
        <div class="hero">
            <h1>Welcome to Online Learning</h1>
            <p>Learn various courses at your own pace.</p>
            <a href="register.html" >Get Started</a>
        </div>
    </div>

</body>
</html>
