# Analyse Text with python

It is a very tiny project on text analysation.

## The whole execution process is structured as following:

First of all, there is a text document read and opened from the Internet.

Than stopwords and special characters are removed from it.

Afterwards following analysation is processed:

    Wordcloud
    Histogram
    Occurency of Words in whole sentence
    Lexical dispersion plot
    Searching for specific words or sequence of characters occuring in these words

After execution, the output is already shown in the jupyter notebook itself.

Explication of the containing files:

### requirements.txt
If you want to use the code in that project, first of all you have to
set up the specific environment called "fenv".

For doing that please follow the instructions in the "requirements.txt" file.

### program.ipynb
That is the main program. Simply open it in a jupyter notebook.
Do not forget: Maybe you have to change kernel to the specific environment called "fenv".

### documentation.txt
It is just a small documentation about how the creation process of the project was designed and executed.

### stopwords_de.txt
### stopwords_en.txt
These are the lists, containing words which are not required for the analysation process.
