# Webpack Starter Template

## Description
This is my personal Webpack starter template configured with essential loaders and plugins. It's set up to help me kickstart my JavaScript projects quickly without having to configure everything from scratch. It includes configurations for processing CSS, images, fonts, and HTML.

## Prerequisites
Make sure you have Node.js installed on your system [Node.js](https://nodejs.org/).

## Installation
To use this template for a new project, follow these steps:

1. Clone the repository:
    ```zsh
    git clone https://github.com/vndlgd/webpack-starter-template.git your-new-project-name
    ```

2. Navigate into your new project directory:
    ```zsh
    cd your-new-project-name
    ```

3. Install the necessary dependencies:
    ```zsh
    npm install
    ```

## Usage

### Development
To start the development server:
    ```
    npm install
    ```
    This command will start the Webpack development server on port 8080. You can view your application at http://localhost:8080. The server provides live reloading for JavaScript, HTML, and CSS changes.

### Building for Production
To build your application for production:
    ```
    npm run build
    ```
    This command will bundle your scripts, styles, and assets into the `dist` directory with content hash in filenames for caching purposes, ready for deployment.

## Customization

### Webpack Configuration
The configuration file is located at `webpack.config.js`. It's set up for development mode with source maps, a development server, and rules for processing CSS, images, and fonts.

### HTMLWebpackPlugin
HTMLWebpackPlugin: This is configured to use `src/index.html` as a template for the generated `index.html` in the `dist` directory.

### CSS
CSS files are processed with `style-loader` and `css-loader`.

### Images and Fonts
The config includes loaders for handling image files (.png, .svg, .jpg, .jpeg, .gif) and font files (.woff, .woff2, .eot, .ttf, .otf), treating them as assets/resources.

Feel free to add or modify loaders and plugins as per your project needs.
