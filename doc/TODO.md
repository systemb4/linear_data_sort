# do
* documentation of each function line by line comments
* documentation of how it works
* have a default main.c that is compiled and installed to system
* fix up make file

* function for switch statments - lexer
* add comparison ops - lexer

* addDef function get working
* sor function works for both definitions and names
* structure AST so that it can be more widely implementable
    * be able to link more defs to name but no def should be linked to def and
      no name should be linked to def
    * AST is linear sort of that it is a linked list but with multiple types to
      each node
    * try to make it a tree and each head of tree is linked to each other OR the
      tree just goes down further as the code progresses

# review
* sort function for all of the tokens

# done