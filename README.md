# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Design</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f9;
        }

        .book-cover {
            width: 300px;
            height: 450px;
            background-color:yellow;
            color:rgb(66, 196, 239);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            border-radius: 5px;
        }

        .book-cover h1 {
            font-size: 1.8em;
            text-align: center;
            margin: 0;
        }

        .book-cover h2 {
            font-size: 1.2em;
            text-align: center;
            margin: 0;
        }

        .book-cover img {
            width: 100%;
            height: 300px;
            border-radius: 5px;
        }
        

        .author {
            font-size: 1em;
            text-align: center;
        }

        .bottom {
            text-align: center;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <h1>BETTER THAN THE MOVIES</h1>
        <h2>New York best seller</h2>
        <img src="c:\Users\admin\Downloads\better than the movies.jpg" alt=" c:\Users\admin\Downloads\better than the movies.jpg" height="50px">
        <div class="author">Lynn Painter</div>
        <div class="bottom">enemies to friends to lovers...</div>
    </div>

</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-02 101606](https://github.com/user-attachments/assets/bd004c63-b0ea-4bc3-b65b-33cf07435062)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
