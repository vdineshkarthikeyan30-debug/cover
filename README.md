# Ex.05 Book Cover Page Design
## Date:26/12/2025

## AIM:
To design a book back cover page using HTML and CSS.

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
dk.html

<html>
    <head>
        <title>Cover Page</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body >
        <div class="description">
            <h1>About the Book</h1>
            <hr color="blue" size="6">

      
            <br>
            <br>
            The Book <span class="color">"Operating System Concepts"</span> is a widely-used textbook covering fundamental computer design principles, modern architectural trends (RISC, CISC, superscalar), and the crucial role of performance, using concrete examples like the Pentium and MIPS processors to explain concepts clearly for undergrad/grad students in CS/CE/EE. 
            
            <div class="quote">
                Understanding micro-level instruction execution, data flow, and memory hierarchy is key to designing high-performance systems            </div>
            <br>
            <br>
        
            
            
            <div class="ifo">
                <img src="my  pho.jpeg" alt="Author Photo" style="height: 180px;width: 170px;">
                <div class="protofolio">
                    <b>DINESH KARITHIKEYAN V (25012548)</b>
                    <br><br>
                    Dinesh karthikeyan v is a Tech enthusiast, coder, and lifelong learner. I have a strong curiosity for software engineering and how modern systems tick. I spend my time exploring innovative ideas, debugging complex problems, and leveling up my technical skills. I’m excited to contribute to the world of development, one project at a time
                </div>
            </div>
            <br>
            
            <div class="footer">
                SEC Publishers <br> Printed in India
                <br>
                <div class="Price">
                Price: $100
                </div>      
                   
            </div>
        </div>
    </body>
</html>


styles.css


body {
            font-size: Arial;
            
        }
        .description
            {
            height: 800px;
            width: 500px;
            background-image:url(book.jpeg);
            background-size: cover;
            color:rgb(164, 14, 159);
            padding: 20px;
            margin: 30px auto;
            border: 2px solid red;
            border-radius: 10px;
        }
        .quote {
            background: rgb(13, 13, 13);
            padding: 10px;
            border-left: 10px solid rgb(231, 78, 83);
            margin: 20px 0;
            font-style: italic;
            text-align: center;
            border-end-end-radius: 10px;
        }
        .ifo
        {
            display: flex;
        }
        .protofolio 
        {
            background:rgb(216, 235, 6);
            gap: 25px;
            padding: 15px;
            border-start-end-radius: 5px;
        }
    
        .footer {
            background:rgb(9, 169, 233);
            color: rgb(57, 125, 79);
            padding: 5px;
            display: flex;
            justify-content: space-between;
            margin-top: 10px;
            border-end-end-radius: 5px;
        }


```

## OUTPUT:

![alt text](<Screenshot (36).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
