# Reverse Polish Notation Calculator

This is a command line application that implements a reverse polish notation (RPN) calculator. 
RPN, also known as postfix notation, is is a mathematical notation in which operators follow their operands.

Ex. '3+3' is written as '3 3 +'

If there are multiple operations, operators are given immediately after their second operands.

Ex. The expression written '3 − 4 + 5' is written as '3 4 − 5 +' 

4 is first subtracted from 3, then 5 is added to it. 

**The following table is a visual breakdown of the algorithm:**

![algorithm](https://github.com/sarahsakordaniels/rpn_calculator/blob/media/algorithm2.png)


**The following illustration is a visual breakdown of RPN as polish sausage:**

![sausage](https://github.com/sarahsakordaniels/rpn_calculator/blob/media/sausage.png)

## Setup & Usage

Fork and clone the repository to your local machine.

To use the calculator, run `$ ruby/bin.rb`. 

![demo](https://github.com/sarahsakordaniels/rpn_calculator/blob/media/demo.gif)

## Future Implementations & Improvements

Currently, the application does not contain any tests. Future implementations include testing to ensure proper functionality and output of the application.
