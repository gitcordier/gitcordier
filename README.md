## ▶️ [Functional Analysis](https://github.com/gitcordier/FunctionalAnalysis) 16 ⭐️

Some solutions to Rudin's Functional Analysis.
It's been a long time I haven't added new content. I really should but proofreading takes time…
Rewriting is ongoing.

## ✅ [Bellingcat](https://github.com/gitcordier/bellingcat) 11 ⭐️

Code from [Bellingcat&#39;s guide](https://www.bellingcat.com/category/resources/how-tos).

## 👨‍💻 { Hi !

## ▶️ [MarkdownToLaTeX](https://github.com/gitcordier/MarkdownToLaTeX)

I am currently working on
[MarkdownToLaTeX](https://github.com/gitcordier/MarkdownToLaTeX), a Markdown-to-LaTeX parser you
can [`pip -install`](https://pypi.org/project/MarkdownToLaTeX).

The MarkdownToLaTeX parsing implements a state machine of which steps are decided by
✏️ The last input character,
📝 A bounded memory that stores the necessary context.

The state machine source code is [here](https://github.com/gitcordier/MarkdownToLaTeX/blob/main/src/markdowntolatex/markdown/parser.py).
Markdown parsing and LaTeX document structuring are combined
[here](https://github.com/gitcordier/MarkdownToLaTeX/blob/main/src/markdowntolatex/latex/document.py).

MarkdownToLaTeX started as a toy project to which I could apply
[`<img src="https://raw.githubusercontent.com/gitcordier/gitcordier/main/tlaplus.png" alt="TLA Plus" width="3%">`](https://github.com/tlaplus),
as explained in
[Specifying Systems](http://lamport.azurewebsites.net/tla/book.html?back-link=learning.html#book).
The parsing state machine was first written in
[`<img src="https://raw.githubusercontent.com/gitcordier/gitcordier/main/tlaplus.png" alt="TLA Plus" width="3%">`](https://github.com/tlaplus), next in
[`<img src="https://raw.githubusercontent.com/gitcordier/gitcordier/main/python-logo@2x.png" alt="Python" width="7%">`](https://github.com/gitcordier/MarkdownToLaTeX).

A compiled-from-code [documentation](https://markdowntolatex.readthedocs.io) and a
[mathsheet](https://raw.githubusercontent.com/gitcordier/MarkdownToLaTeX/main/MarkdownToLaTeX_Mathsheet.pdf) are available as well.
The first chapter of the mathsheet is about formal specification and my very own story with the topic.
I am always eager to learn, so feel free to give me a feedback!

This is an ongoing process… 🚣 but I try as hard as I can to keep up the pace.

## ▶️ [tlaplus](https://github.com/gitcordier/tlaplus)

This repository is dedicated to TLA + specifications. Currently, you may find here the specification of a reversible hoist, invented by the Renaissance architect Brunelleschi. Relevant historical note and pictures available at http://bdml.stanford.edu/Main/BrunelleschiNotes.

## ✅ [The ChemicalBrowsers](https://github.com/gitcordier/TheChemicalBrowsers)

Given a chemical formula represented by a string,
the parser counts the number of atoms of each element contained in the molecule
then returns the result as a dictionary.

The trick is: Reading formulas from right to left makes the algorithm pretty straightforward.

## ✅ [stack_qalculator](https://github.com/gitcordier/stack_qalculator)

Written for a job interview: A
[Reverse Polish Notation](https://en.wikipedia.org/wiki/Reverse_Polish_notation) calculator.
In other words, you can think of it as a stack-based process: First, push numbers in the stack, next compute then save the result as tail of the stack.

## ✅ [ReversePolishNotationParser](https://github.com/gitcordier/ReversePolishNotationParser) 1 ⭐️

Another reverse polish parser, written for a previous job process.

## ✅ [Salesman problem: Special quadratic case](https://github.com/gitcordier/minimal_length_of_graph_traversal)

The special case means quadratic complexity. I like this problem, since getting a clean algorithm was a little bit tricky, but I could make it. Found the problem in a coding contest.

## ✅ [Using Selenium](https://github.com/gitcordier/selenium)

Given a workshop (at this time, it was https://www.parisfintechforum.com), the script gets all "featured" participants websites (Source: https://www.parisfintechforum.com/PFF2018/participants).
you can see this code as a template: I assume that the code can be easily reused and applied to other websites.
