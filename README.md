# Card

This project provides a simple, aesthetically pleasing card component using HTML and CSS. It's designed to be easily integrated into web pages to display information in a structured and visually appealing way.

## Features and Functionality

*   **Card Layout:** A container with a defined width, height, border-radius, and shadow.
*   **Image Display:** Displays an image at the top of the card, configurable via the `src` attribute of the `<img>` tag.
*   **Capsules/Tags:** Displays a set of capsules (tags) related to the card's content.
*   **Content Section:** Displays a heading and a short description.
*   **Read More Button:** A clickable button that can be linked to more detailed information.
*   **Responsive Design:** The card is designed to be responsive and adapt to different screen sizes.

## Technology Stack

*   **HTML:** For structuring the card component.
*   **CSS:** For styling the card component, including:
    *   Background color
    *   Font styling (using Google Fonts - Poppins)
    *   Border-radius
    *   Box-shadow
    *   Flexbox for capsule arrangement
*   **Google Fonts:**  Poppins font is used for the text.

## Prerequisites

A web browser to view the HTML file. No other dependencies are required.

## Installation Instructions

1.  **Download:** Download the `Card.html` file from the repository.  You can clone the repository using git:
    ```bash
    git clone https://github.com/suryavanshamikgpian/Card.git
    ```
2.  **Image:**  Ensure you have an image named `Dal.png` in the same directory as `Card.html`, or replace the `src` attribute of the `<img>` tag with the correct path to your desired image.

## Usage Guide

1.  **Open in Browser:** Open the `Card.html` file in your web browser.
2.  **Customization:**
    *   **Image:**  Change the image displayed by modifying the `src` attribute of the `<img>` tag within the `Card.html` file:

        ```html
        <img src="Dal.png" alt="Image">  <!-- Change "Dal.png" to your image file -->
        ```

    *   **Capsules/Tags:**  Modify the capsules (tags) by changing the text content within the `<div class="capsule">` elements:

        ```html
        <div class="capsules">
            <div class="capsule">Nature</div>
            <div class="capsule">Lake</div>
        </div>
        ```

        You can add or remove capsules as needed.
    *   **Heading:**  Modify the heading text within the `<h2>` tag:

        ```html
        <h2 style="margin: 5px;">Heading</h2> <!-- Change "Heading" to your desired heading -->
        ```

    *   **Description:** Modify the description text within the `<p>` tag:

        ```html
        <p style="opacity: 0.35;">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p> <!-- Change the text here -->
        ```

    *   **"Read More" Button:**  Modify the button text or add a link by modifying the `<button>` tag:

        ```html
        <button class="button">Read More</button>
        ```

        To add a link, you can wrap the button in an `<a>` tag:

        ```html
        <a href="your_link_here.html"><button class="button">Read More</button></a>
        ```

    *   **Styling:** Modify the CSS within the `<style>` tag to customize the appearance of the card. This includes colors, fonts, sizes, and spacing.
3. **Integration:** To integrate this card into an existing website, copy the HTML code within the `<body>` tag of `Card.html` and paste it into the desired location in your website's HTML.  Also, copy the CSS code within the `<style>` tag of `Card.html` and paste it into your website's CSS file or within the `<style>` tag in your website's `<head>`. Make sure the `Dal.png` or the image specified in `img src` is in correct relation with the path for it to be displayed.

## API Documentation

This project does not have an API. It is a front-end component.

## Contributing Guidelines

Contributions are welcome! To contribute to this project:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive commit messages.
4.  Push your changes to your forked repository.
5.  Submit a pull request.

## License Information

No license has been specified for this project. All rights are reserved by the author.

## Contact/Support Information

For questions or support, please contact suryavanshamikgpian through GitHub.