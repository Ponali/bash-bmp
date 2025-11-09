**Quick heads up**: This code contains all the changes made by [Dave Eddy's video](https://youtu.be/lU5s11MR5n0) showcasing this project, which only works on bash version 5.3 and up. As of writing this (november), Debian only ships with bash 5.2. To check your bash version, pull up a terminal and type `echo $BASH_VERSION`.

If you cannot install bash 5.3 on your system, run `git checkout d6f757f609fe5a004ac3c97ab9226bd1fbc648f7` after cloning the repo. This will go back to a previous commit that doesn't have any of the changes from Dave Eddy's video.

bash-bmp
========

Generate Bitmap data in pure bash.

Watch how it was made on [YouTube](https://www.youtube.com/watch?v=XjAIhULJsjc).

Usage
-----

Simple BMP (2x2 pixels)

    ./simple-bmp > out.bmp

![simple-bmp](https://files.daveeddy.com/ysap/bmp/simple.png)

Color Gradient

    ./gradient -h 200 -v 200 -o out.bmp

![gradient](https://files.daveeddy.com/ysap/bmp/gradient.png)

Sprite to BMP (smile)

    cat smile.txt | ./sprite-to-bmp -p palette.txt -o out.bmp

![smile](https://files.daveeddy.com/ysap/bmp/smile.png)

Triangle drawer

    ./triangle-drawer -w 64 -h 64 -o out.bmp

3D World

    ./3d-world -w 64 -h 64 -o out.bmp

License
-------

- MIT License

YouTube
-------

<a href="https://www.youtube.com/watch?v=XjAIhULJsjc"><img alt="Bash BMP YouTube
Thumbnail" src="https://files.daveeddy.com/ysap/bmp/bash-bmp-thumbnail.jpg"
/></a>
