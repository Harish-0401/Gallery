# Ex.08 Design of Interactive Image Gallery
# Date:04.10.2025
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <link rel="stylesheet" href="gall.css">
</head>
<body>
    <h1>MY Gallery</h1>
   <div class="container">
    <div class="card"><img src="audi.jpg" alt=""></div>
   <div class="card"><img src="bmw.jpg" alt=""></div>
    <div class="card"><img src="ben.webp" alt=""></div>
     <div class="card"><img src="rolls.jpg" alt=""></div>
      <div class="card"><img src="dodge.jpg" alt=""></div>
   </div> 

</body>
</html>

body{
    background-color: black;
}
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 50vh;
}
img{
    width: 200px;
    border-radius: 10px;
    -webkit-box-animation: below 2.5px
    linear-gradient(transparent ,transparent,rgba(3,3,3,0.2));
    border: 3px ridge white;
    margin: 5px;
}
.card{
    transition: 0.5s ease ;
    cursor: pointer;;

}
.container:hover > :not(:hover){
    opacity: 0.5;
}
.card.hover{
    transform: scale(1.1);
    filter: grayscale(0%);
}

```
# OUTPUT:

<img width="1366" height="768" alt="2025-10-04 (2)" src="https://github.com/user-attachments/assets/10301db0-9028-445e-9c0a-bf149833aa8d" />


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
