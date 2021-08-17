## **Chapter 5 - 'Images'**

Syntax for Images `<img src="https://www.stockvault.net/data/2016/08/23/208216/preview16.jpg" alt="The Aandromeda galaxy" title="..."/>`

CSS allows us to impliment **Height** & **Width** either Inline or in an external Stylesheet.

Where to place your image? 
- Before `<p> </p>` -> Paragraph starts below the image
- inside the `<p><p/>` -> First row of text will start beklow the image
- Middle of `<p></p>` -> the image is placed between the words the image is inserted next to.

3 rules of Images: 
1. Save in the proper format! 
2. Save the image at the desired size -> save the image at the height & width it will appear on the page.
3. Measure images in pixels.

`<figure> </figure> elements can be used as containers for both and image and an `<figcaption></figcaption>` element.

## **Chapter 11 - 'Color'**

Colors are applied Inline or Externally. They bring life to your webpage and can be applied as a text or background color. 
-> When picking colors stick to the rule of contrasta and ensure the text color is clearly visible over the contrasting background color.

## **|Chapter 12 - 'Text'**
Text can be manipulated ina variety of different ways:
- Font-Size:
- Font-weight:
- Style:
- Stretch:
- Font-family:

We can manipulate text scale:
- Pixels: best way to ensure its appear in the size scale you desire.
- Percentages: Default webpage size is 16px; from here you can create percentages based off od whatever text size you desire for default.
- EM's: Change the size of the text based on the size of text relative to the parent element.

@font-face: allows you to use a font not pre-installed on your editor. 
 font-family: 'name of font family'
 src: url(url of the font family you are bringing in)
 (you will also need to provide an href= into the head of your html document.)

 Alignment:
 - left
 - right
 - center
 - justify: everyline in the paragraph, except for the ladt line, should align with the width of the containing box. 
 
 Vertical-align:
 - text-top:
 - text-baseline:
 - text-bottom:

 Text Indent: Indents the text set to a px or % value.

 (pg 290 - 291 cover Links, and hovering over boxes. will be great for about me page.)

 ## **Blog-Post - 'JPEG vs PNG vs GIF'**

 ### JPEG 

 We will use JPEG for all images that contain a natural scene or where color variation is smooth. Great for photography photos. 
- Text does not render very smooth in JPEG do to the sharp contrast in color between the text and background.
- No transparency support.
- 16 million color support

### PNG
We will use PNG for our highest resolution photos and for those images with text where there are sharp edges and high contrast. will not smooth the colors as easily as JPEG.. Use these for images of text with sharp contrast.
Supports transparency
- standard PNG -> 256 color support (16m on a PNG24)

### GIF
We use GIF for animations. Since the creationg of PNG GIFS have been relegated to the use of animations. 
- 256 color support
































(Creative Common license - src= https://www.stockvault.net/data/2016/08/23/208216/preview16.jpg)

