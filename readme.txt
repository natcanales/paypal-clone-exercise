In order to use the same font as PayPal, you will have to add
the following lines on the top of your CSS file:


    @font-face {
        font-family: 'pp-sans-big-light';
        src: url('./fonts/PayPalSansBig-Light.woff2') format('woff2');
    }

    @font-face {
        font-family: 'pp-sans-small-regular';
        src: url('./fonts/PayPalSansSmall-Regular.woff2') format('woff2');
    }


Then, whenever you want to set the font-family to the PayPal ones,
you will have to do it like in this example:


    h1 {
        font-family: pp-sans-big-light, Helvetica Neue, Arial, sans-serif;
    }