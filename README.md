# Sailing Fortuitous Apps
Some simple apps provided as part of sailingfortuitous.com


## Introduction
There are currently two apps in this repo:
* ~~Jib Overlap Calculator: Uses sail and boat measurements to calculate the size of a foresail~~
  * NOTE: This calculator has been removed from sailingfortuitous.com
  * The new calculator is made in WordPress, available at https://sailingfortuitous.com/jib-calc/
  * The only remaining relevant file relating to the calculator is `JibOverlapCalc.html`, which contains the stripped-down code (jQuery and lots of HTML removed) to do the math and display the bare minimum info. The contents of that file are inserted into a block in the WP page to power the calculator, along with other blocks that add the chrome.
* ~~Son of a Flag: Uses `canvas` to convert text to signal flags~~
  * NOTE: This flag speller has been removed from sailingfortuitous.com
  * New new flag speller is made in WordPress, available at https://sailingfortuitous.com/spell-things-with-flags/
  * The only remaining relevant files relating to the flag speller are `flag-standalone.html`, which contains the stripped-down code (jQuery, Bootstrap, and lots of HTML removed), and the folders of the flag images. The contents of the HTML file is inserted into a block in the WP page to power the flag speller, along with other blocks that add the flavor.

## Built With
* [bootstrap](https://github.com/twbs/bootstrap) - HTML, CSS, and JavaScript framework
* Math
* Love

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
