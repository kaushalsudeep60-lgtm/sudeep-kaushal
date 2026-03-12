<!DOCTYPE html>
<html>
<head>
<title>Library Management System</title>

<style>
body{
    font-family: Arial;
    background-color: #f2f2f2;
}

.login-box{
    width: 350px;
    padding: 30px;
    margin: 100px auto;
    background: white;
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 0 10px gray;
}

input{
    width: 90%;
    padding: 10px;
    margin: 10px;
}

button{
    padding: 10px 20px;
    background: green;
    color: white;
    border: none;
    cursor: pointer;
}
</style>

<script>
function login(){
    var user = document.getElementById("userid").value;
    var pass = document.getElementById("password").value;

    if(user=="adm" && pass=="adm"){
        alert("Login Successful");
    }
    else{
        alert("Invalid User ID or Password");
    }
}
</script>

</head>

<body>

<div class="login-box">
<h2>Library Management System</h2>

<input type="text" id="userid" placeholder="User ID"><br>
<input type="password" id="password" placeholder="Password"><br>

<button onclick="login()">Login</button>

</div>

</body>
</html>
