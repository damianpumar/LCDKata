## Goal: write a program that displays LCD style.

### Estimated Duration: 90 min
### Difficulty: Beginner

Note
------
Please do *NOT* read the next part before completing the previoues one. Part of the purpose of this kata is to make you practice refactoring and adapting to changing requirements.

Part 1
------
Write a program that given a number (integer), converts into LCD style numbers using the following format.

<pre>
   _  _     _  _  _  _  _  
 | _| _||_||_ |_   ||_||_|  
 ||_  _|  | _||_|  ||_| _|
</pre>

(each digit is 3 lines high)

*Given* a number ***1*** <br>
*When* convert to LCD style <br>
*Then* they would see:
<pre>
<!---->
 | 
 |
</pre>
Part 2
------
Follow the previous statement, but now the program must allow numbers greater than 9.

<pre>
   _  _     _  _  _  _  _  
 | _| _||_||_ |_   ||_||_|  
 ||_  _|  | _||_|  ||_| _|
</pre>

(each digit is 3 lines high)

*Given* a number ***13*** <br>
*When* convert to LCD style <br>
*Then* they would see:
<pre>
   _
 | _|
 | _|
</pre>
Part 3
------
Now, refactor the program so that it now accepts letters but still method allows integer (overload methods), converts into LCD style letters, using the following format.

<pre>
  __   __   __  ___   __  __  __
 |__| |__| |     | | |__ |__ |__
 |  | |__| |__  _|_| |__ |   |__|
</pre>

(each digit is 3 lines high, but n lines width)

*Given* a word ***HELLO*** <br>
*When* convert to LCD style <br>
*Then* they would see:
<pre>
       __          __
 |__| |__ |   |   |  |
 |  | |__ |__ |__ |__|
</pre>

### Solutions: Java by Damián Pumar
### Tags: TDD-Algorithms-Refactoring
### Useful Links: 

Copyright
------
This kata based on:
[https://github.com/coreyhaines/kata-number-to-led](https://github.com/coreyhaines/kata-number-to-led)

Copyright © 2009 Corey Haines. See [Here](https://github.com/coreyhaines/kata-number-to-led/blob/master/LICENSE)