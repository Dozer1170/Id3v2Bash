This little script is based on the work from: https://phoxis.org/2011/08/24/bash-script-reading-id3v1-tags/

I added rudimentary id3v2 parsing directly from bash. It will be pretty slow compared to an implementation in almost any other context. I had to write the binary file as hex via xxd and parse it as a string character by character.

Simply pass it a list of files: ./Id3TagReader.bash myfile1.mp3 myfile2.mp3

