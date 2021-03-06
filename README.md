### Objective
Mathnote is an event driven non-linear component-based note-taking web application with a focus on math.

### Libraries to be used
- https://reactjs.org/ Component based state logic for handling UI/UX
- https://d3js.org/ If shapes and drawing are needed
- https://www.mathjax.org/ Displaying math is hard, this library makes it easy
- https://github.com/naptha/tesseract.js#tesseractjs OCR for text (in review)
- https://github.com/falvaro/seshat OCR for math formulas (in review)

### User stories
- The user will be able to hand write out maths and have them converted to text using an Optical Character Recognition (OCR) library
- Use event sourcing for complete edit history and advanced logging
- Mobile/tablet first design
- The user will be able to log in and out
- The user will be able to use a core set of predefined math components such as addition, subtraction, multiplication, and division
- The user will be able to use Mathjax syntax to write formulas, and save these formulas in to "pipeable" components
- The user will be able to non-linearly pipe components to other components to manipulate data output

### User stories - stretch goals
- The user will be able to create, replace, update, and delete components through a Mathnote API
- The user will be able to pipe data, via component(s), via API
- Xoomla plugin for interacting with Mathnote
- A tutorial functionality built in that is similar to Clippy (but actually good)
