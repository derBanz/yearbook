# Python Fundamentals Group Project

In this project you are tasked with creating a year book for your class. Just like you probably have done in school. It should contain at least the following sections:

* A personal profile for each of the class members;
* A representative article on something they have learned so far;
* More! :)

After the book has been assembled, it will be sent off to a printing company. Rather than markdown files, the printing company needs a pdf of the book. This file needs to be created by the group as well. Do some research into how a pdf can be automatically derived from a set of markdown files. Automate the process of creating this pdf using git-hooks.

Tasks that _each_ of the group members should do include the following:

1. Use git for tracking changes to the year book.
2. Employ the _commit fast - commit often_ mentality.
3. Use descriptive commit messages.
4. Use the [git flow][1] methodology for contributing the individual texts to the main repository. Discuss the method within the group and decide how you will integrate it into the workflow.
5. Implement the workflow.

The role of the _integration manager_ must be filled by either the entire group or by a singular student. All commits to the repository must be merged by the _integration manager_, resolving merge conflicts along the way. [You decide][whyPR] whether you use direct write access to the repository or employ [pull requests][pr-difference].


[1]: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=The%20overall%20flow%20of%20Gitflow,branch%20is%20created%20from%20develop&text=When%20a%20feature%20is%20complete%20it%20is%20merged%20into%20the,merged%20into%20develop%20and%20main
[whyPR]: https://softwareengineering.stackexchange.com/questions/340364/if-i-have-direct-commit-access-is-there-any-reason-to-create-a-pull-request-for
[pr-difference]: https://stackoverflow.com/questions/35007939/what-is-the-difference-between-commits-and-pull-requests
