# Maksim Bely 

## Contact Info:
* +375(29)509-97-52
* whitemaxim752@gmail.com 

   I want to acquire skills in the field of front-end development. Learn to put this knowledge into practice.
   At the moment, my objective is to successfully complete the Rolling-scopes-school course.

## Skills

 Basic knowledge: Windows, Android, Java, C#, JavaScript, HTML, HTML5, CSS, CSS3, Git, Github.

## Code example:
```html
<body bgcolor="#FFFFFF" text="#0000FF"
	onload="window.setTimeout('getSecs()',1)">

<script language="JavaScript">
startday = new Date();
clockStart = startday.getTime();

function initStopwatch() {
	var myTime = new Date();
	var timeNow = myTime.getTime();
	var timeDiff = timeNow - clockStart;
	this.diffSecs = timeDiff/1000;
	return(this.diffSecs); }

function getSecs() {
	var mySecs = initStopwatch();
	var mySecs1 = ""+mySecs;
	mySecs1= mySecs1.substring(0,mySecs1.indexOf(".")) + " secs.";
	document.forms[0].timespent.value = mySecs1
	window.setTimeout('getSecs()',1000); }

</script>

<form>
  <p align="center"><strong>
   Вы находитесь на этой странице уже:</strong></font>
   <input type="text" size="9" name="timespent"></p>
</form>

<br><br><br>

<p align="center"><a href="clock1.php"><font color="#000000">
<strong>Посмотрите еще один вариант.</strong></font></a></p>

<form>
  <p align="center">
  <input type="button" value="  НАЗАД  " onclick="Home()">
   <script>
	function Home()
	{location.href="/java/example.php";}
   </script></p>
</form>
```
## Education

* BNTU - MECHANICAL ENGINEERING FACULTY (Automation of technological processes and production)
* BNTU - Enterprise economics and management
* self study
    * Java (application SoloLearn, Herbert Schildt Java 8. The Complete Reference, 8th Edition)
    * HTML, CSS (application SoloLearn, [https://htmlacademy.ru/](https://htmlacademy.ru/))

# English

Pre-Intermediate
Self-study with applications (Simpler, Duolingo)