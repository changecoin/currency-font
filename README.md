# Currency Font
Currency Font provides 10 currency symbols in 6 weights in a sans-serif intended for use with Helvetica Neue.

## Available Symbols
* Australian Dollar
* Bitcoin
 * 2 vertical lines
 * 1 horizontal line
* Canadian Dollar
* Chinese Yuan
* Euro
* British Pound
* Indian Rupee
* Japanese Yen (same symbol as Chinese Yuan)
* Russian Ruble
* United States Dollar

## Available Weights
* 100 Ultralight
* 200 Thin
* 300 Light
* 400 Regular
* 500 Medium
* 600 Bold

## Usage
First decide how many of the weights you want to use and how you want to serve the fonts. At ChangeTip, we use all 6 weights and the Base64-encoded .woff files in our SCSS. I won't attempt to put together ready-to-use stylesheets for everyone because I'd probably get it wrong. :) Everything you should need will be in the ```/fonts/``` directory.

## Contributing
If you want to add a symbol to this font, please also send a pull request - we'd love to include it. To contribute, you'll need to start by setting up [FontCustom](https://github.com/FontCustom/fontcustom/). You'll also need a vector illustration application. I use Adobe Illustrator.

Using the template.ai file in this repo, create your symbol. Use Heveltica Neue, in one of its weights as the basis of your symbol and add and remove elements as needed. When you're finished, trim the artboard width (width only) to the bounding box of the original text symbol. Break the text into outlines, join paths using Pathfinder, and export as SVG. Repeat for every weight.

Once all of your SVGs are ready, use FontCustom to assemble the font. 
