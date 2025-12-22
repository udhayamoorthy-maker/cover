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
  <meta charset="UTF-8" />
  <title>PYTHON PROGRAMMING</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: hsl(168, 33%, 94%);
    }

    /* Cover container with background image */
    .cover {
      width: 600px;
      height: 850px;
      background: url('WhatsApp Image 2025-10-08 at 20.33.55_8c5529a8.jpg') center/cover no-repeat; /* Replace with your background image URL */
      margin: 50px auto;
      color: #ffffffe9;
      padding: 50px;
      box-shadow: 0 0 20px rgba(0,0,0,0.7);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      position: relative;
      background-blur: 5px; /* Optional: adds a slight blur effect to background */
    }

    .title-section {
      z-index: 1; /* Ensures text stays on top of the background */
    }

    .title-section h1 {
      font-size: 36px;
      color: #fff;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.7); /* Adds shadow to text */
    text-align: center;
    }

    .title-section h2 {
      font-size: 20px;
      font-weight: 600;
      color: #ccc;
      margin-top: 100px;
      text-align:right;
      border-bottom: 2px solid hsl(186, 63%, 85%);
      padding-bottom: 5px;
      display: inline-block;
      
    }

   

    /* Footer style */
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-top: 2px solid #d2e5e9;
      padding-top: 20px;
      font-size: 18px;
      
    }

    .logo-box {
      float: left;
      background: hwb(233 0% 93%);
      color: hwb(230 52% 7%);
      padding: 5px 15px;
      font-weight: bold;
      border-radius: 3px;
      
    }

    /* Photo inside cover (Farmer, Crop, or Tech Image) */
    .photo {
      position: absolute;
      bottom: 110px;  /* Positioning the photo from the bottom */
      left: 80%;
      transform: translateX(-50%);
      width: 200px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px #042d9651;
    }
    .logoimg {
  position: absolute;
  bottom: 200px;
  left: 50px;         /* move it to the left side */
  width: 350px;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 0 10px #042d9651;
}

    .author-name{
        font-weight: bold;
        background-color: hwb(232 89% 8% / 0.914);  /* light blue box */
  color: #042d96;             /* dark blue text */
  font-weight: bold;
  padding: 6px 15px;
  border-radius: 8px;
  box-shadow: 0 0 15px rgba(66, 133, 244, 0.6);
  animation: glow 2s ease-in-out infinite alternate;
}

/* glowing animation keyframes */
@keyframes glow {
  from {
    box-shadow: 0 0 10px rgba(66, 133, 244, 0.4);
  }
  to {
    box-shadow: 0 0 25px rgba(66, 133, 244, 0.9)}

    }
  </style>
</head>
<body>

  <div class="cover">
    <!-- Title and Description -->
    <div class="title-section">
      <h1>MASTERING PYTHON PROGRAMMING<br></h1>
      <h2>A Simple Guide TO Master Your Programming Skill</h2>
      
    </div>

    <!-- Footer Section -->
    <div class="footer">
      <div class="logo-box">PYTHON</div>
      <div class="author-name">Dhivya Dharshini</div>
      
    </div>

    <!-- Image inside the cover -->
    <img class="photo" src="P2.png" > 
    <img class="logoimg" src="pylogo.webp" > 
  </div>

</body>
</html>
```

## OUTPUT:
![WhatsApp Image 2025-12-22 at 10 48 18 PM](https://github.com/user-attachments/assets/fabafe8b-3ba9-4b25-a208-ce6ad9611b12)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
