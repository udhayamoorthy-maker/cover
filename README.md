# Ex.05 Book Front Cover Page Design
## Date:18/12/25

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>bookcover</title>
    <style>
        body{
            font-family:Arial;
            background-color:bisque;
            text-align:center;
        }
        .cover{
            width: 600px;
            height:850px;
            margin:50px auto;
            background:url("book cover.jpeg")center/cover no-repeat;
            padding: 40px;
            display:flex;
            flex-direction:column;
            justify-content:space-between;
            position:relative;
        }
        .footer{
            display:flex;
            justify-content:space-between;
            border-top: 3px solid rgb(108, 32, 135);
        }
        .photo{
            position:absolute;
            width:150px;
            right:50px;
            bottom:100px;
        }
        
    </style>
</head>
<body>
    <div class="cover">
        <div>
            <h1 style="color:aqua;font-size:50px">Mastering python program</h1>
            <h2 style="color:blueviolet;font-size:20px">a simple guide to master your programming skill</h2>
        </div>
        <div class="footer">
            <h3 style="color:black">python</h3>
            <h3 style="color:black">sk</h3>
        </div>
        <img src="sk.jpeg" class="photo">
        <img src="pylogo.webp" class="logoimg">
    </div>
    
</body>
</html>
```

## OUTPUT:
<img width="569" height="782" alt="image" src="https://github.com/user-attachments/assets/dd496359-5ca6-477e-9944-f4648e354527" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
