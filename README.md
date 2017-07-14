# Roman Numerals Site

#### This site will translate numbers into Roman Numerals, 07.13.2017

#### By Haneen Abu-Khater and Esti Shay

## Description

This website will prompt the user for input of a number. It will then analyze the user's input and compute the roman numeral number. The website will then display the resulting number in Roman Numerals.

## Specs

* The program matches the 1
  * Input: 1
  * Output: I
* The program matches the 5
  * Input: 5
  * Output: V
* The program matches the 10
  * Input: 10
  * Output: X
* The program matches the 50
  * Input: 50
  * Output: L
* The program matches the 100
  * Input: 100
  * Output: C
* The program matches the 500
  * Input: 500
  * Output: D
* The program matches the 1000
  * Input: 1,000
  * Output: M
* If a 4 appears in the 1s column:
  * Input: 4
  * Output: IV
* If a 4 appears in the 10s column:
  * Input: 40
  * Output: XL
* If a 4 appears in the 100s column:
  * Input: 400
  * Output: CD
* If a 9 appears in the 1s column:
  * Input: 9
  * Output: IX
* If a 9 appears in the 10s column:
  * Input: 90
  * Output: XC
* If a 9 appears in the 100s column:
  * Input: 900
  * Output: CM
* The program finds the largest roman numeral divisor and returns the roman numeral the number of times the given number can be divided by it for numbers with 0 remainder.
  * Input: 2000
  * Output: MM
* The program finds the next smallest roman numeral divisor of the number and appends the roman numeral.
  * Input: 55
  * Output: LV
* The program finds the lowest number to append by, depending on the remainder repeat the process.
  * Input: 57
  * Output: LVII

## Technologies Used

HTML, CSS, Bootstrap, JS, jQuery

### License

MIT

Copyright (c) 2017 Haneen Abu-Khater and Esti Shay
