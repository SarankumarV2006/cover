# Ex.06 Book Front Cover Page Design
## Date: 04.11.2025

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
<head>
    <title>INTERNET INFRASTRUCTURE</title>
    <style>
        body {
            color: white; 
            font-family: Helvetica, sans-serif;
            background-color: black
            margin: 0;
            padding: 0;
        }

        .book {
            width: 726px;
            height: 820px;
            margin: auto;
            position: relative;
            background-image: url("BACKGRND.jpg"); /* Background image */
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
        }

        h1 {
            font-size: 70px;
            margin: 60px;
            margin-bottom: 0px;
        }

        h3 {
            margin: 0px 0px 90px 60px;
            position: absolute;
            bottom: 80px; /* adjusted to not overlap footer */
            font-size: xx-large;
            font-weight: bold;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }

        h4 {
            font-size: 20px;
            margin: 60px;
            margin-top: 10px;
            width: 430px;
        }

        #top {
            border-bottom: 2px solid rgb(177, 178, 245);
            padding: 100px 0px 5px 30px;
            display: inline-block;
        }

        footer {
            position: absolute;
            bottom: 0;
            width: 603px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-top: 2px solid rgb(77, 79, 163);
            padding: 10px 60px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-color: rgba(0, 0, 0, 0.6); /* dark transparent footer */
        }

        #HASH {
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        #HASH span {
            margin: 5px 0px;
            font-size: xx-large;
            font-weight: bold;
        }

        .photo {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid white;
        }

        .photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <section class="book">
        <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
        <h1>INTERNET INFRASTRUCTURE</h1>
        <h4>Networking, Web Services, and Cloud Computing</h4>
        <h3>Second Edition</h3>  

        <footer>
            <div id="HASH" class="blue-msg">
                <span>DR.S.NITHYASREE</span>
                <span id="end"><u>SEC</u></span>
            </div>
            <div class="photo">
                <img src=" profile pic.jpg" alt="Profile Photo">
            </div>
        </footer>
    </section>

    <!-- Adding previous portfolio structure here (e.g., Home, Skills, Projects) -->
    <!-- Make sure the previous sections are integrated as per your design preferences -->
</body>
```

## OUTPUT:


![alt text](<Screenshot 2025-11-10 095413.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
