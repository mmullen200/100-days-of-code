# 100 Days Of Code - Log

### Day 0: July 22, 2017

**Today's Progress**: Set up a basic A-frame scene and added physics system and animation. I also fooled around with the color scheme. I spent a lot of my time reviewing docs for A-frame and Three.js.

**Thoughts:** My goal is to build a simple breakout game in VR.

The user should see a couple of primitives, like a cube and a sphere.

The user should also see a wall of multicolored blocks.

The user should be able to grab one of the nearby objects with the mouse.

When the user releases the block, it should launch in an arc at the wall.

When the launched object collides with the wall, the wall should break.

I could also turn this into a multiplayer artillery game, or create a simple AI for the player to play against.

**Link to work:** [A-frame breakout project](http://jsbin.com/wifoyi/edit?output)

### Day 1: July 23, 2017

**Today's Progress**: My plan today was to set up the loop logic to build a wall of bricks, but this brings up a problem I THOUGHT I sort of understood. It's very simple to create an A-Frame scene directly in HTML, but when I want to start writing JavaScript and folding that in to my A-Frame scene, I'm getting stuck. I never really had a deep understanding of how to use querySelector. I also need to get a grasp on creating components. When I was working on straight Three.js, I was doing everything in a JavaScript file, then dropping it in to the HTML page. This is different. So most of my progress today is in figuring out what I thought I knew but don't really know.

I'll work on this stuff again tonight if I have more time.

**Things to Focus On**
appendChild
QuerySelector
Creating components

[One example using querySelector](https://github.com/processprocess/lazerGlazer_Viz/blob/master/app.js)

### Day 2: July 24, 2017

**Today's Progress**: Great help from the A-Frame people today. Trying to sort out the relationships between Javascript and the DOM when working with A-Frame, @ngokevin pointed me to this example in A-Frame extras:

[Platforms](https://github.com/donmccurdy/aframe-extras/blob/master/examples/platforms/index.html)

Much better understanding of how querySelector works in this situation. Built my wall of bricks, even though it's not pretty yet. Now that I'm digging deeper into A-Frame extras, I see one of my next issues solved:

[Force Push](https://github.com/donmccurdy/aframe-extras/blob/master/examples/force-push/index.html)




