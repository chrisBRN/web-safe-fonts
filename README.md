# Web Safe Font Families

A collection of web safe font families in a code ready format. 

For consistency all font family names are wrapped in single quotes. This is also inline with the CSS spec [recommendation.](https://www.w3.org/TR/2018/REC-css-fonts-3-20180920/#propdef-font-family)

"To avoid mistakes in escaping, it is recommended to quote font family names that contain white space, digits, or punctuation characters other than hyphens"

The font families themselves were largely taken from [Kinsta](https://kinsta.com/blog/web-safe-fonts/), if your interested in web safe fonts I'd also recommend [Maddy Osman via Hubspot](https://blog.hubspot.com/website/web-safe-html-css-fonts)


## Vanilla CSS

### Serif
```css
font-family: 'Baskerville', 'Baskerville Old face', 'Garamond', 'Times New Roman', serif;
font-family: 'Bodoni MT', 'Bodoni 72', 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Times New Roman', serif;
font-family: 'Calisto MT', 'Bookman Old Style', 'Bookman', 'Goudy Old Style', 'Garamond', 'Hoefler Text', 'Bitstream Charter', 'Georgia', serif;
font-family: 'Cambria', 'Georgia', serif;
font-family: 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Calisto MT', 'Times New Roman', serif;
font-family: 'Garamond', 'Baskerville', 'Baskerville Old Face', 'Hoefler Text', 'Times New Roman', serif;
font-family: 'Georgia', 'Times', 'Times New Roman', serif;
font-family: 'Goudy Old Style', 'Garamond', 'Big Caslon', 'Times New Roman', serif;
font-family: 'Lucida Bright', 'Georgia', serif;
font-family: 'Palatino', 'Palatino Linotype', 'Palatino LT STD', 'Book Antiqua', 'Georgia', serif;
font-family: 'Perpetua', 'Baskerville', 'Big Caslon', 'Palatino Linotype', 'Palatino', serif;
font-family: 'Rockwell', 'Courier Bold', 'Courier', 'Georgia', 'Times', 'Times New Roman', serif;
```

### Sans-Serif
```css
font-family: 'Arial', 'Helvetica Neue', 'Helvetica', sans-serif;
font-family: 'Calibri', 'Candara', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
font-family: 'Candara', 'Calibri', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
font-family: 'Century Gothic', 'CenturyGothic', 'AppleGothic', sans-serif;
font-family: 'Dejavu Sans', 'Arial', 'Verdana', sans-serif;
font-family: 'Franklin Gothic', 'Arial Bold', sans-serif;
font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', sans-serif;
font-family: 'Helvetica Neue', 'Helvetica', 'Arial', sans-serif;
font-family: 'Impact', 'Charcoal', 'Helvetica Inserat', 'Bitstream Vera Sans Bold', 'Arial Black', sans serif;
font-family: 'Lucida Sans', 'Helvetica', 'Arial', sans-serif;
font-family: 'Optima', 'Segoe', 'Segoe UI', 'Candara', 'Calibri', 'Arial', sans-serif;
font-family: 'Segoe UI', 'Frutiger', 'Dejavu Sans', 'Helvetica Neue', 'Arial', sans-serif;
font-family: 'Tahoma', 'Verdana', 'Segoe', sans-serif;
font-family: 'Trebuchet MS', 'Lucida Grande', 'Lucida Sans Unicode', 'Lucida Sans', sans-serif;
font-family: 'Verdana', 'Geneva', sans-serif;
```
### Monospace
```css
font-family: 'Consolas', 'Monaco', monospace;
font-family: 'Courier New', 'Courier', 'Lucida Sans Typewriter', 'Lucida Typewriter', monospace;
```

## CSS Variables

### Serif
```css
--font-baskerville: 'Baskerville', 'Baskerville Old face', 'Garamond', 'Times New Roman', serif;
--font-bodoni: 'Bodoni MT', 'Bodoni 72', 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Times New Roman', serif;
--font-calisto: 'Calisto MT', 'Bookman Old Style', 'Bookman', 'Goudy Old Style', 'Garamond', 'Hoefler Text', 'Bitstream Charter', 'Georgia', serif;
--font-cambria: 'Cambria', 'Georgia', serif;
--font-didot: 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Calisto MT', 'Times New Roman', serif;
--font-garamond: 'Garamond', 'Baskerville', 'Baskerville Old Face', 'Hoefler Text', 'Times New Roman', serif;
--font-georgia: 'Georgia', 'Times', 'Times New Roman', serif;
--font-goudy: 'Goudy Old Style', 'Garamond', 'Big Caslon', 'Times New Roman', serif;
--font-lucida: 'Lucida Bright', 'Georgia', serif;
--font-palatino: 'Palatino', 'Palatino Linotype', 'Palatino LT STD', 'Book Antiqua', 'Georgia', serif;
--font-perpetua: 'Perpetua', 'Baskerville', 'Big Caslon', 'Palatino Linotype', 'Palatino', serif;
--font-rockwell: 'Rockwell', 'Courier Bold', 'Courier', 'Georgia', 'Times', 'Times New Roman', serif;
```

### Sans-Serif
```css
--font-arial: 'Arial', 'Helvetica Neue', 'Helvetica', sans-serif;
--font-calibri: 'Calibri', 'Candara', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
--font-candara: 'Candara', 'Calibri', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
--font-century: 'Century Gothic', 'CenturyGothic', 'AppleGothic', sans-serif;
--font-dejavu: 'Dejavu Sans', 'Arial', 'Verdana', sans-serif;
--font-franklin: 'Franklin Gothic', 'Arial Bold', sans-serif;
--font-gill: 'Gill Sans', 'Gill Sans MT', 'Calibri', sans-serif;
--font-helvetica: 'Helvetica Neue', 'Helvetica', 'Arial', sans-serif;
--font-impact: 'Impact', 'Charcoal', 'Helvetica Inserat', 'Bitstream Vera Sans Bold', 'Arial Black', sans serif;
--font-lucida: 'Lucida Sans', 'Helvetica', 'Arial', sans-serif;
--font-optima: 'Optima', 'Segoe', 'Segoe UI', 'Candara', 'Calibri', 'Arial', sans-serif;
--font-segoe: 'Segoe UI', 'Frutiger', 'Dejavu Sans', 'Helvetica Neue', 'Arial', sans-serif;
--font-tahoma: 'Tahoma', 'Verdana', 'Segoe', sans-serif;
--font-trebuchet: 'Trebuchet MS', 'Lucida Grande', 'Lucida Sans Unicode', 'Lucida Sans', sans-serif;
--font-verdana: 'Verdana', 'Geneva', sans-serif;
```
### Monospace
```css
--font-consolas: 'Consolas', 'Monaco', monospace;
--font-courier: 'Courier New', 'Courier', 'Lucida Sans Typewriter', 'Lucida Typewriter', monospace;
```

## Sass/Scss Variables

### Serif
```scss
$font-baskerville: 'Baskerville', 'Baskerville Old face', 'Garamond', 'Times New Roman', serif;
$font-bodoni: 'Bodoni MT', 'Bodoni 72', 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Times New Roman', serif;
$font-calisto: 'Calisto MT', 'Bookman Old Style', 'Bookman', 'Goudy Old Style', 'Garamond', 'Hoefler Text', 'Bitstream Charter', 'Georgia', serif;
$font-cambria: 'Cambria', 'Georgia', serif;
$font-didot: 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Calisto MT', 'Times New Roman', serif;
$font-garamond: 'Garamond', 'Baskerville', 'Baskerville Old Face', 'Hoefler Text', 'Times New Roman', serif;
$font-georgia: 'Georgia', 'Times', 'Times New Roman', serif;
$font-goudy: 'Goudy Old Style', 'Garamond', 'Big Caslon', 'Times New Roman', serif;
$font-lucida: 'Lucida Bright', 'Georgia', serif;
$font-palatino: 'Palatino', 'Palatino Linotype', 'Palatino LT STD', 'Book Antiqua', 'Georgia', serif;
$font-perpetua: 'Perpetua', 'Baskerville', 'Big Caslon', 'Palatino Linotype', 'Palatino', serif;
$font-rockwell: 'Rockwell', 'Courier Bold', 'Courier', 'Georgia', 'Times', 'Times New Roman', serif;
```

### Sans-Serif
```scss
$font-arial: 'Arial', 'Helvetica Neue', 'Helvetica', sans-serif;
$font-calibri: 'Calibri', 'Candara', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
$font-candara: 'Candara', 'Calibri', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
$font-century: 'Century Gothic', 'CenturyGothic', 'AppleGothic', sans-serif;
$font-dejavu: 'Dejavu Sans', 'Arial', 'Verdana', sans-serif;
$font-franklin: 'Franklin Gothic', 'Arial Bold', sans-serif;
$font-gill: 'Gill Sans', 'Gill Sans MT', 'Calibri', sans-serif;
$font-helvetica: 'Helvetica Neue', 'Helvetica', 'Arial', sans-serif;
$font-impact: 'Impact', 'Charcoal', 'Helvetica Inserat', 'Bitstream Vera Sans Bold', 'Arial Black', sans serif;
$font-lucida: 'Lucida Sans', 'Helvetica', 'Arial', sans-serif;
$font-optima: 'Optima', 'Segoe', 'Segoe UI', 'Candara', 'Calibri', 'Arial', sans-serif;
$font-segoe: 'Segoe UI', 'Frutiger', 'Dejavu Sans', 'Helvetica Neue', 'Arial', sans-serif;
$font-tahoma: 'Tahoma', 'Verdana', 'Segoe', sans-serif;
$font-trebuchet: 'Trebuchet MS', 'Lucida Grande', 'Lucida Sans Unicode', 'Lucida Sans', sans-serif;
$font-verdana: 'Verdana', 'Geneva', sans-serif;
```
### Monospace
```scss
$font-consolas: 'Consolas', 'Monaco', monospace;
$font-courier: 'Courier New', 'Courier', 'Lucida Sans Typewriter', 'Lucida Typewriter', monospace;
```

## JS

```js
const fonts = {
    serif: {
        baskerville: "'Baskerville', 'Baskerville Old face', 'Garamond', 'Times New Roman', serif",
        bodoni: "'Bodoni MT', 'Bodoni 72', 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Times New Roman', serif",
        calisto: "'Calisto MT', 'Bookman Old Style', 'Bookman', 'Goudy Old Style', 'Garamond', 'Hoefler Text', 'Bitstream Charter', 'Georgia', serif",
        cambria: "'Cambria', 'Georgia', serif",
        didot: "'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Calisto MT', 'Times New Roman', serif",
        garamond: "'Garamond', 'Baskerville', 'Baskerville Old Face', 'Hoefler Text', 'Times New Roman', serif",
        georgia: "'Georgia', 'Times', 'Times New Roman', serif",
        goudy: "'Goudy Old Style', 'Garamond', 'Big Caslon', 'Times New Roman', serif",
        lucida: "'Lucida Bright', 'Georgia', serif",
        palatino: "'Palatino', 'Palatino Linotype', 'Palatino LT STD', 'Book Antiqua', 'Georgia', serif",
        perpetua: "'Perpetua', 'Baskerville', 'Big Caslon', 'Palatino Linotype', 'Palatino', serif",
        rockwell: "'Rockwell', 'Courier Bold', 'Courier', 'Georgia', 'Times', 'Times New Roman', serif",
    },
    sans: {
        arial: "'Arial', 'Helvetica Neue', 'Helvetica', sans-serif",
        calibri: "'Calibri', 'Candara', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif",
        candara: "'Candara', 'Calibri', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif",
        century: "'Century Gothic', 'CenturyGothic', 'AppleGothic', sans-serif",
        dejavu: "'Dejavu Sans', 'Arial', 'Verdana', sans-serif",
        franklin: "'Franklin Gothic', 'Arial Bold', sans-serif",
        gill: "'Gill Sans', 'Gill Sans MT', 'Calibri', sans-serif",
        helvetica: "'Helvetica Neue', 'Helvetica', 'Arial', sans-serif",
        impact: "'Impact', 'Charcoal', 'Helvetica Inserat', 'Bitstream Vera Sans Bold', 'Arial Black', sans serif",
        lucida: "'Lucida Sans', 'Helvetica', 'Arial', sans-serif",
        optima: "'Optima', 'Segoe', 'Segoe UI', 'Candara', 'Calibri', 'Arial', sans-serif",
        segoe: "'Segoe UI', 'Frutiger', 'Dejavu Sans', 'Helvetica Neue', 'Arial', sans-serif",
        tahoma: "'Tahoma', 'Verdana', 'Segoe', sans-serif",
        trebuchet: "'Trebuchet MS', 'Lucida Grande', 'Lucida Sans Unicode', 'Lucida Sans', sans-serif",
        verdana: "'Verdana', 'Geneva', sans-serif",
    },
    mono: {
        consolas: "'Consolas', 'Monaco', monospace",
        courier: "'Courier New', 'Courier', 'Lucida Sans Typewriter', 'Lucida Typewriter', monospace",
    }
}
```

## JS camelCase / React / ReactNative

```js
const styles = StyleSheet.create({
    serif: {
        fontFamily: 'Baskerville', 'Baskerville Old face', 'Garamond', 'Times New Roman', serif;
        fontFamily: 'Bodoni MT', 'Bodoni 72', 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Times New Roman', serif;
        fontFamily: 'Calisto MT', 'Bookman Old Style', 'Bookman', 'Goudy Old Style', 'Garamond', 'Hoefler Text', 'Bitstream Charter', 'Georgia', serif;
        fontFamily: 'Cambria', 'Georgia', serif;
        fontFamily: 'Didot', 'Didot LT STD', 'Hoefler Text', 'Garamond', 'Calisto MT', 'Times New Roman', serif;
        fontFamily: 'Garamond', 'Baskerville', 'Baskerville Old Face', 'Hoefler Text', 'Times New Roman', serif;
        fontFamily: 'Georgia', 'Times', 'Times New Roman', serif;
        fontFamily: 'Goudy Old Style', 'Garamond', 'Big Caslon', 'Times New Roman', serif;
        fontFamily: 'Lucida Bright', 'Georgia', serif;
        fontFamily: 'Palatino', 'Palatino Linotype', 'Palatino LT STD', 'Book Antiqua', 'Georgia', serif;
        fontFamily: 'Perpetua', 'Baskerville', 'Big Caslon', 'Palatino Linotype', 'Palatino', serif;
        fontFamily: 'Rockwell', 'Courier Bold', 'Courier', 'Georgia', 'Times', 'Times New Roman', serif;
    },
    sans: {        
        fontFamily: 'Arial', 'Helvetica Neue', 'Helvetica', sans-serif;
        fontFamily: 'Calibri', 'Candara', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
        fontFamily: 'Candara', 'Calibri', 'Segoe', 'Segoe UI', 'Optima', 'Arial', sans-serif;
        fontFamily: 'Century Gothic', 'CenturyGothic', 'AppleGothic', sans-serif;
        fontFamily: 'Dejavu Sans', 'Arial', 'Verdana', sans-serif;
        fontFamily: 'Franklin Gothic', 'Arial Bold', sans-serif;
        fontFamily: 'Gill Sans', 'Gill Sans MT', 'Calibri', sans-serif;
        fontFamily: 'Helvetica Neue', 'Helvetica', 'Arial', sans-serif;
        fontFamily: 'Impact', 'Charcoal', 'Helvetica Inserat', 'Bitstream Vera Sans Bold', 'Arial Black', sans serif;
        fontFamily: 'Lucida Sans', 'Helvetica', 'Arial', sans-serif;
        fontFamily: 'Optima', 'Segoe', 'Segoe UI', 'Candara', 'Calibri', 'Arial', sans-serif;
        fontFamily: 'Segoe UI', 'Frutiger', 'Dejavu Sans', 'Helvetica Neue', 'Arial', sans-serif;
        fontFamily: 'Tahoma', 'Verdana', 'Segoe', sans-serif;
        fontFamily: 'Trebuchet MS', 'Lucida Grande', 'Lucida Sans Unicode', 'Lucida Sans', sans-serif;
        fontFamily: 'Verdana', 'Geneva', sans-serif;
    },
    mono: {
        fontFamily: 'Consolas', 'Monaco', monospace;
        fontFamily: 'Courier New', 'Courier', 'Lucida Sans Typewriter', 'Lucida Typewriter', monospace;
    }
})
```