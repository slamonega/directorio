
# Directory Explorer

An intuitive, accessible, and responsive web-based file explorer designed to offer seamless navigation through directories. Built with **Bootstrap 5** for modern, clean design and **GitHub API** integration for fetching repository contents dynamically.

## Key Features

- **Responsive Design**: Built with Bootstrap 5, optimized for mobile and desktop devices.
- **Dynamic Breadcrumb Navigation**: Easily track and navigate through directories.
- **Interactive File Listings**: Icons and sizes are dynamically generated for each file and directory.
- **Markdown Rendering**: Automatically fetches and renders `README.md` files using `marked.js`.
- **File Size Formatting**: Human-readable file sizes for quick reference.
- **Hover Effects**: Interactive hover effects for an enhanced user experience.
- **Extensible**: Easy to customize for various use cases.

## Philosophical Foundations

This project is grounded in the philosophy of **inclusion** and **accessibility**. The clean, minimal interface is designed to be intuitive for users with varying levels of digital literacy. It embodies the idea that **technology should lower barriers to knowledge**, not raise them. The file explorer metaphor echoes our cognitive approach to organizing and structuring knowledge, providing a seamless bridge between human thought and digital organization.

The **clear typography** and **high-contrast design** prioritize readability, ensuring users of all ages and abilities can interact with the system without barriers. This is more than a tool—it is an instrument of democratizing access to information.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/slamonega/directorio.git
   cd directorio
   ```

2. **Host the Project Locally**:
   You can use any local web server to serve the HTML file, such as Python’s built-in server:
   ```bash
   python3 -m http.server
   ```

3. **Open the File Explorer**:
   Open your browser and go to `http://localhost:8000` to access the file explorer.

## SEO & Viral Features

To maximize **visibility** and **viral potential**, the following SEO practices have been incorporated:

- **Descriptive Meta Tags**: Titles and descriptions that highlight the core functionality and accessibility.
- **Keyword Optimization**: Includes relevant keywords like "responsive file explorer", "GitHub integration", "Bootstrap 5 file navigator", and "directory explorer".
- **Image Alt Tags**: Enhances SEO for image searches.
- **Mobile Optimization**: Fully responsive, ensuring higher ranking on mobile searches.
- **Social Sharing**: Easily integratable with OpenGraph and Twitter cards for optimal social media previews.

## Customization

The project is highly **customizable**:
- **Excluded Files**: You can update the list of excluded files by modifying the `excludedFiles` array.
- **Themes**: Modify the Bootstrap theme or apply custom CSS to adapt the look and feel.
- **GitHub Repository**: Replace the `owner` and `repo` variables in the JavaScript to point to your own GitHub repository for dynamic file fetching.

## Contributing

Feel free to fork, submit issues, or contribute to the project. Pull requests are always welcome.

## License

This project is licensed under the MIT License.
