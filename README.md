# Ex.06 Book Front Cover Page Design
## Date:1.12.23

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
<html>
    <head>
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: rgb(233, 15, 226);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url("abd3.jpg");
                background-size: cover;
            }
            .insight{
                color: rgb(255, 0, 0);

            }
            .hrstyle{
                width: 100px;
            }
            .author{
                display: inline;
                position: relative;
                color: rgb(140, 0, 255);
                top: 270px;

                font-family: Georgia;
                font-size: medium;
            }
            .booktitle{
                font-family: 'Courier New', Courier, monospace;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;

            
            }
            .id{
                width: 400px;
                position: relative;
                top: 280px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top: 240px;
                left: 330px;
            }
            .ed{
                color: rgb(28, 177, 55);
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 175px;

            }
            .subtitle{
                font-family: 'Tahoma';
                font-size: large;
                position: relative;
                top: 40px;
            }
            .mypic{
                position: relative;
                top: 240px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
        </style>
        <title>Book Cover Page</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(0, 255, 47);">
            </div>
            <div class="booktitle">
                <h1>Screenless Display</h1>
            </div>
            <div class="subtitle">
                Holographic displays & retinal projection
            </div>
            <div class="mypic">
                <img src="abd4.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgba(255, 166, 0, 0.497);">
            </div>
            <div class="author">
                <p><b>Elamukilan</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Full Edition</b>
            </div>
        </div>

    </body>
</html>
```


## OUTPUT:

![Alt text](<screen shot book.jpg>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
