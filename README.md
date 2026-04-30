# Jean-Gabriel Cordier

Mathematical engineer. I work across parsing, algorithms, formal specification, and data engineering. Below is a selection of projects — active and completed.

---

## Active Projects

### [MarkdownToLaTeX](https://github.com/gitcordier/MarkdownToLaTeX)
A Markdown-to-LaTeX parser, installable via [`pip install MarkdownToLaTeX`](https://pypi.org/project/MarkdownToLaTeX).

The parser implements a state machine with bounded memory for context tracking. The design was formally specified in [TLA+](https://github.com/tlaplus) before being implemented in Python — following the methodology described in Lamport's [*Specifying Systems*](http://lamport.azurewebsites.net/tla/book.html).

- [State machine source](https://github.com/gitcordier/MarkdownToLaTeX/blob/main/src/markdowntolatex/markdown/parser.py)
- [LaTeX document structuring](https://github.com/gitcordier/MarkdownToLaTeX/blob/main/src/markdowntolatex/latex/document.py)
- [Documentation](https://markdowntolatex.readthedocs.io)

A new version of MarkdowntoLaTeX is currently under development. Switch to the dev branch to follow its progress.

- [specifications](https://github.com/gitcordier/MarkdownToLaTeX/tree/dev/specs)

### [Functional Analysis](https://github.com/gitcordier/FunctionalAnalysis) ⭐ 16
Selected solutions to Rudin's *Functional Analysis*. Ongoing revision and expansion.

### [TLA+ Specifications](https://github.com/gitcordier/tlaplus)
Formal specifications written in TLA+. Includes a specification of the reversible hoist invented by Renaissance architect Brunelleschi. ([Historical reference](http://bdml.stanford.edu/Main/BrunelleschiNotes))

### [SAT-Style Math MCQs](https://github.com/gitcordier/SAT-style-math-MCQs)
A collection of SAT-style mathematics problems, written for teaching, with an appendix for advanced readers. Each exercise is accompanied by a Python program that computes the solution. Currently available in French; an English edition is in preparation.

---

## Completed Projects

### [Jobmap](https://github.com/gitcordier/jobmap)
An interactive job search interface that renders results on OpenStreetMap, backed by the Adzuna Jobs API.

### [Bellingcat](https://github.com/gitcordier/bellingcat) ⭐ 11
Python3 translation of [Bellingcat's open-source intelligence guides](https://www.bellingcat.com/category/resources/how-tos).

### [TheChemicalBrowsers](https://github.com/gitcordier/TheChemicalBrowsers)
A parser that counts atoms per element from a chemical formula string, returning the result as a dictionary. Parsing proceeds right-to-left, which simplifies handling of nested parenthetical groups.

### [stack_qalculator](https://github.com/gitcordier/stack_qalculator)
A [Reverse Polish Notation](https://en.wikipedia.org/wiki/Reverse_Polish_notation) calculator implemented as a stack-based processor.

### [ReversePolishNotationParser](https://github.com/gitcordier/ReversePolishNotationParser) ⭐ 1
An alternative Reverse Polish Notation parser implementation.

### [Salesman Problem: Special Quadratic Case](https://github.com/gitcordier/minimal_length_of_graph_traversal)
A solution to a restricted variant of the travelling salesman problem that admits a quadratic-complexity algorithm. Originally encountered in a competitive programming context.

### [Using Selenium](https://github.com/gitcordier/selenium)
A reusable Selenium scraping template that extracts participant website links from a structured event directory page.
