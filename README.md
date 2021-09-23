# Login-Responsivo
![login-html-css](https://user-images.githubusercontent.com/90210126/134449337-29542b56-b184-4ce1-822e-16eaa9c094bd.png)

<h4>Código HTML</h4>

```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="designer/login.css">
    <title>Login</title>
</head>

<body>

    <form id="login">

        <h1>Conecte-se</h1>

        <input type="email" class="sigiloso"  placeholder="Usuário">
        <input type="password" class="sigiloso" placeholder="Senha">
        <input type="submit" value="Entrar">

    </form>

</body>

</html>
```
<br>
<br>

<h4>Código CSS</h4> 

```
body {

    margin: 0;
    padding: 0;
    font-family: 'Courier New', Courier, monospace;
    background-color: #117ae4;

}

#login {
    
    border-radius: 15px;
    width: 300px;
    padding: 40px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #191919;
    text-align: center;

}

#login .sigiloso{

    border:0;
    background: none;
    display: block;
    margin:22px auto;
    text-align: center;
    border: 2px solid #00BFFF;
    padding:14px 10px;
    width:150px;
    outline: none;
    color:white;
    border-radius:20px;
    transition: 0.20s;


}

#login input[type="submit"] {

    border:0;
    background: none;
    display: block;
    margin:22px auto;
    text-align: center;
    border: 2px solid #2ECC71;
    padding:14px 10px;
    width:100px;
    outline: none;
    color:white;
    border-radius:20px;
    transition: 0.20s;


}

#login input[type="email"]:focus, #login input[type="password"]:focus{

width: 250px;
border-color: #8b32df;

}

#login input[type="submit"]:hover{

    cursor: pointer;
    width: 100px;
    background-color: #2ECC71;
    border-color: #2ECC71;
    
    }

#login h1 {

    color:white;
    font-size:20px;

}
```
