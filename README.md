# Frontend Mentor - QR Code Component Solution

This is a solution to the [QR Code Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents
- [Overview](#overview)
- [Screenshot](#screenshot)
- [Links](#links)
- [My Process](#my-process)
- [Built With](#built-with)
- [What I Learned](#what-i-learned)
- [Continued Development](#continued-development)
- [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The QR Code Component allows you to generate scannable QR codes directly in your application. It is lightweight, customizable, and works seamlessly across desktop and mobile devices.

### Features
- Encode any text, URL, or data into a QR code
- Responsive — adapts to different screen sizes (common mobile width: 375px)
- Lightweight and dependency-friendly
- High readability for most QR scanners

### Use Cases
- Sharing links (websites, app downloads, profiles)
- Payment systems and e-tickets
- WiFi or contact information sharing
- Quick access to app features

## Screenshot
![QR Code Component on Desktop](/image.png)
![QR Code Component on Mobile](/image-1.png)


## Links
- Solution URL: [GitHub Repository](https://github.com/YourUsername/qr-code-component)
- Live Site URL: [Live Site](https://cedric-celestino.github.io/qr-code-project/)


## My Process

### Built With
- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I Learned
Through this project, I learned the importance of a **mobile-first approach** in web design. While I initially coded with mobile dimensions in mind, I found myself prioritizing desktop layouts. This experience helped me understand why starting with mobile ensures a more accessible, responsive, and user-friendly design.

Here is an example of the mobile-specific CSS I used:

```css
@media only screen and (min-width: 200px){
  .card {
      max-width: 18rem;
      min-height: 28rem;
      padding: 5%;
  }

  .qr-image {
      max-width: 18rem;
      width: 100%;
      object-fit: contain;
  }

  .title {
      font-size: 1.1rem;
      margin-inline-start: 1.2em;
      margin-inline-end: 1.2em;
  }

  .description {
      font-size: 0.9rem;
      margin-inline-start: 1.2em;
      margin-inline-end: 1.2em;
  }

  .attribution {
      font-size: 1rem;
      padding: 0 3%;
  }
}
```

### Continued Development

I want to improve my skills in **layout positioning** and **container dimensions**. Choosing the right colors for a project is also something I aim to master as I continue my learning journey.

### Useful Resources

* [freeCodeCamp Fullstack Developer Curriculum](https://www.freecodecamp.org/)

## Author

* Frontend Mentor - [@Cedric](https://www.frontendmentor.io/profile/Cedric-Celestino)

## Acknowledgments

* Frontend Mentor for providing the challenge and assets.


