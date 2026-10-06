# Love Quote Card Template

A simple, premium-looking quote card template built with HTML, CSS, and a little JavaScript.

## How to use

1. Open `index.html` in a browser.
2. Edit the `cardData.lines` array in the script section to change the text.
3. Adjust the color variables in `:root` if you want a different theme.

## Example customization

```js
const cardData = {
  lines: [
    "Your first line here",
    "Your second line <span class='highlight'>with highlight</span>",
    "Your third line"
  ]
};
```

## Color theme

You can change colors here:

```css
:root {
  --bg-1: #0f0c20;
  --bg-2: #171327;
  --pink: #ec4899;
  --pink-soft: #f472b6;
  --purple: #a855f7;
  --white: #f8fafc;
}
```

This template is designed for quick customization and easy deployment.
