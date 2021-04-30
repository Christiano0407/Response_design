# Response_design Mobile
Build first responsive design Mobile. 

# Responsive Design Mobile and Desktop.

# Proyect Response for course of Platzi Mobile First. 
- Response Design.
- Media Queries.
- SEO.
- UX / UI / AI. 
- Product Design.
- Web Design with Figma.

# Platzi 
[Links](https://platzi.com/home)

# Color
- [Adobe Color](https://color.adobe.com/es/create/color-wheel)
- [coolors](https://coolors.co/)
- [Gradient](https://mycolor.space/gradient3)
- [Webgradient](https://webgradients.com/)

- --bitcoin-orange: #f7931a;
- --soft-orange: #ffe9d5;
- --secondary-blue: #1a9af7;
- --soft-blue: #e7f5ff;
- --warm-black: #282623;
- --black: #201e1c;
- --off-white: #faf8f7;
- --just-white: #fff;
- --grey: #bababa;


# Font
- [Adobe fonts](https://fonts.adobe.com/)
- [Google Fonts](https://fonts.google.com/)

# Tips: 
- Estilos:
- 1-Posicionamiento.
- 2-Modelo de Caja (box-model).
- 3-Tipografía.
- 4-Estilos Visuales.
- 5-Otros.

# Images
- [Unsplash](https://unsplash.com/)
- [Pexels](https://www.pexels.com/)
- [TinyPng](https://tinypng.com/)

# Icons
- [FontAwesome](https://fontawesome.com/icons?d=gallery&p=2)

# CDN JS
- [CDN](https://cdnjs.com/)

# Media Queries
- [MyDevice](https://www.mydevice.io/#compare-devices)
## Min-Width:
- 768px
- 1024px
- 320px

# Tools Design
- [Materials](https://material.io/)


####HTML code
```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
         <link rel="stylesheet" href="../css/mediaQueries.css" media="screen and (min-width: 930px)">
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>

####Media code
:root {
    /*Colores*/
    --bitcoin-orange: #f7931a;
    --soft-orange: #ffe9d5;
    --secondary-blue: #1a9af7;
    --soft-blue: #e7f5ff;
    --warm-black: #282623;
    --black: #201e1c;
    --off-white: #faf8f7;
    --just-white: #fff;
    --grey: #bababa;
}
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
html {
    font-size: 62.5%;
    font-family:"DM Sans", sans-serif;
}
.main-tables-container {
     display: flex; 
    /* flex-wrap: wrap; */
    width: 930px;
    margin: 0 auto;
}
.product-cards--container {
    display: flex;
    flex-wrap: wrap;
    width: 930px;
    margin: 0 auto;
}
.plans-container--slider {
    justify-content: center;
     overflow: hidden;  /* quitar el scroll */
}
