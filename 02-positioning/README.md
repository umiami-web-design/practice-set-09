# README

## CSS: Positioning

### Instructions

As you go through each step, I recommend checking the code in Firefox. If something is incorrect, you will find the mistake easier to catch if there is less code to review.

1. Open `css/style.css` in Atom and `index.html` in your browser.

2. Create a CSS block which changes every `em` inside the section with an `id` of `relative` as follows: Set the background color to `#ccc`, position `em` as `relative`, move it 20 pixels up and 30 pixels right. (Yes, it is going to look really weird.)

3. Create a CSS block which turns `nav` into a fixed element. Set its width to `100%` and its background color as `rgb(219,81,73)`. Set its positioning as `fixed`. Move it all the way to the top and all the way to the left. (Bonus: As you can see, the `header` is hidden underneath the `nav`. Create a CSS block for `header` and use the correct box model property to adjust the header so it shows up just below the sticky nav.)

4. Create a CSS block for `div` which sets its width at 200 pixels and its height at 200 pixels. Create an `id` selector for **each** div which sets the background color accordingly (i.e. for 'red', use a shade of red). All `div`s are to be contained within `article`.

5. Add a 2 pixel, solid, dark gray border to `article`. Set its minimum height to be 500 pixels.

6. Position the `red` block in the bottom right corner and offset it by 20 pixels from the right. Position the `yellow` div in the top right corner and offset it 20 pixels from the top. Position the `green` div in the top left corner and offset it 20 pixels from the top and 20 pixels from the left. Position the `blue` div in the bottom left corner. There are no offsets for the `blue` div.

7. When the page scrolls, our relatively positioned `em`s hover over our sticky nav. Change the `z-index` property of `nav` so it will always be in front of the content on the page.
