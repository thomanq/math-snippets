# Math snippets for LaTeX and Markdown

A set of math Snippets for Visual Studio code.

# Available snippets

Provides autocomplete for most LaTeX math symbols including:
- Common constructs (`\frac`, `\sqrt`, ...)
- Greek letters (`\alpha`, `\beta`,`\gamma`, ...)
- Variable-sized operators (`\sum`, `\prod`,`\int`, ...)
- Arrows (`\mapsto`, `\Rightarrow`,`\Leftrightarrow`, ...)
- Roman names (`\lim`, `\log`, `\sin`,`\cos`, ...)
- Decorations (`\vec`, `\overline`, `\hat`, ...)
- Logic and sets (`\exists`, `\forall`,`\emptyset`, `\in`, ...)
- Fences / Delimiters (`\langle`, `\lfloor`, `\lceil`, ...)

These snippets are accessible without the leading backslash character `\`.

In addition to the standard LaTeX names, the following shortcuts aliases and shortcuts are provided :


|Alias|Resolves to|Description|
|-|-|-|
|`ii`|`$...$`| Creates inline math formula with dollar delimiter |
|`id`|`$\displaystyle ...$`| Creates inline displaystyle math formula with dollar delimiter|
|`dd`|`$$ ... $$`|Creates display math formula with dollar delimiter|
|`II`|`\(...\)`| Creates inline math formula with bracket delimiter |
|`DD`|`\[\]`| Creates inline display math formula with bracket delimiter|
|`abs`|`\left| ... \right|`| Absolute value|
|`norm`|`\left\| ... \right\|`| Vector norm |
|`lrparentheses`|`\left( ... \right)`| Matching parentheses |
|`lrbrackets`|`\left[ ... \right]`| Matching brackets |
|`bb`|`\\mathbb{...}`| Math BB font |
|`bf`|`\mathbf{...}`| Math BF font|

The full list of supported snippets can be found [here](https://github.com/thomanq/math-snippets/blob/master/snippets/snippets.json).

# Licence

MIT