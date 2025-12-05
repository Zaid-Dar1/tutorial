<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .mainbox{
            border: 2px solid black;
            border-radius: 60px;
            padding: 30px;
            margin: 30px;
            margin-left: 200px;
            margin-right: 200px
        }
        .outerbox{
            border: 2px dashed black; 
            border-radius: 60px;
            padding: 30px
        }
        .topbox{
            border: 2px solid black;
            border-radius:20px;
            margin-bottom: 30px;
            text-align: center;
        }
        .tablebox{
            border: 3px dashed black;
            padding:30px;
            
           
        }
        th{
            border: 2px solid black;
            height: 150px;
            width: 180px;
        }
        td{
            border: 3px solid black;
            border-top: none;
            border-bottom: none;
            height: 120px;
            width: 180px;
            text-align: center;
        }
        table{
            margin-left:  auto;
            margin-right: auto
        }
    </style>
</head>
<body>
    <div class="mainbox">
        <div class="outerbox">
            <div class="topbox">
                <h1>Marks Table</h1>
            </div>
            <div class="tablebox">
                <table>
                    <tr>
                        <th> student </th>
                        <th> Maths </th>
                        <th> Physics </th>
                        <th> Computer <br> Science </th>
                    </tr>
                    <tr>
                        <td> std1 </td>
                        <td> 54 </td>
                        <td> 32 </td>
                        <td> 23 </td>
                    </tr>
                    <tr>
                        <td> std2 </td>
                        <td> 54 </td>
                        <td> 32 </td>
                        <td> 23 </td>
                    </tr>
                    <tr>
                        <td> std3 </td>
                        <td> 54 </td>
                        <td> 32 </td>
                        <td> 23 </td>
                    </tr>
                </table>
            </div>
        </div>
    </div>
</body>
</html>
