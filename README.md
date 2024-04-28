# Ex.06 Book Front Cover Page Design
## Date: 28.04.2024
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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .cover {
            width: 400px;
            height: 711.111111px;
            margin-left: auto;
            margin-right: auto;
            background-color: black;
            margin-top: auto;
            background-image: url(tlou2.jpg);
            background-size: contain
        }

        .title {
            text-align: left;
            font-size: 70px;
            padding-left: 120px;
            padding-top: 50px;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;

        }

        .tag {
            text-align: center;
            font-size: 15px;
            font-style: italic;


        }

        .author {
            text-align: center;
            padding-top: 270px;
            color: rgb(120, 108, 100);
            font-style: italic;
            font-size: 14px;

        }
    </style>
</head>

<body>
    <div class="cover">
        <div class="title">
            THE <br>LAST <br>OF US
        </div>
        <div class="tag">
            "If you're lost in the DARKNESS, look for the LIGHT"
        </div>
        <div class="author">
            An official Canon BOOK for the Award-Winning game from NAUGHTY DOG,<br>
            Written by HARIPRASHAAD RA
        </div>
    </div>





</body>

</html>
```

## OUTPUT:
![ex6](https://github.com/selvasachein/cover/assets/164654451/16892afc-0ec6-4ec3-ab37-840380eb20a1)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
