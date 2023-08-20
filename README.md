# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


### Screenshot

![](./images/Captura%20de%20tela%202023-06-30%20212446.png)

### Links

- Solution URL: [https://github.com/ThyagoHolanda/qr-code](https://github.com/ThyagoHolanda/qr-code)
- Live Site URL: [https://thyagoholanda.github.io/qr-code/](https://thyagoholanda.github.io/qr-code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was my first time using Flexbox e Media queries.

Below are some of the codes I want to highlight:

```css
    main.container {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 95vw;
      min-width: 375px;
      height: 85vh;
      background-color: hsl(218, 38%, 66%);
      box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.200);
      margin: auto;
      padding: 10px;
    }

    @media only screen and (max-width:415px) {
      main.container {
        width: 100%;
        height: 100%;
      }
    }
```

### Continued development

I will continue studying Flexbox Media queries. Some indications of content and feedback that I had regarding this solution, and that I will include in my list of studies, was using more relative units and learning about mobile first.

### Useful resources

- [Developer Mozilla](https://developer.mozilla.org/pt-BR/) - I use it a lot to clear doubts or remember concepts.
- [W3schools](https://www.w3schools.com) - I also highly recommend W3Schools.

## Author

- Website - [Thyago Holanda Monteiro de Lima](https://thyagoholanda.github.io)
- Frontend Mentor - [ThyagoHolanda](https://www.frontendmentor.io/profile/ThyagoHolanda)
- Linkedin - [Thyago Holanda Monteiro de Lima](https://www.linkedin.com/in/thyago-holanda-monteiro-de-lima/)