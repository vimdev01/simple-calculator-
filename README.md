<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="utf-8">
        <title>Projet de calculatrice</title>
        <meta name="description" content="">
        <link rel="stylesheet" href="../css/style.css">
    </head>
    <body>
        <div id="calculator">
            <form name="calculator">
                <input class="result" type="text" name="ans" value=""/><br>
                <div id="button">   
                    <input type="button" value="1" onclick="document.calculator.ans.value+='1'"/>
                    <input type="button" value="2" onclick="document.calculator.ans.value+='2'"/>
                    <input type="button" value="3" onclick="document.calculator.ans.value+='3'"/><br>
                    <input type="button" value="4" onclick="document.calculator.ans.value+='4'"/>
                    <input type="button" value="5" onclick="document.calculator.ans.value+='5'"/>
                    <input type="button" value="6" onclick="document.calculator.ans.value+='6'"/><br>
                    <input type="button" value="7" onclick="document.calculator.ans.value+='7'"/>
                    <input type="button" value="8" onclick="document.calculator.ans.value+='8'"/>
                    <input type="button" value="9" onclick="document.calculator.ans.value+='9'"/><br>
                    <input type="button" value="0" onclick="document.calculator.ans.value+='0'"/>
                    <input type="button" value="." onclick="document.calculator.ans.value+='.'"/>
                    <input type="button" value="="onclick="document.calculator.ans.value=eval(document.calculator.ans.value)"/><br>
                    <input type="button" value="-" onclick="document.calculator.ans.value+='-'"/>
                    <input type="button" value="+" onclick="document.calculator.ans.value+='+'"/>
                    <input type="button" value="/" onclick="document.calculator.ans.value+='/'"/>
                    <input type="button" value="X" onclick="document.calculator.ans.value+='*'"/><br>
                    <input type="reset" value="CE"/>
                </div> 
            </form>   
        </div>
    </body>
</html>
---------------------CSS------------------------------------

#button input
{
    width: 75px;
    height: 70px;
    font-size: 1.5em;
    border-radius: 20px;
    border: 2px solid #827c7c;
    margin-top: 3px;
    background-color: #88d1f1;
    transition-property: background-color, color; 
    transition-duration: 500ms;
}

#button input:hover
{
   background-color: #8a2be2;
   color: #ffffff;
}

#button input:last-child
{
    width: 200px;
}
#calculator
{
    text-align: center;
    margin-top: 275px;
}
.result
{
    width: 222px;
    height: 2em;
    border: 2px solid #827c7c;
    border-radius: 15px;
    font-size: 1.5em;
    text-align: center;
    background-color: #efefef;
}


