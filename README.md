CTF Blader
==========

This is a listing of tools and commands that may help with CTF challenges.

# Table of Contents
1. [Crypto](#crypto)
2. [Miscellaneous](#miscellaneous)


Crypto
======

Caesar Cipher
-------------

Caesar Cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence. And here is a good online decoder for [that](https://www.dcode.fr/caesar-cipher). There is also a tool in linux for caesar cipher called `caesar`.
[More Info](https://en.wikipedia.org/wiki/Caesar_cipher)

![Caesar Cipher](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Caesar_cipher_left_shift_of_3.svg/1280px-Caesar_cipher_left_shift_of_3.svg.png "Caesar Cipher")

Rot13
-----

ROT13 ("rotate by 13 places", sometimes hyphenated ROT-13) is a simple letter substitution cipher that replaces a letter with the 13th letter after it in the alphabet. This is same as doing caesar cipher with 13 as the key. There are multiple variants for this like: `rot47`, `rot5`. 
[More Info](https://en.wikipedia.org/wiki/ROT13)

Rot47
-----

ROT47 is a derivative of ROT13 which, in addition to scrambling the basic letters, treats numbers and common symbols. Instead of using the sequence A–Z as the alphabet, ROT47 uses a larger set of characters from the common character encoding known as ASCII. Specifically, the 7-bit printable characters, excluding space, from decimal 33 '!' through 126 '~', 94 in total, taken in the order of the numerical values of their ASCII codes, are rotated by 47 positions, without special consideration of case. For example, the character A is mapped to p, while a is mapped to 2. The use of a larger alphabet produces a more thorough obfuscation than that of ROT13.
For example: `The Quick Brown Fox Jumps Over The Lazy Dog.` enciphers to:`%96 "F:4< qC@H? u@I yF>AD ~G6C %96 {2KJ s@8]`
Here is a [decoder](https://www.dcode.fr/rot-47-cipher) for Rot47

Maritime Flags
-------------

A maritime flag is a flag designated for use on ships, boats, and other watercraft. But it also comes often in puzzles and CTF challenges. Here is a decoder for [Mary time flags](https://www.dcode.fr/maritime-signals-code).
![Maritime Flags](https://i.stack.imgur.com/N0IZi.png "Maritime Flags")

Birds on wire
-------------

The encryption composed of birds represented as perched on an electric wire is in fact an alphabet of substitution by drawings (of the birds). Each bird represents a letter of the Latin alphabet (26 letters from A to Z) according to the correspondence. Here is a [decoder](https://www.dcode.fr/birds-on-a-wire-cipher).
![Birds on wirde cipher](https://www.geocachingtoolbox.com/pages/codeTables/birdsOnAWire.png "Birds on wire")

Miscellaneous
=============

Esoteric Languages
------------------

Some of the most used esoteric languages are here. For more of them you can visit [here](https://esolangs.org/). And there is an online interpreter called [tio.run](https://tio.run/) which can run most of the esoteric programming languages.

### Brainfuck

Brainfuck is an esoteric programming language created in 1993 by Urban Müller.

Notable for its extreme minimalism, the language consists of only eight simple commands, a data pointer and an instruction pointer. While it is fully Turing complete, it is not intended for practical use, but to challenge and amuse programmers. Brainfuck simply requires one to break commands into microscopic steps.

The language's name is a reference to the slang term brainfuck, which refers to things so complicated or unusual that they exceed the limits of one's understanding.
[More Info](https://en.wikipedia.org/wiki/Brainfuck)
[Interpreter](https://tio.run/#brainfuck)

### Malbolge

 Malbolge is a public domain esoteric programming language invented by Ben Olmstead in 1998, named after the eighth circle of hell in Dante's Inferno, the Malebolge. It was specifically designed to be almost impossible to use, via a counter-intuitive 'crazy operation', base-three arithmetic, and self-altering code.[1] It builds on the difficulty of earlier, challenging esoteric languages (such as Brainfuck and Befunge), but takes this aspect to the extreme, playing on the entangled histories of computer science and encryption. Sometimes, it can be misunderstood as `rot47` or `base85`
 [More Info](https://en.wikipedia.org/wiki/Malbolge)
 [Interpreter](https://malbolge.doleczek.pl/)
