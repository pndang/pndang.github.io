<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Company Layout</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Aptos+Body&family=Mangal+Pro&display=swap');

        .container {
            display: flex;
            align-items: center;s
            margin-bottom: 10px;
        }

        .logo {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            overflow: hidden;
        }

        .logo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .text-container {
            margin-left: 20px;
        }

        .company-title {
            font-family: 'Mangal Pro', sans-serif;
            font-size: 24px;
            font-weight: bold;
        }

        .description {
            font-family: 'Aptos Body', sans-serif;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="assets/thetimes/dg&co.png" alt="Company Logo">
        </div>
        <div class="text-container">
            <div class="company-title">DANGGIACO</div>
            <div class="description"></div>
        </div>
    </div>
</body>
</html>