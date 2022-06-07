# Portfolio

#### By Matt Wilkinson

#### Programming Language Suggester

## Github links
* https://wilkinsonmatt.github.io/Programming_Language_Suggester/
* https://wilkinsonmatt.github.io/Programming_Language_Suggester/
* https://github.com/wilkinsonmatt/Programming_Language_Suggester.git

## Tests

Describe: wordCounter()

  Test: "It should return 1 if a passage has just one word."
  Code:
    const text = "hello";
    wordCounter(text);
  Expected Output: 1

  Test: "It should return 2 if a passage has two words."
  Code:
    const text = "hello there";
    wordCounter(text);
  Expected Output: 2

  Test: "It should return 0 for an empty string."
  Code: wordCounter("");
  Expected Output: 0

  Test: "It should return 0 for a string that is only spaces."
  Code: wordCounter("            ");
  Expected Output: 0

  Test: "It should not count numbers as words."
  Code: wordCounter("hi there 77 19");
  Expected Output: 2


Describe: numberOfOccurrencesInText()

  Test: "It should return 0 occurrences of a word for an empty string."
  Code:
    const text = "";
    const word = "red";
  numberOfOccurrencesInText(word, text);
  Expected Output: 0

## Technologies Used

* CSS
* HTML
* Bootstrap
* JS
* Jquery

## Description

 A Programming Language Suggester webpage that asks future students a series of questions about themselves and provides a language suggestion based on their answers. 
 
 (Unfortunately the results aren't based in science)

## Setup/Installation Requirements

* Download entire github file
* launch index.HTML file in Google Chrome

## Known Bugs

* N/A

## License

Copyright (c) 2022 Matt Wilkinson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR I