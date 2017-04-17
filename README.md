**SVG Inliner JS** will find all img's using svg as image, fetch data via AJAX and write in DOM all the source inline, making possible a better work with SVG and external CSS

How it Works
============

It's a simple setup. In your footer, add the below:

    <script src="svg.inliner.js"></script>

In the img tags using svg file as image, change src attribute to **svg-src** like this:

    <img svg-src="image.svg">

The output will be the exactly the same of svg file
