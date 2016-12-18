#Matching Element Heights

Easily match-up heights across a set of non-linear elements.
Allows for multiple sets, with each set having a different height defined by an inline min-height.

<strong>CodePen demo: <a href="http://codepen.io/2kool2/pen/MbqGOQ">Matching element heights</a></strong>

Super small vanilla script: Approx 417 bytes minified and gzipped (694 bytes uncompressed). No dependencies.


<br>
##How it works

Add data attribute to the elements you wish to equalise and give it a value: data-matchHeights="A".
Ensure the elements each have display: block;.
Then run the script.

All elements with the same data attribute value have the same min-height applied.
The min-height is equal to the tallest elements height and is recalculated when the browser width changes.

<br>
##Basic usage

Include a link to the script:

```html
<script src="js/matchHeights.1.0.min.js"></script>
```

Add data attributes to the elements:

```html
<div data-matchHeights="A">Yada, yada, yada.</div>
&hellip;
<div data-matchHeights="A">Yada.</div>
&hellip;
<div data-matchHeights="A">Yada, yada, yada. Yada, yada, yada. Yada, yada, yada.</div>
```

<br>
##Browser support

Tested Mac and PC: IE9+, Chrome, Safari, Firefox.


<hr>
Mike Foskett @ <a href="https://websemantics.uk/">webSemantics</a>
