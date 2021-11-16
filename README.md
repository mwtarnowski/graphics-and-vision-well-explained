# Graphics & Vision well explained

This is a curated list of excellent learning resources and explanations in the field of computer graphics and vision, possibly in the spirit of [Explorable Explanations](http://worrydream.com/ExplorableExplanations/), but not necessarily - all great materials will find their place here. Only high quality content and real gems :gem:!

Why this combination? As complementary disciplines, computer graphics and computer vision are profoundly related. While computer graphics considers the forward problem of image creation by interpreting the scene description to generate a rendering, computer vision considers the inverse problem - starting from an image we try to understand its content and create a model of the scene. There is also a growing tendency to combine both disciplines, e.g. in augmented reality. I believe that better understanding one of them benefits from a deeper look at the other.

There is a whole bunch of great materials in general computer science and mathematics and it is not the intention of this document to list them all. All of the courses, articles and other resources here are more or less related to computer graphic, computer vision, image processing, etc. If you know a website that should be listed here, please submit a pull request to improve this document. Thank you!

## Courses

- [Computer Vision ML-4360](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/computer-vision/) - A phenomenal Computer Vision course by Prof. Andreas Geiger with slides, lecture notes, problems and solutions. There's also a [YouTube playlist](https://www.youtube.com/playlist?list=PL05umP7R6ij35L2MHGzis8AEHz7mg381_). This course provides an introduction to computer vision with a strong emphasis on 3D vision, covering topics such image formation, geometry reconstruction, scene understanding, graphical models, neural representations.
- [Cyrill Stachniss YT channel](https://www.youtube.com/c/CyrillStachniss) - Videos related to Computer Vision and Photogrammetry topics, presented in the form of both five-minute overview videos ([5 Minutes with Cyrill](https://www.youtube.com/playlist?list=PLgnQpQtFTOGSO8HC48K9sPuNliY1qxzV9)) and full lectures that provide an in-depth understanding of the concept of 3d vision. 
- [Computer Graphics CMU 15-462/662](http://15462.courses.cs.cmu.edu/) - Introductory Computer Graphics class by Prof. Keenan Crane at Carnegie Mellon University with lecture slides, exercises and programming assignments. Course videos available on [YouTube playlist](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E). It focuses on fundamental concepts and techniques, and their cross-cutting relationship to multiple problem domains in graphics (rendering, animation, geometry, imaging).
- [Rendering Course](https://users.cg.tuwien.ac.at/zsolnai/gfx/rendering-course/) - A course on photorealistic rendering, ray tracing and global illumination by Karoly Zsolnai-Fehér at the TU Wien with lecture slides and assignments. Course videos available on [YouTube playlist](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi).
- [Physically Based Rendering: From Theory To Implementation](https://pbr-book.org/) - A book on the mathematical theory behind a modern photorealistic rendering system and its practical implementation. It utilizes literate programming method which combines human-readable documentation and source code into a single reference that is specifically designed to aid comprehension.
- [Discrete Differential Geometry](http://geometry.cs.cmu.edu/ddg) - Discrete Differential Geometry course by Prof. Keenan Crane at Carnegie Mellon University with lecture notes, problems and programming assignments. Course videos available on [YouTube playlist](https://www.youtube.com/playlist?list=PL9_jI1bdZmz0hIrNCMQW1YmZysAiIYSSS). This course focuses on three-dimensional geometry processing, while simultaneously providing a first course in traditional differential geometry.

## Articles

- [Immersive linear algebra](http://immersivemath.com/ila/index.html) - The world's first linear algebra book with intuitive examples that practically show how the math works using fully interactive figures.
- [The Magnificent 2d Matrix](https://ncase.me/matrix/) - A simple yet useful toy to get an intuition about the transformation matrix.
- [Visually Explained: MVP Transformations](https://xnqor.csb.app/) - An interactive sandbox demystifying basic matrix transformations.
- [Visualizing Projections](https://shaunlebron.github.io/visualizing-projections/) - An interactive demonstration of intuitive projections.
- [Visualizing quaternions](https://eater.net/quaternions) - An explorable video series on quaternions giving the context on how and why they are used in computer graphics to describe orientation in 3d.
- [Let's remove Quaternions from every 3D Engine](https://marctenbosch.com/quaternions/) - An interactive introduction to rotors. Allows to feel a subtle touch of the elegant language of 3d geometric algebra.
- [Cameras and Lenses](https://ciechanow.ski/cameras-and-lenses/) - A tour through cameras, lenses and image formation.
- [The Perspective Camera](https://ksimek.github.io/2012/08/13/introduction/) - An comprehensive guide to how the pixels in a 2d image relate to the 3d world exploring the pinhole perspective camera model with interactive demos, runnable code, and practical advice on implementation.
- [Robotic Systems](https://motion.cs.illinois.edu/RoboticSystems/) - A draft of the Robotic Systems book. Although it does not refer exactly to graphics or vision, Section II deserves attention.
- [Color: From Hexcodes to Eyeballs](http://jamie-wong.com/post/color/) - An excellent article on colors touching the topics of electromagnetic radiation, optical biology, colorimetry, and display hardware.
- [Color Spaces](https://ciechanow.ski/color-spaces/) - Bartosz Ciechanowski's article dedicated to RGB values from RGB color spaces.
- [Alpha Compositing](https://ciechanow.ski/alpha-compositing/) - An article explaining the intricacies of opacity and alpha compositing.
- [Lights and Shadows](https://ciechanow.ski/lights-and-shadows/) - Visually delightful explorations of the presence of light as well as its absence.
- [2d Visibility](https://www.redblobgames.com/articles/visibility/)
- [SIGHT & LIGHT](https://ncase.me/sight-and-light/)
- [Line drawing on a grid](https://www.redblobgames.com/grids/line-drawing.html)
- [Curves and Surfaces](https://ciechanow.ski/curves-and-surfaces) - An interactive introdution to parametric curves and surfaces.
- [Bezier Curves from the Ground Up](http://jamie-wong.com/post/bezier-curves/) - An intro to Bezier Curves full of very nice animations.
- [A Primer on Bézier Curves](https://pomax.github.io/bezierinfo/) - An extremely detailed resource on both the maths and programming aspects of Bezier Curves, covering a wide range of topics relating to drawing and working with Bezier Curves.
- [Interactive explanation of marching cubes and dual contouring](https://wordsandbuttons.online/interactive_explanation_of_marching_cubes_and_dual_contouring.html)
- [Metaballs and Marching Squares](http://jamie-wong.com/2014/08/19/metaballs-and-marching-squares/)
- [CNN Explainer](https://poloclub.github.io/cnn-explainer/) - Learn Convolutional Neural Network in your browser! An interactive visualization tool designed to learn and examine convolutional neural networks.
- [The Book of Shaders](https://thebookofshaders.com/) - A step-by-step guide through the universe of fragment shaders. From the basics of GLSL to various applications, with interactive examples to play with in every chapter.
- [Shader School](https://github.com/stackgl/shader-school) - An introduction to GLSL shaders and graphics programming that runs in your web browser.
