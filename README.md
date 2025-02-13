# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```
## Lab Answers

#### Color
- Test: I tested the contrast ratio on webaim.org.
- Results: The color contrast ratio was a 4.08:1 and failed multiple tests for
normal and large text sizes.
- Solution: The background color was changed from #008000 to #e8eee1 and passes
all tests.

#### Semantic HTML
1. Because the titles are wrapped in font elements instead of using headings so keyboard users and screen readers dont have a consistent way to move between major sections
of the webpage. We also rely on the browser default for visualization of tabbing through the page.
2. I updated the article by adding headings, separate paragraphs, figure elements, and descriptive headings and labels.
3. The div class should be replaced with the nav element because it will mark a set of links.

#### The images
- When I updated the article in the semantic HTML section I added descriptions of the pictures below them for accessability reasons.

#### The Audio Player
1. I added a transcription of the audio message for deaf or people with impaired hearing.
2. Adding fall back content to allow the user to download the audio on their device if their browswer doesnt support HTML5 audio.

#### The Forms
1. I added a label for class "visually-hidden" and updated the CSS code to ensure the label is off but still accessible to screen readers.
2. I added the label element for the "Your name" and "Your comment" and now it matches the style of text from the rest of the webpage.

#### The Show/Hide Comment Control
- I updated it to a button class that now allows the tab key to navigate to the button and use the enter/return key to use the button.

#### The Table
- For this part I used the th element on the first row and columns to describe what each are. I also added a caption to the table
so screen readers knew what the table was for. 

#### Other Considerations
- Using the lang attribute to determine the language can allow screen readers get the correct pronunciation and reading rules.