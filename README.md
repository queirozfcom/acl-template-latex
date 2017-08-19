# acl-template-latex

Simple template for ACL papers.

Using a slightly modified version of natbib (the modified library is `plainnatsimple.bst`, the original is `plainnat.bst`).

- full-width tables with custom column width

- images

- `plainnat` was modified to supress more than 3 authors and not show too many fields (such as address) in the references.

## Using in ShareLatex

To use this template on ShareLatex:

- clone the repo and create a .zip package:

    $ git clone https://github.com/queirozfcom/acl-template-latex.git
    $ zip -r acl-template.zip acl-template-latex

- create a project on ShareLatex, click "upload project" and select the zip file you created on the previous step.
