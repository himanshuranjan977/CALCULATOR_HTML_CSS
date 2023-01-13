# CALCULATOR_HTML_CSS

#HTML PARTS

<html>
    <head>
<title>  Calculator</title>
<link rel="stylesheet" href="calculator.css">

    </head>

   <body>
</html>
   <body>

    <h1>
      online calculator
    </h1>
    <h2>
        By:- Himanshu Ranjan
    </h2>

      </div>
   </body> 

    <form name="form1" class="calci" action="calculator.html" method="POST">
<input type="text" name="answer" id="display">
<br></br>


<input type="button" value="c" onclick="form1.answer.value=''" class="button">


<input type="button"  class= "button"value="x" onclick="form1.answer.value=form1.answer.value.substring(0,form1.answer.value.length*1-1)" >

<input type="button"  class= "button"value="00" onclick="form1.answer.value+='00'">

<input type="button"  class= "operator"value="/" onclick="form1.answer.value+='/'">
<br></br>
<input type="button" class= "button" value="7" onclick="form1.answer.value+='7'">
<input type="button"  class= "button"value="8" onclick="form1.answer.value+='8'">
<input type="button"  class= "button"value="9" onclick="form1.answer.value+='9'">

<input type="button"  class= "operator"value="*" onclick="form1.answer.value+='*'">
<br></br>


<input type="button" class= "button" value="4" onclick="form1.answer.value+='4'">
<input type="button"  class= "button"value="5" onclick="form1.answer.value+='5'">

<input type="button"  class= "button"value="6" onclick="form1.answer.value+='6'">

<input type="button"  class= "operator"value="-" onclick="form1.answer.value+='-'">
<br></br>
<input type="button"  class= "button"value="1" onclick="form1.answer.value+='1'">
<input type="button"  class= "button"value="2" onclick="form1.answer.value+='2'">

<input type="button"  class= "button"value="3" onclick="form1.answer.value+='3'">

<input type="button"  class= "operator"value="+" onclick="form1.answer.value+='+'">
<br></br>

<input type="button" class= "button" value="0" onclick="form1.answer.value+='0'" id="zero">

<input type="button" class= "button" value="." onclick="form1.answer.value+='.'">
<input type="button"  class= "operator" value="=" onclick="form1.answer.value=eval(form1.answer.value)">
 </form>

</html>


# CSS PARTS

body{
    margin: 0;
    padding:0;
    line-height: 0.5;
    background:linear-gradient(to left,#08f0aa,#adf506);
    font-family: sans-serif;
}

.calci{
    width: 500px;
    padding-top: 100px;
    padding-bottom: 100;
    position: absolute;
    top:50%;
    left:70%;
    transition:0.25px;
    transform: translate(-50%,-50%);
    text-align: center;
}
#zero{

height: 55;
width: 116;
font-size: 20;
    font-family: sans-serif;
    font-weight: 300;

}

#display{
    
    border:none;
    background: white;
    border-radius: 30px;
    width: 245;
    font-size: 20;
    font-family: sans-serif;
    font-weight: 300;
    height: 60;
    margin: auto;
    border:2px solid white(5, 218, 255, 0.726);
    color: black;



}
.button{
    width: 55;
    height: 55;
    padding-top: -1;
    font-size: 20;
    border: none;
    background: white;
    font-family: sans-serif;
    font-weight: 300;
    border:0;
    border-radius: 30px;
    margin: 1.5;
    transition:0.25px;
    
    
}

h1{
    margin-top: 300px;
    margin-left: 100px;
    font-family: sans-serif;

    font-size:50;
   
    text-decoration: underline;

color: white;
text-transform: uppercase;
font-weight: 700;}

h2{

    color: white;
    margin-top: -1px;
    font-family: sans-serif;
    margin-left: 438px;
}
.operator{
    width: 55;
    height: 55;
    padding-top: -1;
    font-size: 20;
    text-align: center;
    color: black;
    border: none;
    background: white;
    font-family: sans-serif;
    font-weight: 500;
    border:0;
    border-radius: 30px;
    margin: 1.5;
    transition:0.25px;
    cursor:pointer;
    
    
    
}


.operator:hover{
    background: #00d9ff;
}
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    
