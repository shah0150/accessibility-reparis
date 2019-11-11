# Notes About Dinosaur Web Page Accessibility

## Visual Design Notes

- Not enough contrast with the grey text on the white background
- No indication on the main nav links showing which is the current page/link
- The text on top of the image would be hard to read on some screens for some people. Need to create a visual break between the image and the text so it can be read easier.
- A call to action (button) should have more of a contrast with the background green.
- Small text on an icon can be hard to read.
- The form in the footer has no explanation of its purpose.
- No submit button for the form in the footer.

## HTML Notes

- The google font is bringing in three variants but none of them are being used in the CSS. This is a waste of bandwidth which will slow down the performance.
- Should have title attributes for the links.
- The footer form element needs the required action attribute
- The `<nav>` element should be used for the top and footer nav menus
- No ul and li elements are needed now thanks to flex box. Simplify the HTML to improve performance
- `<footer>` element should be used
- The `<dl>` should not have any `<div>` elements as children.
- A `<main>` element should be used instead of the div
- `<section>` elements can be used instead of divs
- A `<header>` element should be used at the top
- No aria-roles specified for any of the divs.
- Image alt attributes are missing or empty.

## CSS Notes

- No fallback fonts in the html font-stack
- The hero-banner image could be changed into a background image in the CSS and then you could simplify the CSS for the hero-banner area greatly. Flexbox can be used to place the content inside the area.
