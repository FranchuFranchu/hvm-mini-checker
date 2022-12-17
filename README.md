# hvm-mini-checker

This is a typechecker written in Kind2 where I'm testing out some ideas.

The code is in the `L` directory. (L stands for "Language").

Run `kind2 run L/Main.kind2` to see an example of what it can do now.

I'm having some issues with parsing right now. It seems to produce terms that look similar to those produced by hardcoding the terms in the Kind2 code, but they behave differently and the parsed terms end up making the typechecker get stuck.

See `L/algorithm.txt` for a summary on notation. The actual code uses slightly different notation; parentheses are skipped and function application is `(function argument)`