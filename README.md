<div align="center">
  <img src="img/logo.png" alt="Logo" width="200" height="200">
  <h1 align="center">Blurry Page Preloader</h1>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#javascript-functionality">JavaScript Functionality</a></li>
    <li><a href="#styling">Styling</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## About

This project is a blurry page preloader implemented using HTML5, CSS3, and JavaScript. It creates a visually appealing loading effect with a blurred background image and a percentage indicator.

### Built With
* [![HTML5][HTML5]][HTML5-url]
* [![CSS3][CSS3]][CSS3-url]
* [![JS][JS]][JS-url]

## Usage

To use the blurry page preloader in your project, follow these steps:

1. Include the required HTML markup in your web page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="css/styles.css">
    <title>Blurry Page Preloader</title>
</head>
<body>
    <section class="bg"></section>
    <div class="loading-text">0%</div>
    <script src="js/main.js"></script>
</body>
</html>
```

2. Link the CSS stylesheets by adding the following line within the <head> section of your HTML file:

```html
<link rel="stylesheet" href="css/styles.css">
```

3. Include the JavaScript code by adding the following line before the closing </body> tag of your HTML file:

```html
<script src="js/main.js"></script>
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## JavaScript Functionality

The JavaScript code in main.js provides the functionality for the blurry page preloader. It gradually increases the loading percentage and updates the text and blur effect accordingly. The blurring() function is responsible for this animation. It uses the scale() function to map the loading percentage to appropriate opacity and blur values.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Conclusion
The progress steps widget is a simple and intuitive way to guide users through a series of steps. By using HTML5, CSS3, and JavaScript, this project provides an easy-to-implement solution for incorporating progress tracking into your web pages. Feel free to modify and expand upon this project to suit your specific needs.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contact

Alireza Mohafezatkar - https://www.linkedin.com/in/alireza-mohafezatkar/ - alireza.mohafezatkar@gmail.com

Project Link: [https://github.com/mohafezatkar/blurry-page-preloader](https://github.com/mohafezatkar/blurry-page-preloader)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=html&colorB=555
[linkedin-url]: https://www.linkedin.com/in/alireza-mohafezatkar/
[product-screenshot]: images/screenshot.png
[HTML5]: https://img.shields.io/badge/html5-8F3C18?style=for-the-badge&logo=html5&logoColor=orange
[HTML5-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[CSS3]: https://img.shields.io/badge/css3-2B88CB?style=for-the-badge&logo=css3&logoColor=blue
[CSS3-url]: https://css-tricks.com/
[JS]: https://img.shields.io/badge/javascript-000000?style=for-the-badge&logo=javascript&logoColor=yellow
[JS-url]: https://www.javascript.com/

