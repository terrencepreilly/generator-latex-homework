# Latex Homework Generator

This [Yeoman](http://yeoman.io/) generator creates the skeleton for a
homework assignment done in LaTeX.

## Installation

First, you must have Yeoman installed.

```bash
yarn global add yo
```

Then `cd` to wherever you are storing your homework
and add this generator:

```bash
yarn add generator-latex-homework
```

## Usage

To start a new homework assignment:

```bash
yo latex-homework
```

If you use no arguments, as above, then Yeoman will prompt
you for the necessary information.  Otherwise, you can
pass it through the command line:

```bash
yo latex-homework <homework-number> <questions> <name>
```

Where `<homework-number>` and `<questions>` are positive integers,
the first representing which homework assignment, and the second
representing the number of questions.  `<name>` is a string:
the author name which will appear on the paper.

## Contributing

If you would like embetter this -- and there is much embetterment to be had -- then submit a pull request at the [github repo](https://github.com/terrencepreilly/generator-latex-homework).
