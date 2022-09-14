Ekaterina Kruk

Contacts
Phone: +7 (981) 780-29-87
Email: nemisekira@gmail.com
GitHub: krukea
Discord: sych(@krukea)

About Me
I've been working as a PHP programmer for the last 7 years but now I want to switch to Frontend development.

Skills
PHP
MySQL
HTML5, CSS3
JavaScript Basics
Git, GitHub
PHP Storm, VS Code

Code example
Create Phone Number from Codewars

Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.

Example
createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]) // => returns "(123) 456-7890"
The returned format must be correct in order to complete this challenge.

Don't forget the space after the closing parentheses!

function createPhoneNumber(numbers){
  if(!numbers) {
    return;
  }
  const numbersString = numbers.join();
  const match = numbersString.replace(/\,/g, '').match(/^(\d{3})(\d{3})(\d{4})$/);
  
  return `(${match[1]}) ${match[2]}-${match[3]}`;
}

Experience
7 years of coding in PHP
Backend and a bit of a Frontend development of an online store
1C and delivery compamies integration, etc.

Education
St. Petersburg Industrial and Economic College - Web programmer
Udemy course - JavaScript - The Complete Guide 2022 (Beginner + Advanced)
https://www.udemy.com/course/javascript-the-complete-guide-2020-beginner-advanced/

Languages
English - Advanced (https://www.efset.org/quick-check/)
Japanese - N5 (Beginner)
Russian - Native
