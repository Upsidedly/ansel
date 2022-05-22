# Comments in Ansel

Making comments in Ansel are quite simple.

For one-line comments, simply use `--` followed by the comment. See an example in the following snippet.

```ansel
str = 'Hello World' -- wow this is a string
```

The text following -- is a comment and will be ignored by the compiler.

For multi-line comments, simply start your comment with `--/` and end it with `/--`. See an example in the following snippet.

```ansel
imt below = 'haiku'
--/
comments seem quite swell
such a rich aspect of code
ansel does it well
/--
```