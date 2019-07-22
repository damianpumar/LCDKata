## Goal: write a program that displays LCD style.

Part 1
------
Write a program that given a number (integer), converts into LCD style numbers using the following format.

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
 
Note: Please do *NOT* read the second part before completing the first. Part of the purpose of this kata is to make you practice refactoring and adapting to changing requirements.

Part 2
------
Now, refactor the program so that it now accepts letters, converts into LCD style letters, using the following format.

<pre>
  __   __   __  ___   __  __  __
 |__| |__| |     | | |__ |__ |__
 |  | |__| |__  _|_| |__ |   |__|
</pre>

(each digit is 3 lines high)

*Given* a word ***HELLO*** <br>
*When* convert to LCD style <br>
*Then* they would see:
<pre>
       __          __
 |__| |__ |   |   |  |
 |  | |__ |__ |__ |__|
</pre>
 
This kata based on:
[https://github.com/coreyhaines/kata-number-to-led](https://github.com/coreyhaines/kata-number-to-led)

Copyright
------
Copyright © 2009 Corey Haines. See [Here](https://github.com/coreyhaines/kata-number-to-led/blob/master/LICENSE)