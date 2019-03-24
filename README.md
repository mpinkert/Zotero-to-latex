# Zotero-to-latex

Converting a Zotero based document to LaTeX can be very tedious, involving manually editing each citation into the proper format.
The notebook and style language in this repository let you simply this process by simply selecting a style, and then copy and pasteing
text into the main latex document and the bibliography into the bibliography file.  

The style format matches the way Zotero natively creates Bibtex citations, so you can convert your entire library to a latex bibliography.
This lets you reference any new citations easily.

## How to use

There are two steps to using this style:

1.) Run the notebook on your Zotero library
2.) Import the style and select it for your document

The style requires that the short-title keyword in a citation holds the first meaningful word of the title.  E.g., the first meaningful
word of "The health benefits of not smoking" is "health"  The notebook accesses your zotero library in order to perform this conversion automatically.  It includes a check to see if the keyword 
is already in the right format, so it runs much faster when you are adding new citations.

## Contact/contribute

Please feel free to contact me if you discover any bugs with this style or to submit a pull request with your own fixes.
