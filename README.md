---

# Static Netflix Website

## Project Description

This project is a **Netflix Clone** built using **HTML** and **CSS** that replicates the landing page of Netflix India. It includes key features like a header, language selection, main section, trending section, multiple reasons to join, FAQ section, and a footer with various helpful links. The page is designed to resemble the look and feel of the official Netflix homepage, with a dark-themed interface and vibrant red accents.

### Features:
- Multi-language dropdown for regional language options
- Call-to-action buttons for users to sign up or log in
- Footer with important links and contact information
- Frequently Asked Questions (FAQ) section with expandable content
- Flexbox layout for a responsive and fluid design

## Table of Contents

- [Netflix Clone Website](#netflix-clone-website)
  - [Project Description](#project-description)
    - [Features:](#features)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Steps to Install](#steps-to-install)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
    - [Files:](#files)
    - [Images Folder:](#images-folder)
  - [Customization](#customization)
  - [Technologies Used](#technologies-used)
  - [Contributing](#contributing)
  - [License](#license)

## Installation

To get started with this project, follow the steps below:

### Prerequisites

- A web browser (Chrome, Firefox, etc.)
- A code editor (e.g., Visual Studio Code)
- A local server to test the webpage (e.g., Live Server extension for VS Code)

### Steps to Install

1. **Clone this repository** to your local machine or download the project files.

    ```bash
    git clone https://github.com/MMALLIKARJUN2312/Static_Netflix_Website.git
    ```

2. **Navigate to the project folder**:

    ```bash
    cd Static_Netflix_Website
    ```

3. **Open the project folder in your code editor** (e.g., VS Code):

    ```bash
    code .
    ```

4. **Open the HTML file in your browser**:
    - Double-click `index.html` or open it in a browser like Chrome, Firefox, etc.
    - If you're using VS Code, you can use the Live Server extension to view the webpage in real-time.

## Usage

1. **Main Page**: The main page features a Netflix-inspired UI with a hero section that includes a description and call-to-action to start watching.
2. **Trending Section**: Displays movie posters with images of trending content.
3. **Reasons to Join**: Four different cards showing why users should join Netflix, including features like "Watch Everywhere", "Download to Watch Offline", "Enjoy on Your TV", and "Create Profiles for Kids".
4. **FAQ Section**: Clickable questions that expand to show answers.
5. **Footer**: Contains contact information, links to FAQs, privacy policy, legal notices, and more.

## Project Structure

```
/Static_Netflix_Website
├── /images
│   ├── Netflix_Favicon.png
│   ├── Enjoy_on_your_tv.jpg
│   ├── Download_To_Watch_Offline.jpg
│   ├── Watch_Everywhere.jpg
│   └── Kids.png
├── index.html
└── index.css
```

### Files:
- **index.html**: Contains the HTML structure of the page.
- **index.css**: Styles the HTML content with modern CSS techniques, including Flexbox and background gradients.

### Images Folder:
- Contains images used throughout the site such as the Netflix logo and icons for the "More Reasons to Join" section.

## Customization

You can customize the Netflix clone by modifying various sections of the project. Here's how you can change some key aspects:

- **Change Background Image**: To change the background image, you can modify the `background-image` URL in the `.netflix-website` class in the `index.css` file.

    ```css
    background-image: linear-gradient(65deg, #000000, transparent) ,url('your-image-url.jpg');
    ```

- **Update Content**: To update the movie images or headings in the "Trending Now" section, replace the `src` attribute in the `<img>` tags under the `.movies-container` div in `index.html`.

    ```html
    <img src="new-movie-image-url.jpg" alt="New Movie">
    ```

- **Language Options**: To add more languages, simply update the `<option>` tags within the `select` element inside `index.html`.

    ```html
    <option value="eng">English</option>
    <option value="hin">Hindi</option>
    <option value="tel">Telugu</option>
    <option value="newLang">New Language</option>
    ```

- **More Reasons Section**: Add new cards in the "More Reasons to Join" section by copying one of the `<div class="card">` blocks and modifying the content accordingly.

    ```html
    <div class="card">
        <h1 class="card-heading">New Reason to Join</h1>
        <p class="card-description">Description of the new reason to join.</p>
        <img src="new-icon.jpg" alt="new icon" class="icon" />
    </div>
    ```

## Technologies Used

- **HTML5**: Markup language for structuring the content.
- **CSS3**: Styles for the layout, typography, and animations.
    - Flexbox: For responsive layouts and alignment.
    - Background Gradient: For creating a smooth dark theme with a background image.

## Contributing

We welcome contributions to enhance this project! If you'd like to improve the code or add new features, follow the steps below:

1. Fork the repository.
2. Clone your forked repository.
3. Create a new branch (`git checkout -b feature-name`).
4. Make your changes and commit them (`git commit -am 'Add new feature'`).
5. Push the changes to your forked repository (`git push origin feature-name`).
6. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
