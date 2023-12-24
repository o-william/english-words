List Of English Words
=============

This repository is originally from https://github.com/dwyl/english-words/tree/master. All work is his. I only uploaded this here for my personal use in my projects and as a quick access backup. Feel free to use. My use case for this is for practicing with a large set of data, especially for things like sorting algorithms. This is not the most complete english list of words. For critical development needs, use an API of dictionary sites like Merriam-Webster. This is because words are being added to the english dictionary every year. Also, more information exists on sites like Merrian Webster, such as definitions, antonymns and so on. I do not actively maintain this repository to reflect this, and I do not think the original owner does this either. For me, this is just a data source for me, for things like sorting algorithms in Python and C++ projects.

Below is his description of the repository.

A text file containing over 466k English words.

While searching for a list of english words (for an auto-complete tutorial)
I found: https://stackoverflow.com/questions/2213607/how-to-get-english-language-word-database which refers to [https://www.infochimps.com/datasets/word-list-350000-simple-english-words-excel-readable](https://web.archive.org/web/20131118073324/https://www.infochimps.com/datasets/word-list-350000-simple-english-words-excel-readable) (archived).

No idea why infochimps put the word list inside an excel (.xls) file.

I pulled out the words into a simple new-line-delimited text file.
Which is more useful when building apps or importing into databases etc.

Copyright still belongs to them.

Files you may be interested in:

-  [words.txt](words.txt) contains all words.
-  [words_alpha.txt](words_alpha.txt) contains only [[:alpha:]] words (words that only have letters, no numbers or symbols). If you want a quick solution choose this.
-  [words_dictionary.json](words_dictionary.json) contains all the words from words_alpha.txt as json format. 
If you are using Python, you can easily load this file and use it as a dictionary for faster performance. All the words are assigned with 1 in the dictionary.

See [read_english_dictionary.py](read_english_dictionary.py) for example usage.
