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

  Test: "It should return 1 occurrence of a word when the word and the text are the same."
  Code:
    const text = "red";
    const word = "red";
    numberOfOccurrencesInText(word, text);
  Expected Output: 1

  Test: "It should return 0 occurrences of a word when the word and the text are different."
  Code:
    const text = "red";
    const word = "blue";
    numberOfOccurrencesInText(word, text);
  Expected Output: 0

  Test: "It should return the number of occurrences of a word."
  Code:
    const text = "red blue red red red green";
    const word = "red";
    numberOfOccurrencesInText(word, text);
  Expected Output: 4

  Test: "It should return a word match regardless of case."
  Code:
    const text = "red RED Red green Green GREEN";
    const word = "Red";
    numberOfOccurrencesInText(word, text);
  Expected Output: 3

  Test: "It should return a word match regardless of punctuation."
  Code:
    const text = "Red! Red. I like red, green, and yellow.";
    const word = "Red";
    numberOfOccurrencesInText(word, text);
  Expected Output: 3

  Test: "If an empty string is passed in as a word, it should return 0."
  Code:
    const word = "";
    const text = "red RED Red!";
    wordCounter(word, text);
  Expected Output: 0

<!-- Describe: removeOffensiveWords()

  Test: "Should return no words if offensive words are submit."
  Code:
    const text = "zoinks, muppeteer, biffaroni, and loopdaloop.";
    const word = "zoinks, muppeteer, biffaroni, and loopdaloop.";
    removeOffensiveWords(word, text);
  Expected Output: 0

  Test: "It should return a value not including the offensive words submit."
  Code:
    const text = "red, green, zoinks, muppeteer, biffaroni, and loopdaloop.";
    const word = "zoinks, muppeteer, biffaroni, and loopdaloop.";
    removeOffensiveWords(word, text);
  Expected Output: 2 -->

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