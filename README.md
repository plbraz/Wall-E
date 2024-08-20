# Wall-E Bot - Listen to Music During the End of Humanity on Earth!

## Project Description

This project is a web page designed to promote the "Wall-E Bot," a bot that can be added to Discord to entertain communities. The design is responsive and uses custom fonts and colors to create a user-friendly and visually appealing interface.
Note: the bot is under development

## Project Structure

```plaintext
/
├── css/
│   └── styles.css
├── images/
│   ├── espaco2.gif
│   ├── wall-e.png
│   └── Pedro.jpg
└── index.html

## Project Structure

- `css/styles.css`: Contains all the custom styles for the page.
- `images/`: Directory containing all the images used on the page.
- `index.html`: The main file that structures the web page.

## Explanation of HTML Code

### Header `<head>`
- **Meta Tags**: Sets the character encoding to UTF-8 and defines the viewport to make the site responsive.
- **Title**: Defines the page title that appears in the browser tab.
- **Style Link**: Connects the HTML to the external CSS file (`styles.css`).

### Body `<body>`
- **Header**:
  - Includes a logo image and a navigation menu with three links: "Tutorial," "Open Source," and "Commands."
  
- **Main**:
  - **Main Content**: Contains the bot's title, a subtitle, and a button to add the bot to Discord.
  - **Secondary Content**: Describes what the bot can do using styled paragraphs.
  
- **Footer**:
  - Displays the author’s image, "Pedro Braz," with his name alongside it.

## Explanation of CSS Code

### General Styles
- **Fonts and Colors**: Fonts are imported from Google Fonts, and primary colors are defined using CSS variables for easy future changes.
- **Basic Resets**: Sets margin, padding, box-sizing, and text-decoration to ensure visual consistency across all elements.

### Body Styles
- **Background**: Applies a background GIF (`espaco2.gif`) that covers the entire screen.
- **Layout**: Sets height and width to occupy the full visible area of the browser.

### Component Styles
- **Header (.cabecalho)**:
  - Uses flexbox to arrange content horizontally with uniform spacing.
  
- **Main (Content Principal .conteudo-principal)**:
  - Structured with flexbox, aligning the text and the bot's image side by side.

- **Button (.conteudo-principal-escrito-botao)**:
  - Stylized button with shadows, rounded borders, and a hover effect that changes the background color.

- **Footer (.rodape)**:
  - Contains the author’s image with text aligned to the right.

### Specific Styles
- **Profile Image (.rodape-imagem)**:
  - The image is resized and adjusted for the footer, with automatic margin to align to the right.

- **Author Text (.autor)**:
  - Displays the author's name next to their image, with proper alignment and spacing.

### Media Queries
- **@media only screen and (max-width: 900px)**:
  - **Responsiveness**: Aligns all elements to the center and adjusts the width to 100% of the screen on devices with a width of less than 900px.
