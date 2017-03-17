## README

I setup this using WebGL. You shouldn't have any CORS issues.

Of note, I include the [Tiny WebGL Helper Library (TWGL)](https://twgljs.org/) which provides syntactic sugar and allows my code to be less verbose than plain webgl. It doesn't add any major features, so I felt safe adding it.

Because this project is so simple, I have all of my code in `project0.html`.
It contains a vertex shader, a fragment shader, and two javascript functions (`render` which renders a frame and triggers the next one, and `start`, which starts the animation).

You should just be able to open `project0.html` in a browser (I tested it in Chrome) to run the project. Or navigate to https://ezraezra101.github.io/animation-projects/project0_spinning_cube/project0.html