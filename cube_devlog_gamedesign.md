**FELLOW BROTHERS AND SISTERS OF THE CUBE.**
WE HAVE RECENTLY DISCOVERED AN AUDIO LOG RESTING NEAR THE CUBE DIGSITE.
CROWD AROUND THE SACRED TAPE PLAYER, LETS HEAR WHAT THIS IS ABOUT.
JEREMY, SET UP THE TAPE PLAYER PLEASE.

*Tape slotting into device noises*
*Audio crackling*

---

Hey everyone who's reading this!! (the five of you) Its me, Erin, sole programmer of Our Cube.
So, yeah, uhm.. I made game. It was very fun to make the game. I enjoyed it a lot.

I guess I should probably talk more than that for this log.
So, if we rewind, about 9 days before now, to January 9th, you'd see me doing what I always do!

I was bored, in a vaguely creative mood, scrolling websites, like Itch.io. Didn't feel like drawing, and having just come out of a game design course, I wanted to sharpen my skillset just a bit. Y'know.. to make sure I kept what I learned in my head.
At some point you would've seen me start scrolling the Jams page. Which.. isn't too abnormal for me. Since I was 12, I've always wanted to make video games. Being told to join a gamejam and make games if I want to learn how to be a game developer, I always joined the most interesting jams at the time... But never made a game for it.

Here, to emphasize my point. Look at my "jams joined" page. See what I mean?

<img width="1639" height="736" alt="image" src="https://github.com/user-attachments/assets/b9db438a-aeb9-4d77-abe7-a96e736fa672" />

So many jams, and I definitely had the time, but I never even tried for most of them.
Which, of course, set my brain up in a bad habit, expecting very little of myself all the time, every time.
This is one of the contributing factors to my self-doubt, and I bet many others suffer the same crap when they try to do creative projects of their own.

Regardless, I joined the 1-BIT JAM.
Unlike every other game jam I’d done before, this one was already halfway through — I only had 3 days left while most people had 7.
But this time, it was different. In the previous year I’d actually completed a proper game design course. I’d learned real 3D modelling and had still kept my temporary school licenses for Maya and Adobe Substance Painter. I’d been properly taught Unity coding too.
All of that gave me just a bit more confidence, because maybe I could actually use what I’d learned instead of just pretending.
This jam felt like the test. A chance to prove to myself that the skills hadn’t just gone in one ear and out the other. Because honestly, self-doubt had followed me through all of college, that constant scratchy inner voice asking “Do you really know any of this, or are you just on autopilot? Will you forget it all the second the course ends?”
Even during my TAFE courses, my brain kept convincing me I wasn’t really learning anything, just going through the motions. And then there’s my dad. Without meaning to (maybe), he says things that make me feel stupid and incapable. That unless I completely fix myself — exercise every day, take perfect care of everything, basically pull myself up by bootstraps — I’m doomed. Doomed to never leave their house, or get kicked out and end up homeless, starving on the street, surrounded by filth and getting robbed.
(DISCLAIMER: Of course, they never said this explicitly, but they unknowingly imply that it would turn out like this.)

That’s the background noise I carried into those 3 jam days.

Reading the jam rules, it said a few things that would define how the jam would go for me:
- You are allowed to use media that is not subject to copyright. (I leeched every single sound and music track direct from Pixabay after learning this)
- After the submission period is over, you can fix bugs and add new ways to play (web build or any other), but not radically change the game. (Which I originally shrugged off, but would later suffer because of.)
- You must also match the theme that will be announced when the jam starts. (I cannot use more than two colors. At all. Even one grey pixel could screw the game.)

However, the game did explicitly state that I could use post-processing to achieve the 1-bit look I need for the jam. Which is very, very good for me.
I have a habit of needing my own game to capture my interest and awe, if I want to continue working on it after the initial excitement of making a game wears off.

The theme of the jam, which was already out, seeing as the jam had already been running for four days, was "Into the depths."
I immediately thought of mining, and I wasn't alone in that idea, there were several other games about spelunking, caving, whatnot, being made.
I did not immediately think of "digging for a cube deity." At the time, I was pretty sure I'd make some sort of digging game, but I was more worried about other things.

So, after a bit of deliberation, I came up with a plan.
Make the rendering and post-processing first. Later, come up with the actual game.
If I start with the 1-BIT part, then I'll secure both my awe in the shaders, and the criteria for a 1-BIT game will be filled instantly.
So when I opened Unity, I spent two-three hours doing youtube tutorials, googling things and testing things in the editor, until I made this.

https://github.com/user-attachments/assets/cd75bc01-fa66-41c6-b790-06c8c493e20c

At the time, this blew my mind. I watched the cube spin aimlessly for about five whole minutes, and it really helped push my motivation towards the game.
Making the one-bit shader was easy, thanks to Madalaski's video on Return of the Obra Dinn's shaders, and how they could be replicated in Unity. If you want to, you can click the image below to watch the video yourself. It's really in-depth!

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Ap4fXGTOb7I/0.jpg)](https://www.youtube.com/watch?v=Ap4fXGTOb7I)

I mean. I should probably admit, that I stole the Threshold shader from his github, and used that and only that for my whole game's 1-bit aesthetic. I did watch the video in full, but I didn't really follow along."
As you may know, the Threshold shader is not responsible for the dithering, only for the contrast between black and white. It took a bit of modification to turn the Threshold shader into a dither shader as well.

So, after stealing the threshold shader and applying dithering to it, alongside the previous shader, we're left with this in the end:

https://github.com/user-attachments/assets/8919935f-4087-4fdb-8864-a5a52c7aea1b

Now, I could have just rolled with that as how my game looked.. but almost every single game made for this jam is some form of Black + White. My game would blend in, hard to see among the other games using this palette. So, I decided to do something crazy.

My game... is **White and Black.**

Gasp.

This means, specifically, that the sky around is bright, whilst objects and UI elements are dark in appearance. Light is dark too, because if you haven't noticed, the colors are inverted, so the original appearance of everything before shaders looks a lot more like this:

More specifically, my game is Light Mauve and Crater Brown.

https://github.com/user-attachments/assets/66be995f-dcdb-4cd0-bdc2-42865707414b


