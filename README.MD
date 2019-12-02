# Latex Template for University of Southampton Coursework

You should be able to compile this latex template if you pay attention to the following points:
- You need to invoke the latex compiler (e.g. `pdflatex`) with the `--shell-escape` flag.
    - If you are using Visual Studio Code with the LaTeX Workshop plugin, this is already configured in the `.latexmkrc` file.
    - If you are using IntelliJ or any other JetBrains product with the TeXiFy-IDEA plugin, you can add this flag in the run configurations under custom compiler arguments.
- You need to have the python package `Pygments` installed, which is used for code listings.
    - If you are not sure wheter it's installed or not, try to run `pygmentize` in a terminal - this will fail if it's not installed.
    - If you need to install `Pygments` run `pip install Pygments`.
