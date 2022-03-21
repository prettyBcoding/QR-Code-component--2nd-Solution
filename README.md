# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![My solution preview](https://raw.githubusercontent.com/prettyBcoding/QR-Code-component--2nd-Solution/main/screenshot.png)


### Links

- Solution URL: https://github.com/prettyBcoding/QR-Code-component--2nd-Solution/blob/main/screenshot.png?raw=true
- Live Site URL: https://prettybcoding.github.io/QR-Code-component/

## My process

### Built with

- HTML5 & CSS3

### What I learned

The most difficult thing that I learned was CSS Flexbox. I didn't know how to use, and after read an article on  W3Schools, MDN and CSS tricks about it, I still had difficulties to use it and still with the comments on last solution of this challenge. But after some searches, I did it.I also didn't how to use the border-radius and box-shadow property. Because before this project I didn't know about their existence 😅, and when I see the design preview of the challenges I knew that I would have to use these properties even without know the name. And I used them in the main element:

```html
<body>
    <main>
      <img src="images/image-qr-code.png" alt="">
      <h1>Improve your front-end skills by building projects</h1>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </main>
 </body>
```

```css
body {
  background-color: #d6e2f0;
  font-family: 'Outfit', sans-serif;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  height: 100vh; <!-- <<<My mind blow up without this property because without it the content stay align on the top of the screen (based on width). And with it, takes 100% of the screen's height making the in the center of the screen. -->
}

main {
  background-color: #fff;
  border-radius: 1rem;
  box-shadow: 0 0 2px  rgba(0, 0, 0, 0.24);
  max-width: 19rem;
}
```

### Continued development

I'm doing a Full Stack Web Development course and I just finish the Frontend part, now comes de backend part, but I'll still be continuing taking challenges from the Frontend Mentor to improve my Frontend skills.

### Useful resources

- [Google fonts](https://fonts.google.com/specimen/Outfit) - This helped me to get the font of the challenge reason.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs) - This is an amazing web docs which helped me with the challenge's CSS part, for example, to round the corners of the div and image's outer border edge, and helped me with box-shadow too. I recommend it. It is useful if you know what you want but don't how use it in the code like css properties and whatever.
- [HTML Color Codes](https://developer.mozilla.org/en-US/docs/Web/CSS/) - I used it to convert the HSL color to Hex because the atom was warning about to use HSL.
- [CSS-Tricks](https://css-tricks.com/) - I found here a good artcile about CSS Flexbox.

## Author

Benolísio Baptista
* Instagram - [@benolisio](https://www.instagram.com/benolisio)

## Acknowledgments

Thanks to people who comments in my last solution (on Frontend Mentor) giving me some hints to make it better.
