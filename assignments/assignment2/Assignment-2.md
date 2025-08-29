<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
 /* style.css */
<style>
 body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

.container {
    width: 90%;
    margin: 20px auto;
    background-color: #fff;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h2 {
    text-align: center;
    margin-bottom: 20px;
}

.menu-item {
    margin-bottom: 20px;
}

.menu-title {
    color: #fff;
    padding: 10px;
    text-align: center;
    border-radius: 5px 5px 0 0;
}

.chicken {
    background-color: #ff6347; /* Red */
}

.beef {
    background-color: #964b00; /* Brown */
}

.sushi {
    background-color: #ffff00; /* Yellow */
    color: #000; /* Text color for sushi to make it visible on yellow background */
}

.menu-description {
    background-color: #d3d3d3; /* Gray */
    padding: 10px;
    border-radius: 0 0 5px 5px;
}
</style>
</head>
<body>
    <div class="container">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <div class="menu-title chicken">Chicken</div>
            <div class="menu-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
        </div>
        <div class="menu-item">
            <div class="menu-title beef">Beef</div>
            <div class="menu-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
        </div>
        <div class="menu-item">
            <div class="menu-title sushi">Sushi</div>
            <div class="menu-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
        </div>
    </div>
</body>
</html>
