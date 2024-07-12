# Welcome to Sahir's HTML learning Website
### Here you will not need to take templates or any other help from others!
#### Lets start!
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
# What are headings ,paragraphs and linebrakes are?
### Headings are called h1,h2,h3,h4,h5,h6 in html
These heading starts biggest to smallest like h1 is the biggest heading and h6 is the smallest heading!
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <h2> heading</h2>
    <h3> heading</h3>
    <h4> heading</h4>
    <h5> heading</h5>
    <h6> heading</h6>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### Paragraphs are called "p" in HTML
For example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <p>Hello! This is a paragraph, there is no difference in pargraph and a line in html </p>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### Line breaks are used for making next line and they are called br in HTML
For example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <p>I want to make a break after this sentence <br> So i used br!</p>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
# What are Attributes in HTML
## HTML attributes provide additional information about HTML elements.
### href attribute
the a tag defines hyperlink and href tells where the link should go!
For example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <a href="google.com">Google</a>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### src attribute
the img tag defines the image and the src tells the path to img
For example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <img src="football.png">

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### width and height attribute
image tag also contains the width and height attribute to tell the width and height of img.
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <img src="ball.png" width="200px" height="300px"> 

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### alt attribute
img tag also contain alt attribute because if incase the image is not displayed so the alt text is displayed instead of image
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <img scr="basketball.png" width="200px" height="300px" alt="basketball">
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### class attribute
tthis attribute is used to give the element an identity to find it.
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title> Example </title>

    <!--css-->
    <style>
      .heading{
        text-align:center;
      }
    </style>
  </head>
  <body>
    <!--html-->
    <h1 class="heading"> Hello </h1>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
> **_Note:_** other css properties you will learn in css tutorial

### id attribute
id attribute also works like class and defined as #
and it is also used for javascript.

### style attribute
style attribute is to give the styles immidiatly to the element
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title> Example </title>

    <!--css-->
    <style>

      
    </style>
  </head>
  <body>
    <!--html-->
    <h1 style="text-align:center;"> Hello </h1>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
> **_Note:_** other css properties you will learn in css tutorial


# What are formatting elements in html
## Fromating elements are used to format the text
### bold element
it is used to make the text bold and it is called b in HTML
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <b>This is bold text</b>
    
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### Strong element 
this element is used to give importance to text and it is called strong in HTML
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <strong>This is strong text</strong>
    
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
## HTML i and em element
### i element
this element is used to make th text italic.
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <h1><i> Hello World </i><h1>
    
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### em element 
it defines the emphasized text typically the text is displayed italic inside it.
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello World </h1>
    <h1><em> Hello World </em></h1>
    
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### small element
it defines the the smaller txt
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <p> Hello World </p>
    <small> Hello World </small>
    
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### mark element 
it is used to highlight any txt 
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello <mark> World </mark></h1>
    
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### del element 
it defines text that has been deleted from a document. Browsers will usually strike a line through deleted text
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello <del> Universe </del> World </h1>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### ins element
it defines an inserted text in element it basically underlines th inserted text
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello <del>Universe</del> <ins>World</ins> </h1>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### sub element
this element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas.
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <p> This is <sub> suscripted </sub> text.</p>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### sup element 
this element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes
for example: 
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <p> This is <sup> superscripted </sup> text.</p>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
# What is HTML page title
### It is the text which is shown in the title bar
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title> Example </title>

    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello </h1>

    <!--js-->
    <script>

    </script>
  </body>
</html>
```
# What are div in HTML
### it is by default a block element, meaning that it takes all available width, and comes with line breaks before and after
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title> Example </title>

    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <h1> Hello </h1>
    <p> It says <div>Hello</div> only</p>
    <!--js-->
    <script>

    </script>
  </body>
</html>
```
### div has no required attributes but style, height, width, id and class is used with it.
### divs are also used as containers
for example:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title> Example </title>

    <!--css-->
    <style>

    </style>
  </head>
  <body>
    <!--html-->
    <div style="background-color: yellow;">
      <h1> London </h1> <br>
      <h3> It is capital city of england </h3>
      <h3> London is a city </h3>
    </div>



    <!--js-->
    <script>

    </script>
  </body>
</html>
```















