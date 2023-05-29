<html>

<head> <meta name="viewport" content="width=device-width, initial-scale=1">

<style>

Body { font-family: Calibri, Helvetica, sans-serif; background-color: pink;

} button {

width: 100%;

background-color: #4CAF50; color: orange; margin: 10px 0px; }

padding: 15px;

border: none; cursor: pointer;

form {

border: 3px solid #f1f1f1;

} input[type=text], input[type=password] { margin: 8px 0; display: inline-block;

width: 100%;

padding: 12px 20px;

border: 2px solid green; box-sizing: border-box;

} button:hover {

opacity: 0.7;
}

.cancelbtn {

width: auto;

padding: 10px 18px;

margin: 10px 5px;

}

46
.container {

padding: 25px;

background-color: lightblue;

</style>

</head>

<body> <center> <h1> Student Login Form </h1> </center>

<form>

<div class="container">

<label>Username : <input type="text" placeholder="Enter Username"

</label>

name="username

<input type="password" placeholder="Enter Password"

" required> <label>Password: </label>

name="password

" required>

<button type="submit">Login</button>

<input type="checkbox" checked="checked"> Remember me <button type="button" class="cancelbtn"> Cancel</button> Forgot <a href="#"> password? </a>

</div>

</form>

</body>

</html>
