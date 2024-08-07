You've heard of Markdown, perhaps even Markleft or Markright – but have you heard of Markthrough? Probably not! Markthrough is a lightweight markup syntax that's just a step up from plaintext.

This project is still under development. For updates, see the project's [repository](https://github.com/markthrough/Markthrough.github.io).

### What makes Markthrough special?
Unlike Markdown, the plain text (ex. `**bold**`) and the final rendering (ex. **bold**) are two different things. If you wanted to copy/paste the final rendering of any Markdown text, you'd lose all the syntactic formatting (the `**` in `**bold**`).


In Markthrough, the plain text & final rendering are the same thing. Don't be mistaken – styling is still employed – but all the plaintext is still there. If you copy/pasted the styled Markthrough, you'd still have everything.


The syntactic choices were chosen to make sense – ex. declaring headers in ALL CAPS, having fill-in-the blanks represented by ___, or quote-text as `| quote-text`. Even if you were to strip away all the styling, Markthrough would still make sense. This makes it especially useful for the CLI, where text styling/formatting is limited.


Markdown, I strongly believe, has strayed from its origins a bit. Why are there two different ways to represent code? For a syntax that aims to be simple, that is one too many ways to represent code. Instead of `code` and `fenced code blocks`, how about we just treat everything inbetween two backticks as the same thing? If it's single-line, it's `code`, and if it's multi-line, it's a `fenced code block`.

Also, why do you need to need to press enter twice for a newline in Markdown? A newline is a newline, damnit!


Markdown has a total of 17 features – which is far too many. Who even needs emojis? Is your 45-year-old aunt using Markdown? Probably not! While we're at it, we can throw images out the window too. You can just link it.


The same goes for terms/definitions, footnotes, super/subscripts, and all the other frivolous features of Markdown. Some Markdown features have been combined into one – like lists. Instead of having different list types for `1)` numbers or `a)` letters, you can put anything you want behind the `)`. If it's sequential, Markthrough will autofill with the next in the sequence – Roman numerals included (which, last I checked, Markdown does not support). You can put `*)`, which turns it into a checkbox. You can even have unordered lists by using `–` or `*`. It's beautiful.


In the words of Henry David Thoreau,

> Our life is frittered away by detail. Simplify, simplify.
