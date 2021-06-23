# HTML HSL and HSLA Colors
---

HSL stands for hue, saturation, and lightness.

HSLA color values are an extension of HSL with an Alpha channel (opacity).

<hr>

## HSL Color Values

In HTML, a color can be specified using hue, saturation, and lightness (HSL) in the form:

hsl(_hue_, _saturation_, _lightness_)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

Lightness is also a percentage value, 0% is black, and 100% is white.

<div>
 <h3>Example</h3>
<div>

<div style="line-height:80px;color:white;font-size:20px;font-weight:bold;text-align:center;font-family:Consolas, 'Courier New', Courier, monospace">
  <div>
    <div style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(240, 100%, 50%)">hsl(240, 100%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%)</div>
  </div>
  <div>
    <div style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</div>
  </div>
  <div>
    <div style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%)</div>
  </div>
</div>
</div>
</div>

<hr>

### Saturation

Saturation can be described as the intensity of a color.

100% is pure color, no shades of gray

50% is 50% gray, but you can still see the color.

0% is completely gray, you can no longer see the color.

<div>
 <h3>Example</h3>
<div>

<div style="line-height:80px;color:white;font-size:20px;font-weight:bold;text-align:center;font-family:Consolas, 'Courier New', Courier, monospace">
  <div>
    <div style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 80%, 50%)">hsl(0, 80%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 60%, 50%);">hsl(0, 60%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 40%, 50%);">hsl(0, 40%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 20%, 50%);">hsl(0, 20%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 0%, 50%);">hsl(0, 0%, 50%)</div>
  </div>
</div>
</div>
</div>

<hr>

### Lightness

The lightness of a color can be described as how much light you want to give the color, where 0% means no light (black), 50% means 50% light (neither dark nor light) 100% means full lightness (white).

<div>
 <h3>Example</h3>
<div>
<div style="line-height:80px;color:white;font-size:20px;font-weight:bold;text-align:center;font-family:Consolas, 'Courier New', Courier, monospace">
  <div>
    <div style="background-color:hsl(0, 100%, 0%);">hsl(0, 100%, 0%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 100%, 25%)">hsl(0, 100%, 25%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 100%, 75%);">hsl(0, 100%, 75%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 100%, 90%);color:#555555">hsl(0, 100%, 90%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 100%, 100%);color:#555555;">hsl(0, 100%, 100%)</div>
  </div>
</div>
</div>
</div>

<hr>

## Shades of Gray

Shades of gray are often defined by setting the hue and saturation to 0, and adjust the lightness from 0% to 100% to get darker/lighter shades:

<div>
 <h3>Example</h3>
<div>
<div style="line-height:80px;color:white;font-size:20px;font-weight:bold;text-align:center;font-family:Consolas, 'Courier New', Courier, monospace">
  <div>
    <div style="background-color:hsl(0, 0%, 20%);">hsl(0, 0%, 20%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 0%, 30%)">hsl(0, 0%, 30%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 0%, 40%);">hsl(0, 0%, 40%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 0%, 60%);">hsl(0, 0%, 60%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 0%, 70%);color:#555555">hsl(0, 0%, 70%)</div>
  </div>
  <div>
    <div style="background-color:hsl(0, 0%, 90%);color:#555555;">hsl(0, 0%, 90%)</div>
  </div>
</div>
</div>
</div>

<hr>

## HSLA Color Values

HSLA color values are an extension of HSL color values with an Alpha channel - which specifies the opacity for a color.

An HSLA color value is specified with:

hsla(_hue,_ _saturation_, _lightness, alpha_)

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
    <div style="background-color:hsla(9, 100%, 64%, 0);color:#555555;">hsla(9, 100%, 64%, 0)</div>
  </div>
  <div>
    <div style="background-color:hsla(9, 100%, 64%, 0.2);color:#555555;">hsla(9, 100%, 64%, 0.2)</div>
  </div>
  <div>
    <div style="background-color:hsla(9, 100%, 64%, 0.4);">hsla(9, 100%, 64%, 0.4)</div>
  </div>
  <div>
    <div style="background-color:hsla(9, 100%, 64%, 0.6);">hsla(9, 100%, 64%, 0.6)</div>
  </div>
  <div>
    <div style="background-color:hsla(9, 100%, 64%, 0.8);">hsla(9, 100%, 64%, 0.8)</div>
  </div>
  <div>
    <div style="background-color:hsla(9, 100%, 64%, 1);">hsla(9, 100%, 64%, 1)</div>
  </div>
</div>
</div>
</div>

[[HTML CSS| NEXT -->]]