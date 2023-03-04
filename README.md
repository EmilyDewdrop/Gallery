# Gallery
## My second project as part of my Founders & Coders application

This gallery displays the four other projects I completed as part of my Founders & Coders application. I really enjoyed getting to play with the mix of images and colours and the (relatively) simple layout that comes with the using flexbox. This gallery features:

### Features

- a flexbox with four cards that grow, shrink and wrap as the screen is resized 
- a button that expands and shrinks each box when pressed, and gives more information about each project
- a link to each project on GitHub Pages

### Process

I find flexbox, in general, simple and intuitive. However, the intricacies of the grow and shrink functions took me a while to master. I had a significant amount of trouble with both the fourth box taking up the whole width of the second row when the screen shrunk, and the content growing larger than the boxes. This was fixed by support from others at the Support Circle Meet-up, a lot of trial and error, and discovering the min-content and max-content properties. The boxes now grow and shrink enough that there aren't massive gaps between them, but not too much to look strange and out-of-proportion when resizing.

In terms of JavaScript, my initial plan was to be able to click the button and the image would be replaced with text. However, after much trial and error and a lot of googling, I was unable to find a simple way to do this (it's something I want to keep working on). Instead I opted for having the buttons make text appear, and then boxes growing with the text. I think this looks clear and clean. I tried several different ways to make this function work (indeed, I found so many different possible options for it on various forums) but eventually went with a way that seemed intuitive to me (I really like if... else statements). I am certain there must be a simplier way to do this with a single function instead of one for each button, but instead of aiming for the perfect solution I opted for one that I knew worked and I understood. I would, however, love to come back to and look at other ways to do this once I'm more skilled in JavaScript.

