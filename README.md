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


License
-------

- MIT License

YouTube
-------

<a href="https://www.youtube.com/watch?v=XjAIhULJsjc"><img alt="Bash BMP YouTube
Thumbnail" src="https://files.daveeddy.com/ysap/bmp/bash-bmp-thumbnail.jpg"
/></a>
