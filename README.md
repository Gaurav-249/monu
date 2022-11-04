<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #text1{
            background-color: #989898;
            height: 50px;
            width: 100%;
            left: 0px;
            bottom: 0px;
        }
        #text2{
            background-color: magenta;
            height: 50px;
            width: 100%;
            left: 0px;
            bottom: 0px;
            position: fixed;
        }
        div{
            background-color: #333;
            height: 250px;
            width: 300px;
        }
        body{
            margin: 0px;
        }
        p{
            color: #666;
            text-decoration-line: line-through;
            text-transform: uppercase;
            letter-spacing: 5px;
            word-spacing: 20px;
           border: 5px solid pink;
        }
        h1{
            color: aquamarine;
            background: #eee;
        }
        button{
            background-color: goldenrod;
         /* font-size: 50px; */
        }
    </style>
</head>
<body>
    <center>
        <div id="text1">HEADER</div>
        <hr color="red" size="10">
        <p>We use both first and third-party cookies to personalise web content, analyse visits to our websites and tailor advertisements. Some of these cookies are necessary for the website to function, whilst others require your consent. More detail can be found in our cookie policy and you can tailor your choices in the preference centre.</p>
        <h1>LOGIN PAGE.</h1>
        <div>
            NAME:<br>
        <input type="text" name="nm" placeholder="NAME:"><br><hr><br>
        PASSWORD:<br><br>
        <input type="password" name="ps" placeholder="PASSWORD:"><br><hr><br>
        <button>CLICK ME</button>
        </div>

        <div id="text2">FOOTER</div>
    </center>
</body>
</html>
