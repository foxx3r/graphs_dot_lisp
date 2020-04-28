# graphs_dot_lisp
that's a graph made in LISP, usibg graphviz

To use that script, you need to already have installed `graphviz`.

First of all, load the LISP file on SBCL:

`* (load "graph-util.lisp")`

And then, make a list with nodes 'nd edges, after that, execute the function graph->png (or ugraph for unordered graphs), as you can see below:

`* (graph->png "my_file.dot" *wizard-nodes* *wizard-edges*)`

Those lists are specified by default in graph-util, and my_file.dot is the file that'll be written.
