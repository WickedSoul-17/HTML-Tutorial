# HTML Colors
---

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

<hr>

## Color Names

In HTML, a color can be specified by using a color name:

 <div class="w3-row w3-center" style="margin:0 -16px;line-height:80px;color:white;">
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:tomato;">Tomato</div>
  </div>
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:orange;">Orange</div>
  </div>
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:dodgerblue;">DodgerBlue</div>
  </div>
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:mediumseagreen;">MediumSeaGreen</div>
  </div>
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:gray;">Gray</div>
  </div>
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:slateblue;">SlateBlue</div>
  </div>
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:violet;">Violet</div>
  </div>
  <div class="w3-col l3 m6 w3-padding">
    <div style="background-color:lightgray;color:#444444">LightGray</div>
  </div>
</div>


HTML supports [140 standard color names](https://www.w3schools.com/colors/colors_names.asp).

<hr>

## Background Color

You can set the background color for HTML elements:

<div style="background-color:dodgerblue; text-align:center;color:white;font-size:24px;">Hello World</div>
<br>
<div style="background-color:tomato;color:white;"><br>
  Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
  Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.<br><br>
</div>

### Example
```
<h1 style="background-color:DodgerBlue;">Hello World</h1>  
<p style="background-color:Tomato;">Lorem ipsum...</p>
```

<hr>

## Text Color

You can set the color of text:

<h1 style="color:Tomato;">Hello World</h1>

<p style="color:dodgerblue;" >Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>

<p style="color:Mediumseagreen;" >Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>

### Example
```
<h1 style="color:Tomato;">Hello World</h1>  
<p style="color:DodgerBlue;">Lorem ipsum...</p>  
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

<hr>

## Border Color

You can set the color of borders:

<h1 style="border:2px solid Tomato;">Hello World</h1>  
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>  
<h1 style="border:2px solid Violet;">Hello World</h1>

### Example
```
<h1 style="border:2px solid Tomato;">Hello World</h1>  
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>  
<h1 style="border:2px solid Violet;">Hello World</h1>
```

<hr>

## Color Values

In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

The following three \<div> elements have their background color set with RGB, HEX, and HSL values:

<div style="line-height:60px;color:white;font-size:20px;font-weight:bold;text-align:center;font-family:Consolas, 'Courier New', Courier, monospace">
  <div style="background-color:rgb(255, 99, 71);margin:10px 0;">rgb(255, 99, 71)</div>
  <div style="background-color:#ff6347;margin:10px 0;">#ff6347</div>
  <div style="background-color:hsl(9, 100%, 64%);margin:10px 0;">hsl(9, 100%, 64%)</div>
</div>

The following two \<div> elements have their background color set with RGBA and HSLA values, which adds an Alpha channel to the color (here we have 50% transparency):

<div style="line-height:60px;color:white;font-size:20px;text-align:center;font-weight:bold;font-family:Consolas, 'Courier New', Courier, monospace">
  <div style="background-color:rgba(255, 99, 71, 0.5);margin:10px 0;">rgba(255, 99, 71, 0.5)</div>
  <div style="background-color:hsla(9, 100%, 64%, 0.5);margin:10px 0;">hsla(9, 100%, 64%, 0.5)</div>
</div>

### Example
```
<h1 style="background-color:rgb(255, 99, 71);">...</h1>  
<h1 style="background-color:#ff6347;">...</h1>  
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>  
  
<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>  
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```

<hr>

### Learn more about Color Values

You will learn more about [RGB](https://www.w3schools.com/html/html_colors_rgb.asp), [HEX](https://www.w3schools.com/html/html_colors_hex.asp) and [HSL](https://www.w3schools.com/html/html_colors_hsl.asp) in the next chapters.

[[RGB| NEXT -->]]