<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login-form</title>
    <style>
        
        h2
        {
            text-align: center;
        }
        .wrapper
        {
            height: 400px;
            width: 400px;
            background-color: blueviolet;
            background: transparent;
            border: 2px solid rgba(255,255,255,.2);
            color: white;

    
            
        }
        *
        {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body
        {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 150px;
            background-color: blue;
            background-image:url("neww.jpeg");
            background-size: cover;
            backdrop-filter:blur(500px);

        }   
       .wrapper .input-box
        {
            width: 100px;
            height: 100px;
            margin: 30px 0;
    
        }
        .input-box input
        {
            width: 300px;
            height:30px;
            border-radius:25px;
            background: transparent;
            margin-left: 10px;
            
        }
        input[type="text"],input[type="password"]
        {
            margin-bottom:20px;
            color: white;
            font-size:15px;
            text-indent:1cm;
        }
        
        .btnn
        {
            width: 300px;
            height: 40px;
            margin-left: 40px;
            font-size: medium;
            margin-top: 20px;
            text-align: center;
            font-weight:bold;
            background-color:beige;
            border-radius: 20px;
            margin-bottom: 20px;
        }
        .remember
        {
            margin-left: 20px;
        }
        .remember a
        {
            margin-left: 70px;
        }
        
p{
    margin-left: 20px;
}

        


    </style>
</head>
<body>
    <div class="wrapper">
    <h2>Login-form</h2>
    <div class="input-box" >
    <label></label>
    <input type="text" placeholder="Username" >
    <br>
    <label></label>
    <input type="password" minlength="8" placeholder="Password">
    </div>
    <div class="remember"> 
    <label>
        <input type="checkbox">remember-me
    <a href="#" >forget password</a>
    </label>
    </div>
    <div class="xyz">
<input type="button" class="btnn" value="Login">
<!-- <input type="button" class="btn" value="submit"> -->
<p>Dont have an-account?<a 
    href="#">Register</a></p>

</div>    
</div>
</body>
</html>

