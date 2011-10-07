# Ruby Style Guide

Based on [Chris Neukirchen's Ruby Style
Guide](http://github.com/chneukirchen/styleguide/).

## Formatting:

* Use UTF-8

* Use 2 space indent, no tabs.

* Use Unix-style line endings.

* Use spaces around operators, after commas, colons and semicolons,
  around `{` and before `}`.

* No spaces after `(`, `[` and before `]`, `)`.

* Use one space before statement modifiers (postfix
  `if`, `unless`, `while` and `until`).

* Indent `when` as deep as `case`.

* Use an empty line before the return value of a method (unless it
  only has one line), and an empty line between `def`s.

* Use empty lines to break up a long method into logical paragraphs.

* Keep lines fewer than 80 characters.

* Avoid trailing whitespace.


## Syntax:

* Use `def` with parentheses when there are arguments.

* Use `&&` and `||` for boolean expressions.

* Use `{...}` for single-line blocks and `do...end` for multi-line blocks.

* Avoid `return` where not required.

* Avoid line continuation (`\`) where not required.

* Avoid using the return value of `=` in comparisons.

* Use `||=` freely.

## Naming:

* Use `snake_case` for methods.

* Use `CamelCase` for classes and modules. (Keep acronyms like HTTP,
  RFC, XML uppercase.)

* Use `SCREAMING_SNAKE_CASE` for other constants.

* Use `_` or names prefixed with `_` for unused or private variables.

* When defining binary operators, name the argument "other".


## Comments:

* Comments longer than a word are capitalized and use punctuation.

* Avoid superfluous comments.


## The rest:

* Avoid writing methods that span more than 10 lines.

* Avoid writing methods that receive more than 3 parameters.

* Use `def self.method` to define singleton methods.

* Avoid needless metaprogramming.

* Don't use `rescue` as a predicate.

* Don't use catch-all `rescue`.

* Don't use `case` without an `else` branch.

## General:

* Code in a functional way, avoid mutation when it makes sense.

* Do not mutate arguments unless that is the purpose of the method.

* Do not mess around in core classes when writing libraries.

* Do not program [defensively](http://www.erlang.se/doc/programming_rules.shtml#HDR11).

* Keep the code simple.

* Don't overdesign.

* Don't underdesign.

* Avoid bugs.

* Read other style guides and apply the parts that don't dissent with
  this list.

* Be consistent.

* Use common sense.
