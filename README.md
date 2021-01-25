# Parsity Coding Challenge

Below are 6 coding problems, each worth several points. In total, 20 points are available and you must get 14 in order to "pass". But not to worry! If you do not pass the first time, you will be able to attempt the challenge again.

Please read each prompt carefully and follow the directions. When you're finished you'll submit you work through a form and your work will then be immediately and automatically graded. If you submit your work incorrectly, it could lead to misleading, failing results.

It is recommended that you use the [`submission-template.js`](submission-template.js) file as a starting point.


## Problem 1 - Worth 4 Points
Write a function called `findSum` that takes an array of numbers as an argument and finds the sum of that array of numbers and returns the sum as a number.
For example:

```js
findSum([2, 4, 6]);  // 12
```

## Problem 2 - Worth 4 Points
Write a function called `findFrequency` to find the MOST frequent item, and the LEAST frequent item in any given array of strings. It should return an object that looks like this: `{ most: 'a', least: 'd'}`. Note, you can assume that `findFrequency` will always be called with an array of strings passed in as an argument.
For example:

```js
findFrequency(['a', 'b', 'c', 'a', 'b', 'c', 'a', 'a', 'd']); // { most: 'a', least: 'd' }
```

## Problem 3 - Worth 4 Points
Write a function called `isPalindrome` that takes an argument as a string and returns `true` if that string is a palindrome and `false` if that string is not a palindrome. You can assume that all strings will be single words with no spaces.
For example:

```js
isPalindrome('canal'); // false
isPalindrome('Ana'); // true
```

## Problem 4 - Worth 3 Points
Write a function called `largestPair` that takes an array of integers and finds the pair of adjacent elements that has the largest product and return that product.
For example:

```js
largestPair([5, 1, 2, 3, 1, 4]); // 6
largestPair([9, 5, 10, 2, 24, -1, -48]) // 50
```

## Problem 5 - Worth 3 Points
Write a function called `removeParenth` that takes one argument (a string) which has parentheses (1 open and 1 close) and returns that same string, but without the parentheses and the text inside the parentheses. You can assume that the string is one word with no spaces and only 1 set of parentheses.
For example:

```js
removeParenth('ido(not)liketocode'); // 'idoliketocode'
```

## Problem 6 - Worth 2 Points
Write a function called `scoreScrabble` which takes a string as an argument (a single word) and returns the word's scrabble score as a number. For reference, the following letters are the worth the following points:

* 1 - a, e, i, o, u, l, n, r, s, t
* 2 - d, g
* 3 - b, c, m, p
* 4 - f, h, v, w, y
* 5 - k
* 8 - j, x
* 10 - q, z

Examples:

```js
scoreScrabble('hello'); // 8
scoreScrabble('quiet'); // 14
```
