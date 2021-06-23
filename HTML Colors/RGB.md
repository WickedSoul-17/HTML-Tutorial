# HTML RGB and RGBA Colors
---

An <abbr title="RED, GREEN, BLUE">RGB</abbr> color value represents RED, GREEN, and BLUE light sources.

An <abbr title="RED, GREEN, BLUE, ALPHA Channel">RGBA</abbr> color value is an extension of RGB with an Alpha channel (opacity).

<hr>

## RGB Color Values

In HTML, a color can be specified as an RGB value, using this formula:

**rgb(_red,_ _green_, _blue_)**

Each parameter (red, green, and blue) defines the intensity of the color with a value between 0 and 255.

This means that there are 256 x 256 x 256 = 16777216 possible colors!

For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255), and the other two (green and blue) are set to 0.

Another example, rgb(0, 255, 0) is displayed as green, because green is set to its highest value (255), and the other two (red and blue) are set to 0.

To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

<div>
 <h3>Example</h3>
<div>
<div style="line-height:80px;color:white;font-size:20px;font-weight:bold;text-align:center;font-family:Consolas, 'Courier New', Courier, monospace">
  <div>
    <div style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0)</div>
  </div>
  <div>
    <div style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255)</div>
  </div>
  <div>
    <div style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113)</div>
  </div>
  <div>
    <div style="background-color:rgb(238, 130, 238);">rgb(238, 130, 238)</div>
  </div>
  <div>
    <div style="background-color:rgb(255, 165, 0);">rgb(255, 165, 0)</div>
  </div>
  <div>
    <div style="background-color:rgb(106, 90, 205);">rgb(106, 90, 205)</div>
  </div>
</div>
</div>
</div>

<hr>

## Shades of Gray
Shades of gray are often defined using equal values for all three parameters:

<div>
 <h3>Example</h3>
<div>
<div style="line-height:80px;color:white;text-align:center;font-size:20px;font-weight:bold;font-family:Consolas, 'Courier New', Courier, monospace">
  <div>
    <div style="background-color:rgb(60, 60, 60);">rgb(60, 60, 60)</div>
  </div>
  <div>
    <div style="background-color:rgb(100, 100, 100);">rgb(100, 100, 100)</div>
  </div>
  <div>
    <div style="background-color:rgb(140, 140, 140);">rgb(140, 140, 140)</div>
  </div>
  <div>
    <div style="background-color:rgb(180, 180, 180);">rgb(180, 180, 180)</div>
  </div>
  <div>
    <div style="background-color:rgb(200, 200, 200);color:#555555">rgb(200, 200, 200)</div>
  </div>
  <div>
    <div style="background-color:rgb(240, 240, 240);color:#555555">rgb(240, 240, 240)</div>
  </div>
</div>
</div>
</div>

<hr>

## RGBA Color Values

RGBA color values are an extension of RGB color values with an Alpha channel - which specifies the opacity for a color.

An RGBA color value is specified with:

rgba(_red,_ _green_, _blue, alpha_)

The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all).

<div>
<h3>Example</h3>
<div>
<div style="
    line-height:80px;
    color:white;text-align:center;
    font-size:20px;
    font-weight:bold;
    font-family:Consolas, 'Courier New', Courier, monospace;
    background-image:url(img_bg_eyeicon.png), url(img_bg_transparent.gif);
    background-repeat:no-repeat, repeat;
    background-position:center, top left;
    background-color:#ffffff;">
  <div>
    <div style="background-color:rgba(255, 99, 71, 0);color:#555555;">rgba(255, 99, 71, 0)</div>
  </div>
  <div>
    <div style="background-color:rgba(255, 99, 71, 0.2);color:#555555;">rgba(255, 99, 71, 0.2)</div>
  </div>
  <div>
    <div style="background-color:rgba(255, 99, 71, 0.4);">rgba(255, 99, 71, 0.4)</div>
  </div>
  <div>
    <div style="background-color:rgba(255, 99, 71, 0.6);">rgba(255, 99, 71, 0.6)</div>
  </div>
  <div>
    <div style="background-color:rgba(255, 99, 71, 0.8);">rgba(255, 99, 71, 0.8)</div>
  </div>
  <div>
    <div style="background-color:rgba(255, 99, 71, 1);">rgba(255, 99, 71, 1)</div>
  </div>
</div>
</div>
</div>

[[HEX| NEXT -->]]