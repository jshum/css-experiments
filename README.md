css-experiments
===============

Experiments to test the limit of CSS

Test1:

* hello.html
* style.css

Test 2:

* home.html
* test.css

Trying to replicate the adjustable width of Test 1 in Test 2. 
Findings:
CSS doesn't mix fixed and flexible widths.
It doesn't calculate what the remaining amount of space is inside a div. It takes it

What we are trying to do is simply not accomplishable using plain-vanilla CSS.
The proof is here: http://www.dynamicdrive.com/style/layouts/category/C10/

There are no fixed, fluid fluid views
Only,
fixed, fluid, fixed
&
fixed, fixed, fluid

But you can use calc() which is supported by some browsers.

http://caniuse.com/#feat=calc
