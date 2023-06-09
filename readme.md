
<h1 align="center"> FCC-7-Flexbox-PhotoGallery </h1>

## Getting Started:
- css flexbox photo gallery
- We'll use Flexbox to build a responsive photo gallery webpage.
- Flexbox helps us design a webpage so that it looks good on any screen size.

## Tech stack:
   - browser
   - Code Editor (like Visual Studio Code/ notepad)

## Learnt:
- Flexbox is a one-dimensional CSS layout that can control the way items are spaced out and aligned within a container.
- for images to give full width and full image
   -  width:100%; max-width:350px;
-  To keep uniform size for the images
   - height:300px;
-  To Align the text in the center
   -   text-align:center
-  To make the text uppercase use the text-transform property with uppercase as the value.
   -    text-transform:uppercase;
- Add border-bottom when we need a bottom line under any element:
   -   border-bottom:4px solid #fdb347
- Flexbox has a main and cross axis. The main axis is defined by the flex-direction property, which has four possible values:
   -  row (default): horizontal axis with flex items from left to right
   -  row-reverse: horizontal axis with flex items from right to left
   -  column: vertical axis with flex items from top to bottom
   -  column-reverse: vertical axis with flex items from bottom to top
      -  display: flex;
      -  flex-direction: row;
      -  flex-wrap:wrap
- The justify-content property determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them.
   -    justify-content:center
-  The align-items property positions the flex content along the cross axis. In this case, with your flex-direction set to row, your cross axis would be vertical.
- To vertically center the images
   -    align-items: center;
- To create some space around the container and center of it.
   -  padding: 20px 10px;
   -  max-width:1400px;
   -  margin:0 auto;
- All the images have different aspect ratios, To prevent some of the images being distorted, we can use  object-fit property.
   -  object-fit:cover
- To give some space between the images,we can use <strong>gap</strong> CSS shorthand property.
   -  The gap CSS shorthand property sets the gaps, also knowns as gutters, between rows and columns. 
   -  The gap property and its row-gap and column-gap sub-properties provide this functionality for flex, grid, and multi-column layout.
   -  gap:16px
- We can Smooth out the images a bit by using border-radius property.
   -  border-radius:10px
- The ::after pseudo-element creates an element that is the last child of the selected element. You can use it to add an empty element after the last image.
   -  .gallery::after {
   -  content: "";
   -  width:350px;
   -  }
-  The alt image attribute should describe the image content. 
   -  Screen readers announce the alternative text in place of images. 
   -  If the image can't be loaded, this text is presented in place of the image

## application shots
   <img width="300" height="300" alt="application snip" src="https://github.com/Sangi19/FCC-7-Flexbox-PhotoGallery/blob/main/flex-gallery.PNG"> 

## Deploy on Vercel:
- vercel Link - https://fcc-7-flexbox-photo-gallery.vercel.app/

## Built by

👤 **Sangeetha Ramkumar**

- [LinkedIn](https://www.linkedin.com/in/sangeetharamkumar)
- [GitHub](https://github.com/Sangi19)
- [E-mail](sangiammu1020@gmail.com) 