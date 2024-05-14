# Ex.06 Book Front Cover Page Design
## Date:23.04.2024

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
''''
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>book-front-cover</title>
    <style>
        body{
            top:0;
        }
        .pic {
            /* background-image: url("images/coffee-cover.jpg");
            background-repeat: no-repeat;
            background-size: cover; */
            background-color: rgb(33, 98, 195);
            color: white;
            height: 100vh;
        }

        .layout {
            margin: 0% 25% 0% 25%;
        }

        p {
            margin-bottom: 0;
            padding-bottom: 0;
        }

        h4,
        h3 {

            margin: 0;

        }
    </style>
</head>

<body>
    <div class="layout">
        <div class="pic">
            <div style="margin:2%;">
                <p style="margin-top: 5%;padding:2% 0% 0% 0%;color:wheat;font-size: 25px;"><i>READER INSIGHT</i></p>
                <div style="width:25%;">
                    <hr style="padding:0% 2% 0% 0%">
                </div>
                <h1 style="text-align: center;margin-top:5%;font-size:45px;color:gold"><i>Brewed Culture: A Sip Through
                        History<i></h1>
                <p style="text-align: center">Step into the rich tapestry of coffee's journey through time and culture
                    in "Brewed Culture."</p>
                    <img style="align-items: center;border-radius: 10px;height: 200px; width: 200px;margin: 30px;" src="![Screenshot 2024-05-06 201716](https://github.com/dhinesh87/cover/assets/146917182/4975a229-f09e-46c7-8371-b9adabcb6970)
">
                <div style="display: flex;justify-content: space-between;font-size:25px;color:wheat;">
                    <h3 style="margin-top:15%;">Second Edition</h3>
                    <img src="![IMG-20230808-WA0002](https://github.com/dhinesh87/cover/assets/146917182/6fd4146a-df4d-4f67-b702-9909122bb221)
" width="100px" height="100px" style="margin-top:7%;">
                </div>
                <hr>
                <div style="display: flex;justify-content: space-between;font-size:25px;color:rgb(245, 179, 209)">
                    <h4>M.DHINESH </h4>
                    <h4>SAVEETHA CLG</h4>
                </div>
            </div>
        </div>
    </div>
</body>

</html>

''''
## OUTPUT:
![alt text](<Screenshot 2024-05-06 202323.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
