
# Assignment - CSS 2

***

## Configuration steps

<details>

* Create a new repository based on repository from CSS 1
* Nothing much changes here from

</details>

## Assignment goal

<details>

The goal of this assignment is to make your site more responsive, using media queries and other techniques, as well as to add a few elements to your application.

</details>

## Formal requirements

<details>

Your application should contain the following breakpoints, with adjustments listed below:

***IMPORTANT*** Measurements such as font height or weight, paddings, margins should be adjusted for **each breakpoint**. I leave these adjustments to your liking, as each project differs from others.

Listed below are only ***CHANGES*** - if something is not mentioned for a particular breakpoint, it should remain as-is (excluding properties mentioned by important notice above)

* 320px-768px
  * precisely 1 card per row
    * cards should now be horizontal
      * image should be on the left side
      * content and button remain in vertical orientation, as previously
  * Header navigation link list should be vertical instead of horizontal
  * Footer link lists should now be oriented vertically, one below the other
  * ***OPTIONAL*** Nav menu should become a hamburger menu - you can use some JS for this
  * ***OPTIONAL*** Should contain a floating button in bottom-right corner of the screen that shows the left panel mentioned in further steps, but on the right-hand side instead
* 769px-1200px
  * precisely 3 cards per row
  * Should contain a floating panel on the left-hand side of the screen, containing 4-5 buttons
* \> 1200px
  * precisely 3 cards per row
    * cards should now be horizontal
      * image should be on the right side
      * content and button remain in vertical orientation, as previously
    * cards, along with text, should accommodate very wide screens
  * Should contain a floating panel on the left-hand side of the screen, containing 4-5 buttons
* ***OPTIONAL*** If you feel comfortable with it, refactor your CSS to SASS
* ***OPTIONAL*** Make it so that when user enters print mode for your app, only the card list gets printed

</details>

# Assignment - CSS 1

***


## Configuration steps

<details>

* Fork this repository
* Clone your forked copy
* Run `yarn install` or similar to get this project's packages
* Configure your IDE to run Prettier with settings provided
    * Note: make sure Prettier runs for CSS and HTML, this might be disabled by default in Webstorm

</details>

## Please remember

<details>

* Use consistent commit messages `https://www.conventionalcommits.org/en/v1.0.0/`
* (Probably) the best source for technical information regarding this task: `https://developer.mozilla.org/en-US/`
* If you're hopelessly stuck for more than 20 or so minutes, don't hesitate to contact me
* HTML matters in this assignment, too. Try to use an appropriate tag for its function - f.e. `<header>` for a header and `<ul>` or `<ol>` for lists 
* Use your best stylistic judgment when it comes to creating elements described in formal requirements. Descriptions there are on the vague side on purpose - don't be afraid to make it pretty
* Anywhere in this project where a link is present - it does not have to lead anywhere, just be there for presentational purpose
* For any long-form text elements, use lorem ipsum
* Interactive elements should have hover and other applicable modifiers also styled
* Anywhere an image is mentioned, you can use a solid color or a gradient
* Styles should not be in a `<style>` tag, but in their own file

</details>

## Assignment goal

<details>

The goal of this assignment is to create a simple page using CSS and HTML that contains a header, a footer, and some content, using flexbox and BEM.

</details>

## Formal requirements

<details>

The page should contain the following elements:
* Header
  * Navigation bar
    * Should contain 3-5 links
  * Title image
    * HTML element with text styled to be in the middle of this image - your site name
* Main content
  * ***OPTIONAL TASK: use grid instead of flex for this part***
  * 11 cards, evenly distributed maximum 3 per row. Cards should consist of:
    * Card header image
    * Card title
    * Card content - a paragraph of text
    * "Details" button (should not do anything at this time)
* Footer
  * Two columns, 2-4 links each, oriented vertically

</details>

