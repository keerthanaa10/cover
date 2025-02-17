# Ex.06 Book Front Cover Page Design
## Date: 28-10-23

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>cover</title>
        <style>
            body {
                background-image: url('samp.png');
                background-size: 500px 750px;
                background-repeat: no-repeat;

            }
            p{
                font-family: Arial;
                text-align: center;
                margin-top: 0;
                margin-bottom: 0;
            }

            div{
                text-align: center;
            }

            .T1{
                font-weight: bold;
                color: rgb(243, 242, 240);
                font-size:17px;
                margin-top: 30px;
                margin-left: -1350px;

            }
            .l1{
                width: 20%;
                margin-left: -10px;
            }
            .T2{
                font-weight: bold;
                color: rgb(238, 233, 228);
                font-size:45px;
                margin-top:70px;
                margin-left: -1225px;
            }

            .T3{
                font-weight: bold;
                font-size:20px;
                margin-top: 480px;
                color: rgb(248, 247, 245);
                margin-left: -1350px;

            }
            .l2{
                width: 20%;
                margin-left: -10px;
            }
            .i1{
                height: 100px;
                margin-left: 410px;
                margin-top: -180px;
            }
        </style>
    </head>
    <body>
        <p class="T1">
            First Edition
        </p>
        <hr class="l1" color="white">
        
        <p class="T2">
            Clouds
        </p>
        
        <p class="T3">
            Keerthana Raghou
        </p>
        
        <hr class="l2">
        <img src="prof.jpeg" class="i1" style="vertical-align:bottom">
        
        
    </body>
</html>
```

## OUTPUT:
![Alt text](image.png)

![Alt text](image-1.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
