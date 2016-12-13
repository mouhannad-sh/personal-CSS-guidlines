# Personal-CSS-guidlines
My personal CSS &amp; SASS guidelines, decided to post them here so I would visit github more often 0_0

1- Always look for a way to avoid ovevrrides, #bootstrap_is_no_excuse

2- In SASS don't be a lazy-ass that '@extend' every time they want to re-use an existing class, add that class name in your HTML

3- If you have "variables.scss" or a file which you '@import' in every other .scss file, DO NOT write any CSS make sure that your code includes only variables and @mixins DO NOT write sass to generate CSS inside of that file because it's going to be dublicated in every file that you '@import' it in.

4- Modulize your CSS and have some utility classes ready before you start the build this practice will keep your CSS file size to minimal which results in better page load speed.

5- DO NOT confuse browsers with your selectors, yah yah! browsers are smart (except for IE which is an abomination) however rendering big ass selectors doesn't help.

6- Keep your CSS organized or the next developer to deal with your code will curse you to death! 

7- Browsers read CSS selectors from right to left consider that when you style a `<ul>` , `<ol>` or `<dl>`

8- DO NOT dublicate IDs, seriously stoooop!!

9- DO us all a favor and write ":first-of-type" instead of ":nth-of-type(1)"...

10- Read about CSS variables (yes CSS variables is now a thing)

11- Writing SASS doesn't mean modulization out of the picture.

12- Use emmet and stop wasting your time.

13- If you aren't planning to change "rem" on your body on different views stick to "px" or "em".

14- Put some comments in your SASS if you're doing something that might confuse the next developer.

15- When you copy someone els's css please READ it before you do so, it will take you more time trying to figure out why is it causing issues after production.

16- If you are the type to include a whole css library and end up using only few lines from that library. Consider a career change.

17- seriously don't @extend when you can add that class to your HTML (everytime you do that an imaginary puppy dies)

.... to be continued 
