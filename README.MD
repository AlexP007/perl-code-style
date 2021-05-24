# PERL STYLE GUIDE

This is a set of best practices for styling code that I put together during my
big PERL journey. The beginning of this venture was the
[question](https://www.perlmonks.org/?node_id=11132778)
asked on the wisdom search forum on May 20, 2021. I will update this guide
as new knowledge arrives. However, never forget to appreciate conventions within
the team as well as styles in modules when collaborating. This guide could be
basis for such agreements.

## SHORT SUMMARY

* Indent is 4 spaces. No tabs allowed.
* Put a semicolon after every statement, unless it's the last statement in a one-line BLOCK.
* No space before the semicolon.
* No space between function name and its opening parenthesis.
* Space after each comma.
* Do not put spaces after '(' pr '{' and before ')', '}' and other list operators.
Also in function arguments.
* Line up corresponding items vertically.
* Uppercase constant names.
* Lowercase local variables.
* Lowercase function and method names.
* Use underscore _ as a delimiter in naming.
* Package names are an exception to this rule. Modules should begin with a capital
letter and use mixed case, but probably without underscores.
* Use unless instead if not (if !).
* Prefer to use 'and', 'or' instead of '||', '&&' in most cases if priority is
not important to you.
* Prefer to use if .. elsif .. else instead of several BLOCKS of if on the same
logic context.
* Don't cuddle an else.
* Closing curly bracket of a multi-line BLOCK should line up with the keyword
that started the construct.
* Opening braces for BLOCKS go on the same line, and closing braces
go on the next line after the body.
* In multi-line conditions, put end of the line after each operator, except last one.
* Always place use strict and use warnings in the heading.
* It's a good practice to have comments in complex regular expressions.
* Try to limit your code with 74-78 columns lines.
* Use empty line to separate logical pieces of code.
* Never use function prototypes. In most cases (99%) it's pointless and weird.
* Always unpack arguments @_ first.
* Always use return explicitly.
* Use two-part version numbers.
