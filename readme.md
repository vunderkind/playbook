# Series Eight Loader Assessment

## Task: creating an image slider for Playbook
### Considerations
I initially planned to write this in React to demonstrate my mastery of React, but I quickly realized it wouldn't show very much, especially since I'm not managing state (apart from, of course, the images in the slider. I suppose in production-ready code, where one might be fetching the videos from an API, this would be ideal - but I don't imagine that would happen, especially this is a marketing page. I expect that this page remains quite static.)

No need for hooks, dynamic routing, all the Dom manipulations React is ideal for. So I kept it very simple. 

Written in barebones HTML/CSS. Ditto the slider, in basic JavaScript. No libraries and/or plugins were used for this task. I initially scaffolded an earlier version of the slider in jQuery, but it masked my understanding of JavaScript too much to make it illuminating. 

## What's not yet done?
The mobile navbar. It's pretty straightforward, but I'd like to make a fancy sliding sidebar for the mobile view. I got stuck on the design thinking for this, and I suspect I'd have moved faster if there was already one designed in the Sketch file. 

## Optimizations
Converted the smaller assets to SVG and the larger ones to WebP. My process for deciding what was WebP versus what was SVG is largely arbitrary, but I generally optimized for the smallest possible size on Lighthouse pagespeed insights. 

Speaking of optimizations, one thing that bothered me was how pixelated the logo was rendering, especially on Retina displays. I suppose I could have asked for higher-res SVGs, but I didn't catch that until much later in my process. 

## Refactor
If I had more time to work on this, here are a few things I'd do better:

1. Write cleaner CSS, probably using BEM paradigms or TailWindCSS' components. 

2. Spend a lot more time thinking about the interactions I want to see on the slider. As it happened, I sorta kept fiddling with the slider until it looked somewhat good. Better planning would have done this some justice. 

3. Optimize this code for all screens. Because of the way I wrote the `position: absolute` properties of the slider, it's liable to break on certain screens. This would not fly in real-world use. 

