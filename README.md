<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style type="text/css">
*{padding: 0; margin: 0; box-sizing: border-box;}
body{
    width: 100%;
    height: 100vh;
    background: url(./l2.jpg);
    background-size: cover;
    background-position: center ;
    background-repeat: no repeat ; 
} 
.contain{
    margin-left: 36%;
    width: 300px;
    height: 400px;
    margin-top: 10%;
    box-shadow: 4px 4px 20px 10px  #ffffff88;
    backdrop-filter: blur(3px)
    
}
.form{
   text-align: center;
   color: white;
}
.inp1{
    margin-top: 8%;
    margin-left: 4%; 
    font-size: large;
}
.remem{
    margin-top: 8%;
    margin-left: 4%; 
    font-size: 22px;
}
.link{
    margin-top: 8%;
    margin-left: 4%; 
    font-size: 22px;
}
 button{
    background-color: black;
    color: white;
    margin-top: 8%;
    margin-left: 4%; 
    font-size: 22px;
    border: none;
    border-radius: 25px;
    width: 200px;
    height: 44px;
 }
 button:hover{
   border: 3px solid white;
   background-color: black;
   color: white;
   font-size: large;
   cursor: pointer;
 }
 p{
    margin-top: 8%;
    margin-left: 4%; 
    font-size: 22px;
 }
</style>
<body>
        <div class="contain">
    <div class="form">  
        <form action="">
            <h1>login form</h1>  
    </div>
    <div class="log">
    <input  class="inp1" type="text" placeholder="username" maxlength="30" required>    
        </div>
        <div class="log">
    <input class="inp1" type="text" placeholder="password" maxlength="30" required>    
        </div>
        <div class="remem">
            <label ><input type="checkbox">remember me
    </div> 
    <div class="link"><a href="#">forgot password?</a></div>
    
     <button type="submit" class="btn" align="center">login</button>
     <div class="acc">
        <p>don't have an account? <a href="#">register</a></p>
     </div>
        </form>
    </div>
</body>
</html>
