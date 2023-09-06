# 3D Flip Button

This is a simple HTML and CSS code snippet that creates a stylish 3D flip button. You can use this code to enhance the visual appeal of buttons on your website.

## Getting Started

To use this 3D flip button on your website, follow these simple steps:

1. Copy the HTML code below and paste it into your HTML file:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>3D Flip Button</title>
</head>

<body>

    <span><a href="#"></a></span>

</body>

</html>
```

2. Copy the CSS code below and save it as a `style.css` file in the same directory as your HTML file:

```css
@import url("https://fonts.googleapis.com/css?family=Montserrat:600&display=swap");

body {
    margin: 0;
    padding: 0;
    display: flex;
    height: 100vh;
    align-items: center;
    justify-content: center;
    background: #fff;
}

span {
    position: relative;
    display: inline-flex;
    width: 180px;
    height: 55px;
    margin: 0 15px;
    perspective: 1000px;
}

span a {
    font-size: 19px;
    letter-spacing: 1px;
    transform-style: preserve-3d;
    transform: translateZ(-25px);
    transition: transform 0.25s;
    font-family: "Montserrat", sans-serif;
}

span a:before,
span a:after {
    position: absolute;
    content: "BUTTON";
    height: 55px;
    width: 180px;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 5px solid black;
    box-sizing: border-box;
    border-radius: 5px;
}

span a:before {
    color: #fff;
    background: #000;
    transform: rotateY(0deg) translateZ(25px);
}

span a:after {
    color: #000;
    transform: rotateX(90deg) translateZ(25px);
}

span a:hover {
    transform: translateZ(-25px) rotateX(-90deg);
}
```

3. Save the HTML and CSS files, and then open the HTML file in your web browser to see the 3D flip button in action.

## Customization

You can customize the button's appearance by modifying the CSS styles in the `style.css` file. You can change the button's size, colors, fonts, and more to match your website's design.

Feel free to use and modify this code to create unique and eye-catching buttons for your website or web application. Enjoy!

## Preview
<img width="960" alt="Screenshot 2023-09-06 184307" src="https://github.com/Aarzoo75/3D-Flip-Button/assets/59678435/12a2e917-c51f-46c2-ae89-9fe8d9a4cab7">
