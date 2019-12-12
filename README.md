# color2palette

> sass extension for creating a palette from a single color

## Install

```bash
Clone it 👽
```

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

## License

MIT ©
