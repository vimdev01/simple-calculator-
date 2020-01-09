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
                    <input type="button" value="=" onclick="document.calculator.ans.value=eval(document.calculator.ans.value)"/><br>
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
