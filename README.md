# Custom selectors

A set of general CSS custom selectors for use with [cssnext](https://github.com/cssnext/cssnext) ([postcss-custom-selectors](https://github.com/postcss/postcss-custom-selectors))

## Install

```sh
$ npm install custom-selectors
```

## Examples, [full list](https://github.com/antontrollback/custom-selectors/blob/master/index.css)

```css
:--universal {
  box-sizing: border-box;
}

.Post :--headings {
  font-weight: 600;
}

.Button:--hover-focus-active {
  color: blue;
}

.Button:active {
  opacity: 0.5;
}

```

```css
*,
*:before,
*:after {
  box-sizing: border-box;
}

.Post h1,
.Post h2,
.Post h3,
.Post h4,
.Post h5,
.Post h6 {
  font-weight: 600;
}

.Button:active,
.Button:focus,
.Button:hover {
  color: blue;
}

.Button:active {
  opacity: 0.5;
}
```
