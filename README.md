# color2palette

> sass extension for creating a palette from a single color

[![NPM](https://img.shields.io/npm/v/color2palette.svg)](https://www.npmjs.com/package/color2palette)

## Install

```bash
npm i color2palette
```
or
Clone it 👽

## Usage

#### HTML

```html
ul
  -for (var x = 1; x < 10; x++)
    li(class='step-'+x)
```

#### Sass
```css
@import '/color2palette'; 
@include color2palette(#dc2142, "step", 9);
```

#### Example
[Live on CodePen!](https://codepen.io/ahmetozantekin/pen/eYmzzrQ)


## License

MIT ©
