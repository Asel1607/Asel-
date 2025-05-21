
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Форма для записи и чтения из базы данных DynamoDB</title>
    <style>
        html {
            background-color: #FFEBCD;
            background-blend-mode: overlay;
        }
        h1 {
            color: #1C1C1C;
            font-family: system-ui;
            margin-left: 20px;
        }
        button {
            background-color: #32221A;
            border-color: #32221A;
            color: #FFFFFF;
            font-family: system-ui;
            font-size: 20px;
            font-weight: bold;
            margin-left: 10px;
            margin-top: 20px;
            width: 100px;
        }
        textarea {
            color: #222629;
            font-family: "Times New Roman", Times, serif;
            font-size: 14px;
            margin-left: 10px;
            margin-top: 20px;
            height:300px;
            width: 450px;
            text-align: left; 
        }
    </style>
</head>
<body>
    <form>
        <label>Для ввода в базу</label>
        <br>
        <textarea type="text" id="data" rows="4" cols="50"></textarea><br>
        <button type="button"></button>>Внести</button>
    </form>
    <textarea id="db_data" rows="4" cols="50" disabled></textarea>
</body>
</html>
