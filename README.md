# John-Hopkins-Coursera-Module-2-Assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            overflow: hidden;
            padding: 20px;
        }

        .section {
            box-sizing: border-box;
            border: 1px solid black;
            background-color: #ffffff;
            float: left;
            width: 100%;
            padding: 20px;
            margin: 10px 0;
        }

        .section-title {
            position: absolute;
            top: 10px;
            right: 10px;
            background-color: #ff9900;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
        }

        @media screen and (min-width: 768px) {
            .section {
                width: 49%;
                margin: 10px 1%;
            }
            .section:nth-child(2n) {
                margin-right: 0;
            }
            .section:nth-child(2n+1) {
                clear: both;
            }
        }

        @media screen and (min-width: 992px) {
            .section {
                width: 32.33%;
                margin: 10px 1%;
            }
            .section:nth-child(3n) {
                margin-right: 0;
            }
            .section:nth-child(3n+1) {
                clear: none;
            }
            .section:nth-child(3n+2) {
                clear: none;
            }
        }
    </style>
    <title>Responsive Page</title>
</head>
<body>
    <div class="container">
        <div class="section">
            <div class="section-title">Chicken</div>
            <p>Lorem ipsum dolor sit amet...</p>
        </div>
        <div class="section">
            <div class="section-title">Beef</div>
            <p>Lorem ipsum dolor sit amet...</p>
        </div>
        <div class="section">
            <div class="section-title">Sushi</div>
            <p>Lorem ipsum dolor sit amet...</p>
        </div>
    </div>
</body>
</html>
