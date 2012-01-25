# Extending Ruby With C

This is the examples and instructions from the 2/21/12 Groupon Geekfest.

# Generating the html version

You can generate an html version of this document will full syntax highlighting by running

    M-x org-export-as-html-to-buffer

after that is run, simply save the buffer to a file of your choosing

# Generating the source code

The org-mode document will generate all of the code for the example in the correct locations by running

    C-c C-v t
	
This executes `org-babel-tangle` against the document and extracts all necessary code to the proper locations.
