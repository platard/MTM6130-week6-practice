# CSS background properties

## 1. Set Up the HTML Structure
Create an HTML file and setting up the basic structure with `<html>`, `<head>`, and `<body>` tags. Link an external CSS file to the HTML file using the `<link>` tag.

## 2. Define Global Styles
In the CSS file, start by resetting some default styles using the * selector. Then, define global styles for the `<body>` element, such as setting the font family, line height, and text color.
```
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Body styles */
    - font(Arial)
    - fallback font (sans-serif) 
    - line height(1.5) 
    - color of the font(#333)
```


## 3. Style the Header
Use background properties to style the <header> element. You can set a background color, adjust the padding, and modify the styles for the navigation menu.
```
/* header (0,0,1)*/
    - background color (#067300) 
    - padding: 20px;
  
/* unordered list (0,0,2)*/
    Define the appearance of the marker or bullet points for an unordered list as 'none'
    display: flex;
    justify-content: space-between;
  
  
  /* list items (0,0,3)*/
    display: inline;
  
  /* anchor tags of an unordered list (0,0,4) */
    text-decoration: none;
    color: #ffffff;
    padding: 10px;
```

## 4. Style the Hero Section
Use the background-image, background-size, and background-position properties to set a background image. Adjust the padding and text styles to ensure readability.
```
 /** Hero section (1,0,0) */
    - set the 'Bread' image as the background of the element
    - specify the background covering its entire background container area.
    - position the image at the center of the conatiner.
    aling the text to the center
    padding: 100px 0;
  
  /* main heading (1,0,1) */
    font-size: 36px;
    margin-bottom: 20px;
  
  
  /* hero section paragraphs (1,0,1) */
    size of the font 18 pixels
  
```


## 5. Style the About Section
Set an appropriate background color and adjust the padding for proper spacing.
```
 /* About (1,0,0)
    - background color ( hexadecimal f9f9f9)
    padding: 50px;

```

## 6. Style the Services Section
Choose a background color and adjust the padding to create a visually appealing section.

## 7. Style the Footer
Set a background color, adjust the padding, and modify the text color to create an attractive footer.

## 8. Experiment and Refine
Change the backgroun image and use the white brick wall. Feel free to experiment with background properties, such as background-repeat. Adjust the colors, images, and other properties as desired to refine the overall appearance.