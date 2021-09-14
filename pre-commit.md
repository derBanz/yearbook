Go to this page and follow the instructions they may change in the future)
https://pandoc.org/installing.html#macos

brew install librsvg python homebrew/cask/basictex

Now on the project file .git/hooks/pre-commit add the following command so that it runs before every commit:

pandoc readme.md --pdf-engine=xelatex -o readme.pdf    (rename the files according to your project)

chmod +x .git/hooks/pre-commit
then add and  commit your file

You should know have a pdf alongside your other project files!


