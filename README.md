Angular Sticky
==============

A simple, pure javascript (No jQuery required!) AngularJS directive to make elements stick when scrolling down.

# Features

  * Allows use of an offset so elements can be sticked to ej. 50px from the top of the browser
  * Recalculates element position on page load and on window resize
  * Clean: No classes are added, no jQuery is required, no CSS files or configuration is needed.

# Usage

Include the .js file in your page then enable usage of the directive by including the "sticky" module
as a dependency. Use the directive as follows:

    <div sticky> Hey there! </div>

To make the element stick within a certain offset of the top of the screen, you can provide an offset as follows:

    <div sticky offset="100"> I won't touch the top of your screen! </div>

Cheers.