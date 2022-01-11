# Notes, thoughts, ideas, references

- study design for approach and reuseable styles
- set-up basic folder structure
- linked css and js files to html
- enabled Live Server
- enable sass to compile scss to css w/terminal
- set up sass to watch for changes/ terminal
- structured HTML, used `section` and `article` tags of note.
- font was going to fall back and not Inter?
- add BEM class names

## Sass folder structures

https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4

- started following Coder Coder's videos using the Gulp workflow

## Toggle styles

- got really tricky with hover states and using the checkbox with theme switching,
  but, I got it figured out! This was a very helpful resource:

- higlight title on hover of switch
  https://jsfiddle.net/ThinkingStiff/dWHzF/

- Only works on decendant selectors or next siblings NOT previous siblings or parents!

# functional requirements

Light/Dark mode toggle -- takes system preference by default but can override with toggle

- what Html markup(accesible)

use fieldset, legend, radio inputs

- switching between light/dark modes via Js --
- Three option toggle: light/dark/system and
  prefers-color-scheme media query -- https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme
  Css variables (custom properties) -- https://css-tricks.com/updating-a-css-variable-with-javascript/

Accessibility

- use correct heading tags
- screenreader-only text for card titles/username -- https://www.accessibility-developer-guide.com/examples/hiding-elements/
