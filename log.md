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

**Today's Progress**: Great help from the A-Frame people today. Trying to sort out the relationships between Javascript and the DOM when working with A-Frame, @donmccurdy pointed me to this example in A-Frame extras:

[Platforms](https://github.com/donmccurdy/aframe-extras/blob/master/examples/platforms/index.html)

Much better understanding of how querySelector works in this situation. Built my wall of bricks, even though it's not pretty yet. Now that I'm digging deeper into A-Frame extras, I see one of my next issues solved:

[Force Push](https://github.com/donmccurdy/aframe-extras/blob/master/examples/force-push/index.html)

### Day 3: July 25, 2017

**Today's Progress**: Added random colors to blocks, created nested loops to build wall. Unfortunately, my bricks all come crashing down, which is actually really funny to watch. Need to figure out who to have physics on my blocks, but also keep them as a stable wall.

Had an idea this morning to create a point-and-click escape adventure game. This old-school game format is really popular, and it would be perfect for VR.

[Updated project is here](http://jsbin.com/tagulom/1/edit?output)

### Day 4: July 26, 2017

**Today's Progress**:

I feel like I need to pick up the pace. Stabilized my wall a bit, but it still comes tumbling down after a a little while. This [Mozilla post](https://hacks.mozilla.org/2017/05/having-fun-with-physics-and-a-frame/) might give me an idea as to why. Next up, I want to start launch objects at the wall, and figure out a scoring mechanism. I know it's not a full-fledged game, but it is headed in the right direction. Looking at gameplay vids of the old arcade game [Battlezone](https://www.youtube.com/watch?v=Ctr54kopo8I&t=55s), that's the kind of thing I'd like to make. Simple models, either against AI or against another player.

[Updated project is here](http://jsbin.com/tagulom/edit?output)

### Day 5: July 27, 2017

[Interaction and controllers in A-Frame](https://aframe.io/docs/0.6.0/introduction/interactions-and-controllers.html)

Added mouse pointer controls, still need to use that to push objects.

### Day 6: July 28, 2017

**Today's Progress**:

Still hacking on physics and cursor controller! Seems like when I add animations to dynamic-bodies I lose collisions. Found lots of different ways to handle this stuff, but haven't managed to make it work in my project. As a sideline, I will probably start making some models in MagicaVoxel. Instead of a straight-up version of Battlezone, I think a cool voxel version in vivid colors would be cool. Lots of giant weird geometric shapes.

