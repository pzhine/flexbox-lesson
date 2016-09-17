# Advanced CSS (flexbox)
- make your apps look professional and have good UX
- tags: CSS, React, Flexbox, Responsive

# Objectives
- Apply a stylesheet to your React app
- Use flexbox to layout elements in your app
- Use a glyph font to style buttons and add icons

# Resouces
- [Flexbox introduction](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Material Design forms examples](https://www.muicss.com/docs/v1/css-js/forms)
  This is a library that will style your forms to meet the Google Material Design spec. It’s a good example of giving your forms a consistent look and feel.
- [Flexbox demo tool](https://github.com/pzhine/flexboxdemo)
  Clone this repo and follow the readme to build and run the demo. Experiment with different layouts.
- [Flexbox cheatsheet](http://apps.workflower.fi/css-cheats/?name=flexbox)
- Glyph font libraries
  - [FontAwesome](http://fontawesome.io/icons/)
  - [Zurb](http://zurb.com/playground/foundation-icon-fonts-3)
  - [IonIcons](http://ionicons.com/)

# Warmup/Review Exercise
Write CSS for [this html](warmup.html) so that it looks like this in the browser:  
![mockup](warmup.png)

# Lecture

## Webpack and CSS
Start with a new clone of the [simple react setup](https://github.com/nmadd/simple-react-setup). Then run:
```
npm install
npm install --save-dev css-loader style-loader
```
Add the following line to your App.js file:
```javascript
var css = require("style!css!./App.css");
```
Now clear out App.css and add the following line:
```css
h1 {
  color: red;
}
```
Run `npm start` and your "Hello world" header should be red!
