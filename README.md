# FlexBox-Direction
Fundamentos Aprendendo Flex Box Direction


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundamentos - Flex Direction</title>
<style>
    .flex-container{
        margin: 0;
        padding: 0;
        display: flex;
        list-style: none;
    }

    .flex-item{
        background: blueviolet;
        height: 50px;
        width: 50px;
        line-height: 50px;
        font-size: 20px;
        color:white;
        text-align: center;
        margin: 5px;

    }
    
    .row{flex-direction: row;
    }

    .row-reverse{
        flex-direction: row-reverse;
    }
    .row-reverse li{
        background: red;
    }
    .column{
        float: left;
        flex-direction: column;
    }

    .column li{
        background: orange;
    }

    .column-reverse{
        float: right;
        flex-direction: column-reverse;
    }

    .column-reverse{
        background: purple;
    }

</style>    
</head>
<body>
    <ul class="flex-container row">
        <li class="flex-item">1</li>
        <li class="flex-item">2</li>
        <li class="flex-item">3</li>
        <li class="flex-item">4</li>
        <li class="flex-item">5</li>
    </ul>

    <ul class="flex-container row-reverse">
        <li class="flex-item">1</li>
        <li class="flex-item">2</li>
        <li class="flex-item">3</li>
        <li class="flex-item">4</li>
        <li class="flex-item">5</li>
    </ul> 

    <ul class="flex-container column">
        <li class="flex-item">1</li>
        <li class="flex-item">2</li>
        <li class="flex-item">3</li>
        <li class="flex-item">4</li>
        <li class="flex-item">5</li>
    </ul> 

    <ul class="flex-container column-reverse">
        <li class="flex-item">1</li>
        <li class="flex-item">2</li>
        <li class="flex-item">3</li>
        <li class="flex-item">4</li>
        <li class="flex-item">5</li>
    </ul> 

</body>
</html>
