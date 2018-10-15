<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	<table>
    <p><b> Student ID#        : <a id="demo"></a> </p>
	<p> <b>Student First Name : <a id="demo1"> </p> </a>
	<p> <b> Student Last Name  : <a id="demo2"></a> </p>
	<p> <b>Student Grade      :  <a id="grade"> </a> </p>
	<a style="color: red" id="red" > </a> <a style="color: blue" id="blue"></a></p>
	<p style="color: red" id="red1"> </p>
	<P style="color: blue" id="blue2"> </p>


<script type="text/javascript">
var a=prompt("Input Student Id#: ");
var b=prompt("Input First Name: ");
var c=prompt("Input Last name");
var d=prompt("Enter Student Grade: ");	

    document.getElementById("demo").innerHTML=a;
    document.getElementById("demo1").innerHTML=b;
    document.getElementById("demo2").innerHTML=c;
     document.getElementById("grade").innerHTML=d;


   	



if(d%2==0 && d<=3 )
{


 document.getElementById("blue").innerHTML="PASSED"

}
else if(d%2==0 && d>3)
{

	document.getElementById("blue").innerHTML="FAILED" 
}

else if(d%2==1&& d<=3)
{
	 	document.getElementById("red").innerHTML="PASSED "
}
else if(d%2==1 && d>3)
{
	 
	document.getElementById("red").innerHTML="FAILED" 
}



		</script>

</body>
</html>
