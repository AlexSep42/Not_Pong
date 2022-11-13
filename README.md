# A (legally distinct) version of Pong

I made this just to practice/learn Godot as I'm planning to start using it properly.

It's not a very good adaptation and I could absolutely improve it but it's good enough for what I was intending it to be, and I'm bored of the project.

Stuff that's wonky:
- Ball Physics

My personal biggest issue is the physics of the ball and collisions, currently I am using a very simple bounce function which just mirrors the vector, which ends up creating a pretty bland experience.  Ideally I would want the angle of the bounce to be more severe the further away from the center the ball hits from.
- Randomizing

I'm still not quite sure how to use the randomize function, which creates some funky stuff to happen, e.g.: when the game starts, the ball always goes to the same side as the person who lost the point last round; and the angle at which the ball starts from can be way too obtuse which ends up with the ball bouncing between the walls a ton before it actually reaches one of the player paddles.

Stuff that's good:
- "Art" style/design

I think calling the graphics I made for pong "Art" is a bit optimistic but I'm quite glad with how it turned out anyway.  To make the background, paddles, and balls I used Aseprite and I used the font [Mono](https://github.com/pixeldroid/fonts/tree/main/menu) by PixelDroid (under Open Font License).  The little details I added like having the collision of the paddles be 1 pixel taller and lower than the sprite just to add a tiny space if the player is hitting the walls, or having the small vertical pillars on the side have collision as well as the normal walls were the things I'm most proud of in a weird way.
- Movement

The movement is pretty much the easiest thing I did but I'm still happy with how it feels; it's very snappy and responsive and about what I would expect from Pong movement
- Code
I'm under no assumption that my code is good but I feel like its good enough for my first go at GDScript.  There are still fragments of commented-out bug-fixing code and useless notes but in terms of the actual meat of it I tried to make sure I followed the style guides and implemented my personal best practices to make it both readable and editable in future.

This write-up is more for my own reflection more than anything but if someone is stumbling upon it I hope you've found something in here useful/interesting.

Thanks!
