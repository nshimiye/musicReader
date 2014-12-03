MusicReader
===========

User story:
==========
I am part of choir, but I do not know how to read music, I rely heavily on our director, Sean who teaches almost all the songs. He sometimes, records the Base part of the song and send it to us (Base singers). I have found this recording very helpful, so I thought about automating this recording process which would help even other voice singes ( Soplano, Alto, and Tenor ). 
There are some paid service that do this already but I wanna make something better and that meets all my needs.

Use Cases:
=========
* User can convert between music sheet (pdf) and a known music notaion language (to be set later) Note: both ways.
  - This music notation language is nothing but a container to hold information extracted from the music sheet (pdf)
* User can create playables file (midi, mp3) from information extracted from the music sheet (pdf)
* User can specify which voice type (Soplano, Alto, Tenor, Bass) to create playables file for.


Built for musicians who don't know how to read music notes. They will be able to listen to audio generated from pdf that contains music notes.

Language
========
* Java
* Javascript ( Meteor ), html5

External tools
==============
* PDFBox [https://pdfbox.apache.org/]
