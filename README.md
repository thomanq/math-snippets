# Math snippets for LaTeX and Markdown

A set of math snippets for Visual Studio Code.

# Available snippets

Provides autocomplete for most LaTeX math symbols including:
- Common constructs (`\frac`, `\sqrt`, ...)
- Greek letters (`\alpha`, `\beta`, `\gamma`, ...)
- Variable-sized operators (`\sum`, `\prod`, `\int`, ...)
- Arrows (`\mapsto`, `\Rightarrow`, `\Leftrightarrow`, ...)
- Roman names (`\lim`, `\log`, `\sin`, `\cos`, ...)
- Decorations (`\vec`, `\overline`, `\hat`, ...)
- Logic and sets (`\exists`, `\forall`, `\emptyset`, `\in`, ...)
- Fences and delimiters (`\langle`, `\lfloor`, `\lceil`, ...)

These snippets are accessible without the leading backslash character `\`.

In addition to the standard LaTeX names, the following aliases and shortcuts are provided :

|      Alias      |      Resolves to       |                           Description                           |
| --------------- | ---------------------- | --------------------------------------------------------------- |
| `ii`            | `$...$`                | Creates inline math formula with dollar delimiters              |
| `id`            | `$\displaystyle ...$`  | Creates inline displaystyle math formula with dollar delimiters |
| `dd`            | `$$ ... $$`            | Creates display math formula with dollar delimiters             |
| `II`            | `\(...\)`              | Creates inline math formula with bracket delimiters             |
| `DD`            | `\[\]`                 | Creates inline display math formula with bracket delimiters     |
| `abs`           | `\leftǀ... \rightǀ`    | Absolute value                                                  |
| `norm`          | `\left\ǀ ... \right\ǀ` | Vector norm                                                     |
| `lrparentheses` | `\left( ... \right)`   | Matching parentheses                                            |
| `lrbrackets`    | `\left[ ... \right]`   | Matching brackets                                               |
| `bb`            | `\\mathbb{...}`        | Math BB font                                                    |
| `bf`            | `\mathbf{...}`         | Math BF font                                                    |

The full list of supported snippets can be found [here](https://github.com/thomanq/math-snippets/blob/master/snippets/snippets.json).

# How to write math with Markdown

There are several VS Code extensions available from the Marketplace, for example [Markdown+Math
](https://marketplace.visualstudio.com/items?itemName=goessner.mdmath). It is thus possible to use the built-in Markdown preview pane within VS Code.

Another way is to use [KaTeX](https://katex.org/) directly by placing the [starter template code](https://github.com/KaTeX/KaTeX#starter-template) on top of your Markdown file.

# Licence

MIT
