# CSS Positioning, Display, & Styling Practice Repository

### About This Repository

I created this repository to practice and understand the **position** and **display** properties in CSS. Additionally, I am incorporating **CSS transitions** to manipulate a `div` element using various transformation functions. I have also explored **CSS background properties** to manipulate background images effectively.

### Position Property in CSS

The **position** property in CSS determines how an element is placed within a document. Below are the different values I am working with:

- **Relative**: The element is positioned relative to its normal position. Adjusting `top`, `right`, `bottom`, or `left` will move the element from where it would normally be.
- **Absolute**: The element is removed from the normal document flow and positioned relative to the nearest positioned ancestor (anything other than `static`). If no ancestor is positioned, it is placed relative to the `<html>` element.
- **Fixed**: The element is positioned relative to the browser window. It stays in place even when scrolling.
- **Static**: The default position of all elements. The element follows the normal document flow and does not respond to `top`, `right`, `bottom`, or `left` properties.

### Display Property in CSS

The **display** property determines how an element is rendered on the page. Below are the different values I am practicing with:

- **Inline**: Elements do not start on a new line and only take up as much width as necessary. `width` and `height` properties do not affect inline elements.
- **Block**: Elements start on a new line and take up the full width of their container. `width` and `height` can be applied.
- **Inline-Block**: Similar to `inline`, but allows setting `width` and `height` while keeping elements on the same line.

### CSS Transitions & Transformations

To enhance my practice, I am using **CSS transitions** to manipulate a `div` element with the following transformation functions:

- **Scale**: Adjust the size of an element.
  ```css
  transform: scale(1.5); /* Increases size by 50% */
  ```
- **TranslateX**: Moves an element along the horizontal axis.
  ```css
  transform: translateX(50px); /* Moves element 50px to the right */
  ```
- **Skew**: Tilts an element along the X or Y axis.
  ```css
  transform: skew(
    10deg,
    5deg
  ); /* Skews element by 10 degrees on X-axis and 5 degrees on Y-axis */
  ```
- **Rotate**: Rotates an element around its center.
  ```css
  transform: rotate(45deg); /* Rotates element 45 degrees */
  ```

### CSS Background Manipulation

I am also practicing background-image manipulation using different properties:

- **Contain**: Ensures the background image is fully visible within the element while maintaining its aspect ratio.
  ```css
  background-size: contain;
  ```
- **Cover**: Scales the background image to cover the entire element while maintaining its aspect ratio.
  ```css
  background-size: cover;
  ```
- **Auto**: Keeps the original size of the background image.
  ```css
  background-size: auto;
  ```
- **No-Repeat**: Ensures the background image does not repeat.
  ```css
  background-repeat: no-repeat;
  ```

### Creating a Photo Blog
As an additional challenge, I am using the concepts learned in this repository to create a photo blog. The photo blog will incorporate:
- **Positioning elements** (relative, absolute, fixed, static) for layout structuring.
- **Display properties** to organize content blocks and images.
- **CSS background properties** to style images effectively.
- **CSS transitions and transformations** to add interactivity to images and text.
-
![photoblog](https://github.com/user-attachments/assets/2049ea93-13f1-45ba-8a78-1d9f456e3080)


### Technologies Used
- **HTML** for structure
- **CSS** for styling, positioning, and background manipulation
