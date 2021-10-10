# The Surreal Aquarium v1.3
------------------------
## Overview
USING PIXI JS
This is a simple application featuring a stage, various sprites, and animations, compiled to form an aesthetic surreal aquarium scene...

Sprites include...
- a fish tank background
- a betta fish
- a small fish
- a large fish
- school of fish
- a minnow fish
- coral
- kelp
- bubble

The balloon sprites are animated along both sine and cosine waves in order to create movement in the scene.

The remaining sprites have been updated using async functions and promises.

The minnow fish acts as a player sprite in which a function allows it to move to wherever the user clicks on the screen.

The fish to the left idley cycles through random colors as it bobs.

The fish to the right bobs until clicked in which a food pellet is created and it swims up and eats it, then returning to its base state.

The betta fish, when clicked, blows a bubble which rises to the surface and then pops.

The addition of a CSS file and its styling further creates the effect of a visual aquarium as the app window spans the width of the screen; in addition a custom name plate is included beneath the app window. 

## Author Testimony
This experience, being my first time using PIXIJS, was overall very smooth. Following the tutorial was enough to give me the basic toolset to inspire a full scene. I was able to achieve the resulting scene with what was taught in the tutorial. There were no problems during this process, just general troubleshooting and finetuning individual elements, until I was satisfied with the end product. In addition, I was able to work around certain things, such as a translation movement by adjusting the values of the sine wave, thus giving the appearance of a horizontal movement; to mimic the feel of depth, I adjusted the tints of the image elements; to further update these effects, the previous animations were replaced with the Animation.to functions. This allows better control over individual sprites, their positions, calling functions, and the ability to chain animations to form paths.

While the scene is good as is, to make it feel more interactive, the added functionality discussed above this testimony was added. As an added touch, aquarium audio is looped in the background. 

As far as a strategy goes, my main plan was to use as few lines of code as needed for each specific function, keeping things simple, but also reusable. 

## Sources
### Audio
[Aquarium Noises](https://freesound.org/s/167748/)
### Images
[Favicon by Freepik.com](https://www.flaticon.com/free-icon/fish_1691086?term=fish&page=1&position=8&page=1&position=8&related_id=1691086&origin=tag)

[Betta](https://www.clipartkey.com/view/oJoibm_transparent-beta-fish-png-blue-betta-fish-sticker/)

[Small Fish](https://pngtree.com/freepng/fish-for-display_5640267.html)

[Big Fish](https://pngtree.com/freepng/fish_5614059.html)

[School of Fish](https://www.pngitem.com/middle/oJhxT_fish-image-school-of-fish-transparent-background-hd/)

[Minnow Fish](https://www.cleanpng.com/png-fathead-minnow-bluntnose-minnow-freshwater-fish-fi-3564166/download-png.html)

[Background Image](https://unsplash.com/photos/ADcXaqQ9vOM?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)

[Kelp](https://www.cleanpng.com/png-kelp-seaweed-algae-deep-sea-tangles-algae-vector-3171675/download-png.html)

[Coral](https://www.pngfind.com/download/hiiJxh_coral-png-picture-portable-network-graphics-transparent-png/)

[Bubble](https://pngtree.com/freepng/element-float-round-blue-bubble_3917386.html)

#### Note: some links connect to images where user is only permitted two downloads a day, in the case a link returns a screen where the image itself does not show, use alternate link provided below
[Bubble Alt Link](https://pngtree.com/so/element)
### Resources
[Dower Chin - Pixi.js Tutorials](https://www.youtube.com/watch?v=_HjQTzpbRK4&list=PLGsA9l-S7trVmUJ7HJsNSKIj0qoAO_qO8)

[PixiJS](https://pixijs.com)
