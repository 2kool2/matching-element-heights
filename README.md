<h1>Matching Element Heights</h1>

Easily match-up heights across a set of non-linear elements.<br>
Allows for multiple sets, with each set having a different height defined by a JavaScript injected inline ``` min-height ```.

<strong>CodePen demo: <a href="http://codepen.io/2kool2/pen/MbqGOQ">Matching element heights</a></strong>

Super small vanilla script: Approx 417 bytes minified and gzipped (694 bytes uncompressed) with zero dependencies.


<br>
<h2>How it works</h2>

Add data attribute to the elements you wish to equalise and give it a value: ``` data-matchHeights="A" ```.<br>
Ensure the elements each have ``` display: block; ```.<br>
Elments must have ``` box-sizing: border-box; ```.<br>
Then run the script.

All elements with the same data attribute value have the same ``` min-height ``` applied.<br>
The ``` min-height ``` value is equal to the tallest elements height and is recalculated when the browser is resized.

<br>
<h2>Basic usage</h2>

Add data attributes to the elements:

```html
<div data-matchHeights="A">Yada, yada, yada.</div>
&hellip;
<div data-matchHeights="A">Yada.</div>
&hellip;
<div data-matchHeights="A">Yada, yada, yada. Yada, yada, yada. Yada, yada, yada.</div>
```

Include a link to the script:

```html
<script src="js/matchHeights.1.0.min.js"></script>
```

<br>
<h2>Browser support</h2>

Tested Mac and PC: IE9+, Chrome, Safari, Firefox.


<hr>
Mike Foskett @ <a href="https://websemantics.uk/">webSemantics</a>
