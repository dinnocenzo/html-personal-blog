# Blog-html

A personal blog built with plain HTML and CSS, featuring article posts with images, a styled header, and a footer with navigation links.

## Tech Stack

- HTML5
- CSS3
- Google Fonts (Montserrat, Silkscreen)

## Project Structure

```
Blog-html/
├── blog.html       # Main blog page with article posts
├── style.css       # Stylesheet for layout and visual design
├── img/
│   ├── certificado.jpg   # Image for software engineering certificate post
│   ├── pato.jpg          # Image for "Pato Espia" post
│   └── volar.jpg         # Image for levitation post
├── .gitignore
├── LICENSE
└── README.md
```

## Setup / Installation

No build tools or dependencies are required. This is a static HTML project.

1. Clone the repository:
   ```bash
   git clone https://github.com/dinnocenzo/Blog-html.git
   ```
2. Open `blog.html` in any modern web browser:
   - Double-click the file in your file explorer, or
   - Drag and drop it into a browser window, or
   - Use a local development server (e.g., VS Code Live Server extension).

## Usage

Simply open `blog.html` in a browser to view the blog. The page displays three article posts, each with a title, description, and image. The footer includes a link to jump back to the top of the page and a contact email link.

To add a new post, duplicate an `<article class="post">` block inside the `.container` section in `blog.html` and update the content and image source accordingly.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
