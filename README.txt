# Lego Gift Finder

## Content

This component is composed of:

1. `index.html`
2. `images/**/**` @ 1x, 1,5x, 2x, 3x - png / webp / jpg
3. `README.txt`
4. `fonts/cerapro-bold-webfont` + `.woff` / `.woff2`
5. `src/style.scss` + `style.css`
6. `nouislider.min.css`
7. `nouislider.min.js`
8. `wNumb.min.js`


## Usage

The component can easily be copy-pasted directly into your code with little adjustments to make it work. Copy everything between `<!-- Copy start HEAD -->` and `<!-- Copy end HEAD -->` from the head element and `<!-- Copy start BODY -->` and `<!-- Copy end BODY -->` from the body element.

Make sure to copy the fonts from the `fonts` folder - but only do this once for all elements using the same font. Once per page also include the global styles between <!-- Global styles to be included once per page --> and <!-- Global styles end -->.

The inline styles should be minified before put into production to optimize performance. The styles are left unminified for easier editability and readability.

### Retrieving results
The values from the search are stored in the 'searchResult' variable when the user clicks 'SEE RESULTS'. If you need to add additional logic when the user clicks the search button, do so in the 'getSearchResult' function.

## Dependencies
The Gift Finder uses three small external javascript libraries which are listed below.

### Category/Interest Slider
The Category/Interest Slider uses Tiny Slider 2 to display the category options in a draggable and responsive slider. 
https://github.com/ganlanyuan/tiny-slider

### Range sliders
The age and price range sliders are handled by noUiSlider to make it easy to retrieve values from the user selection.
The currency symbol and max price can easily be changed by editing the variables 'currencySymbol' and 'priceMax'.
https://github.com/leongersen/noUiSlider


### JavaScript Number & Money formatting
Tiny library used in the range sliders to format displayed numbers differently than the raw data.
https://github.com/leongersen/wnumb
