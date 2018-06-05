# pagina-cualquiera
pagina cualquiera
<!DOCTYPE html>
<html>
<head>
<style>
div.container {
 width: 100%;
 border: 1px solid gray;
}
header, footer {
 padding: 1em;
 color: white;
 background-color: black;
 clear: left;
 text-align: center;
}
nav {
 float: left;
 max-width: 160px;
 margin: 0;
 padding: 1em;
}
nav ul {
 list-style-type: none;
 padding: 0;
}

nav ul a {
 text-decoration: none;
}
article {
 margin-left: 170px;
 border-left: 1px solid gray;
 padding: 1em;
 overflow: hidden;
}
</style>
</head>
<body>
<div class="container">
<header>
 <h1>City Gallery</h1>
</header>

<nav>
 <ul>
 <li><a href="#">London</a></li>
 <li><a href="#">Paris</a></li>
 <li><a href="#">Tokyo</a></li>
 </ul>
</nav>
<article>
 <h1>London</h1>
 <p>London is the capital city of England. It is the most populous city in the United Kingdom, with
a metropolitan area of over 13 million inhabitants.</p>
 <p>Standing on the River Thames, London has been a major settlement for two millennia, its
history going back to its founding by the Romans, who named it Londinium.</p>
</article>
<footer>Copyright &copy; W3Schools.com</footer>
</div>

<form>
User name:<br>
 <input type="text" name="username"><br>
User password:<br>
 <input type="password" name="psw">
</form>

<form action="/action_page.php">
First name:<br>
 <input type="text" name="firstname" value="Mickey"><br>
Last name:<br>
 <input type="text" name="lastname" value="Mouse"><br><br>
 <input type="submit" value="Submit">
</form>

<form action="/action_page.php">
First name:<br>
 <input type="text" name="firstname" value="Mickey"><br>
Last name:<br>
 <input type="text" name="lastname" value="Mouse"><br><br>
 <input type="submit" value="Submit">
 <input type="reset">
</form>

<form>
 <input type="radio" name="gender" value="male" checked> Male<br>
 <input type="radio" name="gender" value="female"> Female<br>
 <input type="radio" name="gender" value="other"> Other
</form>


<input type="button" onclick="alert('Hello World!')" value="Click Me!">


<form>
Select your favorite color:
 <input type="color" name="favcolor">
</form>

<form>
Birthday:
 <input type="date" name="bday">
</form>

<form>
Enter a date before 1980-01-01:
 <input type="date" name="bday" max="1979-12-31"><br>
Enter a date after 2000-01-01:
 <input type="date" name="bday" min="2000-01-02"><br>
</form>

<form>
Birthday (date and time):
 <input type="datetime-local" name="bdaytime">
</form>


<form>
E-mail:
 <input type="email" name="email">
</form>

<form>
Birthday (month and year):
 <input type="month" name="bdaymonth">
</form>

<form>
Quantity (between 1 and 5):
 <input type="number" name="quantity" min="1" max="5">
</form>




form>
Quantity:
 <input type="number" name="points" min="0" max="100" step="10" value="3
0">
</form>


<form>
 <input type="range" name="points" min="0" max="10">
</form>


<form>
Search Google:
<input type="search" name="googlesearch">
</form>



<form>
Telephone:
 <input type="tel" name="usrtel">
</form>

<form>
Select a time:
 <input type="time" name="usr_time">
</form>

<form>
Add your homepage:
 <input type="url" name="homepage">
</form>


<form>
Select a week:
 <input type="week" name="week_year">
</form>


</body>
</html>
