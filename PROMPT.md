Initial:

```
i want to write a script or small program in rust, c, or python that takes
newline-delimited input on stdin, evaluates each line as a C expression, and
prints theresult to stdout. variables informally defined on earlier lines like
"x = 0x1234" should remain in scope during the evaluation of all subsequent
lines. type of variables sholud be inferred according to standard practices.
default output format should be hex(0xABCD), with a -b flag to output in binary
instead. either output formatted should beleft-padded with zeros to be the same
length as the longest value of any variable in theexpression being evaluated.
```

Update to include expressions in output:

```
keep everything the same, just print the expression itself on the line first,
then a colon followed by whitespace, and the the value of the expression (same
as it is already being printed). pad the whitespace so the values are left-
aligned with each other, with at least one space between the colon and the first
character of the value.
```

Update to fix padding issue:

```
in the second example in @README.md > Examples (the one starting with 'mask'),
it would be better if the mask value was left-padded with 0s so that place
values line up with the other binary values printed on the following lines.
```
