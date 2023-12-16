# Ex-06-Book-Cover-Design

NAME:YUVARAJ JOSHITHA

REFERENCE NUMBER : 23011447

DEPARTMENT:AIML

# AIM:

To design a book-cover-design using HTML and CSS.

# DESIGN PROCEDURE:

# STEP 1:

Start define the document type as HTML.
# STEP 2:

Open the HTML structure with necessary head and body sections.In the head section ,set
the title as Book Coverpage and define the styles for the bookcover.Use the CSS styles in
the code.The styles include:
background-color,
background-image,
background-position,
background-repeat,
cellpadding,
font-size,
font-family,
display,
line-height.

# STEP 3:

In the body section ,create a division with the text with respective to the headings:
"BEST NOVELT"
"KILLING IT SOFTLY "
"A Novel of Obsession"
"A Complusive read and peak psychological suspense"
"First Edition"
"Leopoldine Hugo"
"Penguin"

# STEP 4:

Close the HTML structure.

# CODE:
```
<!DOCTYPE html>
<html>
    <head>
        <title> Book Coverpage</title>
        <style>
            h1{
                color:bisque;
            }
            .bookpage{
                width: 400px;
                height: 650px;
                padding: 20px;
                background-image: url("COVER PAGE.jpg");
                background-position:center;
                background-repeat:no-repeat;
                margin-left:auto;
                margin-right:auto;

            
            
            }
            .toptext{
                color:red;
                padding: left 5px;
                font: size 14px;
                font-family:Arial, Helvetica, sans-serif;

            }
            .tophr{
                color:orangered;
                width:180px;




            }
            hr{
                color: orange;

            }
            .booktitle{
                font-family:Arial, Helvetica, sans-serif;
                padding:10px 10px 0px 10px;
                display:flex;
                align-items:center;
                justify-content:center;
                margin-right:10px;
                margin-left:10px;
                font-size:30px;
                line-height:normal;

            }
            .author{
                color:white;
                display: inline;
                position: relative;
                font-family: Arial, Helvetica, sans-serif;
                display:inline;
                font-size:20px;
                line-height:5px;

            }
            .sub-text{
                color:bisque;
                font-family:Arial, Helvetica, sans-serif;
                display: flex;
                line-height: 5px;
                margin-right:10px;
                margin-left: 10px;
                font-size: 14px;


            }
            .footer{
                color:orange;
                padding-top: 150px;

            }
            .image{
                color:red;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 22px;
                
            
            }
            .bottomhr{
                color: brown;
                width: 400px;

            }
            img{
                width: 90px;
                height: 100px;
                margin-right: 20px;
                vertical-align: bottom;

            }
            .edition{
                color: red;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 22px;
                line-height: bottom;

            }
        </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BEST NOVEL</div>
            <div class="tophr"><hr></div>
            <div class="booktitle"><h1>KILLING IT SOFTLY</h1></div>
            <h3 class="sub-text">&nbsp;&nbsp;&nbsp;A Novel of Obsession</h3>
            <h3 class="sub-text">&nbsp;&nbsp;&nbsp;A compulsive read and peak psychological suspense</h3>
            <div class="footer">
                <h2 class="edition">&nbsp;&nbsp;First Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="img.jpg"></h2>
                <div class="bottomhr"><hr></div>
                <div class="author"><h3>&nbsp;&nbsp;Leopoldine Hugo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Penguin</h3></div>

            </div>
        
        </div>
    </body>
</html>
```

# OUTPUT:

![Screenshot 2023-12-16 114649](https://github.com/Joshitha-YUVARAJ/Ex-06-Book-Cover-Design/assets/145742770/d1c1a6c4-253d-4476-b080-706a2efe6933)



# RESULT:

Thus the book-cover-design has been successfully created using HTML and CSS.
