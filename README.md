# Final Project
## Requirements:
The goal of this assignment is to give you a chance to apply all that you have learned to a project of your own choosing.

1. It must involve some serious 3D computer graphics.
2. It must be worth 100 points.
3. It must be do-able in 1 week.
4. It can involve textures, but doesn't have to.
5. It can involve lighting, but doesn't have to.
6. It can involve shaders, but doesn't have to.
7. It can involve shadows, but doesn't have to.
8. It can be based on other work that you have seen, but it must be your own implementation.
9. It must be adequately explained in your write-up.

## Learning Objective:
When you are done with this assignment, you will have had the chance to apply your newly-discovered graphics knowledge to an application that has significance to you. Sometimes, this project is used to launch someone into their research. Sometimes, this project is used to impress recruiters.

## Your Proposal
- Before your project becomes "official", I need to approve a proposal from you. This needs to be a 1-page PDF suvbmitted to Canvas by the date and time listed above. What you propose must be worth 100 points. Compare what you are proposing versus one of the 100-point projects, for example.
- Give me enough detail that I can figure out if it is worth 100 points and if it is doable in a week. I will get back to you by the end of the following week to tell you if your proposal has been accepted.
- On the proposal front page, be sure to put "Final Project Proposal", your name, and your email address.

## AI!
I played with ChatGPT some over the summer. It was much better at writing non-graphics code and 2D graphics code than it was at writing 3D graphics code. (It was pretty good at generating OpenGL code to draw a 2D circle.) But, I expect that you are better at generating prompts than I am. So one of your Final Project options is to use ChatGPT (or other LLM programs like it) to generate and/or animate a 3D scene. It has to be an interesting-enough scene to earn the full points. (A sphere won't cut it.)

I suspect that one can use ChatGPT to generate parts of a simple 3D scene and then surround it with your more-complex supporting code. But I am also expecting that a few people will surprise the hell out of me with what they can do more automatically. If you do this, you need to document what LLM you used, what prompts you used, and what code it generated with them.

## Possible Helps
- If you want to bring in other 3D objects to work with (and there are a lot of them on the Internet), look for something in a .obj format. If you want to load a .obj file, incorporate the file loadobjfile.cpp into your own code. (See the Announcements.) Warning! Not all obj files have normal vectors and texture coordinates. Take a look at the obj file (it is ascii-editable). If you see lines of text beginning with vn, it has normals. If you see lines beginning with vt, it has texture coordinates.
- If you liked the Bézier curves from the Geometric Modeling notes, there is a Bézier surface form as well. It has 16 control points instead of 4 and produces a smooth, slightly-bumpy, surface instead of a smooth, slightly-bumpy, curve. I'd be happy to show this to you if you would find it useful.

## The Turn-In Process:
Use Canvas to turn in:
1. All source code files (.cpp, .vert, .frag)
2. (Do not turn in .obj or .bmp files. If I want them, I'll ask you for them.)
3. Your PDF report containing:

- Do not zip or tar any files together!
- To see how to turn these files in to Canvas, go to our Project Notes noteset, and go the the slide labeled How to Turn In a Project on Canvas.
- Be sure that your video's permissions are set to unlisted.. The best place to set this is on the OSU Media Server.
- A good way to test your video's permissions is to ask a friend to try to open the same video link that you are giving us.
- The video doesn't have to be made with Kaltura. Any similar tool will do.

Your PDF submission is due at the date and time listed above.

Note: This is a hard deadline. Bonus Days cannot be used on this project.

## Your PDF Report
In addition to doing the project, you also need to write a final report about it:
- Turn the PDF of your report into Canvas with your other files
- You report needs to include:
    1. The text from your proposal
    2. What you actually did for your project
    3. How your project differs from what you proposed, and why
    4.(optional) Any impressive cleverness you want us to know about
    5. What you learned from doing this project (i.e., what you know now that you didn't know when you started)
    6. Some images that are especially representative of what you did
    7. A link to the video showing off your project. Be sure your video is set to unlisted.

## Some Comments on Popular Project Ideas
I have noticed some patterns in popular project ideas. Click here to see those comments.

## Grading
Getting the project proposal in on time and in the right format is worth the first 10 points!
