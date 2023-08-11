>>>>>>Here's a documentation for the HTML code:

---

## First Project

This HTML document represents a simple webpage layout. It contains various sections like a header, main content, and a footer. The webpage showcases a fictional project with sections for navigation, banner, about us, services, and contact information.

### Document Structure

- **`<!DOCTYPE html>`**: Declares the document type and version of HTML being used.
- **`<html>`**: The root element of the HTML document.
  - **`<head>`**: Contains metadata and includes external resources like stylesheets and the title of the webpage.
    - **`<meta>`**: Provides metadata about the document.
    - **`<title>`**: Sets the title of the webpage that appears in the browser tab.
    - **`<link>`**: Links an external stylesheet (`style.css`) to style the webpage.
  - **`<body>`**: Contains the visible content of the webpage.
    - **`<header>`**: Represents the header section of the webpage.
      - **`<nav>`**: Defines the navigation bar.
        - The navigation bar contains the project name and navigation links.
    - **`<main>`**: Contains the main content of the webpage.
      - **`<section id="banner">`**: Represents the banner section.
        - This section includes a headline, description, and an image.
      - **`<section id="ABOUT">`**: Represents the about us section.
        - Similar structure to the banner section.
      - **`<section class="kj">`**: Represents the services section.
        - This section showcases three cards describing different services.
      - **`<section>`**: Represents the contact information section.
        - This section includes the address, contact details, and navigation links.
    - **`<footer>`**: Represents the footer section.
      - Displays a copyright notice for the year 2023.

### Key Features

- Navigation bar with project name and links.
- Banner section with a headline, description, and image.
- About us section with a headline, description, and image.
- Services section with three cards describing different services.
- Contact information section with address, contact details, and navigation links.
- Footer displaying the copyright notice.

### CSS Styling

The layout is enhanced by an external stylesheet (`style.css`) that defines the appearance of various elements throughout the webpage.

---

This documentation provides an overview of the HTML structure, sections, features, and overall layout of the provided HTML code. Please note that the actual appearance of the webpage will depend on the linked CSS stylesheet and any additional styling applied. phpr-1




>>>>> Here's the documentation for the CSS code:

---

## Cascading Style Sheets (CSS) Documentation

The following CSS code defines styling rules for various elements in an HTML document. These rules are intended to provide consistent and visually appealing design across the webpage. The styles encompass the navigation bar, banner, about us section, services section, contact information section, and footer.

### Global Styles

- **`*` Selector**: Applies styles to all elements.
  - `margin: 0;` and `padding: 0;`: Resets margin and padding to zero for all elements.
  - `font-family: Verdana, Geneva, Tahoma, sans-serif;`: Sets the default font family for the document.

### Navigation Styles

- **`.nav-container` Class**: Styles the navigation container.
  - `display: flex;`: Sets the container as a flex container.
  - `justify-content: space-around;`: Distributes items with equal space around.
  - `align-items: center;`: Vertically aligns items at the center.
  - `background-color: rgb(85, 83, 83);`: Sets the background color.

- **`.navbar` Class**: Styles navigation items.
  - `color: #fff;`: Sets text color to white.

- **`.navbar>li` Selector**: Styles navigation list items.
  - `list-style-type: none;`: Removes list bullet points.
  - `display: inline;`: Displays items in a line.
  - `margin-left: 45px;`: Adds space between items.

- **`.navbar>li:hover` Selector**: Styles navigation list items on hover.
  - `color: rgb(202, 23, 23);`: Changes text color to red on hover.
  - `transition: 0.1s;`: Adds a smooth color transition effect.
  - `cursor: pointer;`: Changes cursor to a pointer on hover.

- **`.n-button` Class**: Styles buttons.
  - `background-color: red;`: Sets the button background color to red.
  - `color: #fff;`: Sets text color to white.
  - `padding: 15px 25px;`: Adds padding to the button.
  - `border: 0;`: Removes button border.
  - `cursor: pointer;`: Changes cursor to a pointer.

### Banner Styles

- **`#banner` Selector**: Styles the banner section.
  - `display: flex;`: Sets the section as a flex container.
  - `justify-content: space-around; align-items: center;`: Centers content horizontally and vertically.
  - `height: 100vh;`: Sets the section height to 100% viewport height.
  - `background-image: linear-gradient(90deg, #e9c2c2, #fff);`: Applies a linear gradient background.

- **`.dec` Class**: Styles the banner description container.
  - `margin: 15px; padding: 35px;`: Adds margins and padding.

### About Us Section Styles

- **`#ABOUT` Selector**: Styles the about us section.
  - `display: flex; flex-direction: row-reverse;`: Reverses the content order.
  - `justify-content: space-around; align-items: center;`: Centers content horizontally and vertically.

### Services Section Styles

- **`.kj` Class**: Styles the services section.
  - `background-image: linear-gradient(90deg, rgb(32, 32, 30), rgb(41, 20, 20));`: Applies a linear gradient background.
  - `color: #fff; padding: 65px; height: 60vh;`: Sets text color, padding, and height.

- **`.ervice` Class**: Styles the services container.
  - `display: flex; justify-content: space-around; align-items: center;`: Centers content horizontally and vertically.

- **`.card` Class**: Styles the service cards.
  - `background-color: #080808;`: Sets background color.
  - `text-align: justify; color: #fff;`: Sets text color and alignment.
  - `height: 300px; width: 220px;`: Sets card dimensions.
  - `margin: 10px; padding: 15px; border: 2px solid #201e1e;`: Adds spacing and border.
  - `box-shadow: 5px 5px 15px rgb(158, 107, 107);`: Adds a shadow effect.

### Footer Styles

- **`footer` Selector**: Styles the footer.
  - `text-align: center; font-size: 15px; padding: 15px; color: #fff;`: Sets alignment, font size, padding, and text color.
  - `background-color: black;`: Sets the background color.

### Contact Info Styles

- **`.contact` Class**: Styles the contact title.
  - `color: #fff; padding: 25px; font-size: 35px; text-align: center; background: #cf2d2d; font-style: oblique;`: Sets text color, padding, font size, alignment, background, and font style.

- **`.contact-cont` Class**: Styles the contact container.
  - `background-image: linear-gradient(

90deg, rgb(158, 105, 105), #da3131);`: Applies a linear gradient background.
  - `display: flex; justify-content: space-around; align-items: center; height: 65vh;`: Centers content horizontally and vertically, and sets height.

- **`.phn` Class**: Styles the contact phone details.
  - `text-align: justify; font-style: italic; font-size: 30px; border-left: 2px solid black; padding: 35px;`: Sets alignment, font style, font size, border, and padding.

- **`.navfat>ul` Selector**: Styles navigation footer links.
  - `list-style-type: none; text-align: justify; font-style: italic; text-decoration: underline; font-size: 25px; border-left: 2px solid black; padding: 35px; cursor: pointer;`: Sets list style, alignment, font style, text decoration, font size, border, padding, and cursor.

- **`address` Selector**: Styles the contact address.
  - `font-size: 25px;`: Sets font size.

---

This documentation provides an overview of the styling rules applied to various elements within the HTML document. The styles contribute to the overall appearance and design of the webpage.
