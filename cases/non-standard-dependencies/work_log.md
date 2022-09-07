# Work log on the issue "Create a reproducible notebook with non-standard dependencies"

- We started out installing Quarto.  
  We were both Linux, OS X, and Windows users so this was done in
  several different ways; some downloaded the appropriate Quarto
  package from the Quarto homepage, an ArchLinux user found Quarto as
  a package in the distribution's default repository.
- To work on the issue, we first forked
  <https://github.com/WarwickCIM/quarto-workshop> to
  <https://github.com/alessandrofelder/quarto-workshop> to work on it
  in the latter and eventually create a pull request from it against
  the former.
- One user could not make Quarto work with R code snippets under his
  Ubuntu install, see
  <https://github.com/quarto-dev/quarto-cli/discussions/2333>.
- Some users integrated Quarto in VSCode; with varying success. It
  seems to work from VSCode with simple Python snippets, but attempts
  to import additional packages in the Python code caused Quarto to
  fail. *This was fixed:* Importing `matplotlib` and using it to plot
  seems to require running `%matplotlin inline` in the code snippet
  (like in Jupyter notebooks).
- We have created an example Quarto Markdown file with a Python
  snippet importing some 3rd-party packages as well as a
  requirements.txt file for `pip` which goes along with it.
