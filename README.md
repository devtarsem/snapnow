# Snapnow

Every little web application needs image processing for basic purposes like if we are uploading a png image to the server we have to process it because a user don’t care about what format of dimentions he/she is uploading, o for processing that we have to use long codes and we have to repeat that code on multiple basis with different specifications , as a developer let’s solve this problem so to solve this problem I develop a new NPM package by using this package developed by me, you are able to process the image by just one line of code , the package name is “snapnow” so let’s now see what functionalities does this package offer to you

1.) You are able to resize the image

2.) You are able to grayscale the image

3.) You are able to tint the image with custom colours

4.) You are able to rotate the image

5.) You are able to blur the image with specific strength

6.) You are able to sharpen the image with specific strength

7.) You are able to flip the image across x-axis.

8.) You are able to flop the image across y-axis.

9.) You are able to get metadata of the image across x-axis.
🚀There are functionalities that are added to package in the future or anyone what to contribute is also fine the functionalities are

1.) Compositing the images

2.) Finding patterns in images

🚀 The usage of package is very easy with the attached reference video you can see how to use the code.

🚀Installation

🚀Use à Npm I snapnow

```
const sanpnow = require('snapnow')

const img = sanpnow.processImages(
    `./db.png`
    ,`./dbnew.png`
    ,{scale : true, height : 300, width : 300, fit : "fill"}
    ,{gray : false}
    ,{tint : false, R : 244, G : 206, B : 20}
    ,{rotate : true, angle : 45}
    ,{blur : false, level : 5}
    ,{sharpen : true, level : 50}
    ,{flip : false}
    ,{flop : false}
    ,{text : true})

```

## code explanation

in the above code you all see that we are working in boolean system, all you have to undestand is these boolean statements,
the property that you want to apply on your image you have to make it true with the necessary values.

### Note

1.) for Fit value we have 5 options - fill - contains - cover - inside - outside

2.) the input directory name(`./db.png`) be not be same with output directory (`./dbnew.png`)

That's all just install the package and make the image processing super easy.
