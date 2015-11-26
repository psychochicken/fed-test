# Dev Test Thoughts

## General task priority
Break down the design into it’s base responsive breakpoints, components, and modules and build the site up from there.

1. Project set up / folder structuring
2. Responsive breakpoints
3. Global styles
    1. Headings
    2. Fonts
    3. Paragraph styles
    4. Colours
    5. Buttons
    6. Base Module Styles (padding, any responsive changes)

4. Module structuring - break the design into modular chunks, work out what modules (if any) are being reused and/or extended (i.e. image blocks with captions).
    1. Header / Footer
    2. Featured Slider
    3. Intro blurb
    4. Images with Blurb
    5. Image Blocks
    6. Images with Captions (Image Blocks with Captions)
    7. More Layouts
    8. More Projects

5. Set up any extra JS functionality
    1. Carousel
    2. Modal with Captions

## General Project Notes:
- Mobile first - in this case there was no mobile designs so I made judgement calls and would flag anything that didn’t quite work between breakpoints (like the image caption stuff) for a chat with the designer.
- Project Layout - used a build tool called FastShell just to get the project up and running quickly but the /src folder layout is my own. Normally I’d also have a /modules folder with each module HTML, CSS, and JS existing in it’s own folder.  
- Fonts - obviously there wasn’t any included fonts with the design, so I just set the CSS up for them and I’d normally wait for the files from the designer and drop them into the right folder.

## Potential accessibility issues:
- Heading hierarchy - multiple h1’s on the page, I’d get around it be breaking everything into semantic sections so the heading hierarchy would still make sense.
- Image alt text - lots of images in the design, need to ensure they all have the appropriate alt text
- Color contrast - potential problems with all the various shades of grey in the design, may need to either tweak contrast or provide alternative styling.
- Keyboard accessibility with JS components - making sure that content within the featured-slider and the caption modals is still keyboard accessilble. Normally I’d try and make sure whatever plugin we were using was as accessible as possible before we dove in with it.
