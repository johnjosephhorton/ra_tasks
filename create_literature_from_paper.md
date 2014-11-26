Getting Every Paper that Cites a Paper
======================================

Step 1: Getting Started
---------------
1. Email me from the email address you use for your Dropbox account. 
1. I will give you a PDF of an academic article
1. Create a folder called `<last_name_of_first_author>_literature.` For example, if the author's name was smith, it
would be called `smith_literature.` If it is hyphenated name or has an
apostrophe, remove the spaces/apostrophes. 
1. Add me to the folder as a collaborator (don't just share the content). 
1. Create a plain text bibTeX document in that same folder called `literature.bib`.   

Step 2: Finding and documentating each article cited in the original article 
----------------------------------------------------------------------------
For each paper cited in the article (look in the 'references' section): 

1. Find the PDF (ideally the published version on the journal's webpage). Best way to start is to Google the title of the paper. Make a note of any papers you cannot find or access. If it is a book, do not try to add it---just make a note in the "not_found.txt" file you will create (See Step 3.)   
1. Add that PDF to the folder 
1. Rename the PDF to `<last name of first author>_year.pdf`, all lowercase. For
   example, if the article is Adam Smith, 1776, you would name the PDF `smith776.pdf` 
1. For each PDF article, find the bibTeX entry somewhere online, ideally at the actual journal where that article was published. Paste it into `literature.bib.`
1. Each bibTeX entry requires a key that is the first part of a bibTeX entry. The "key" for each entry should be the name of the PDF. For example, suppose the name of the article is `horton2010.pdf`.
The corresponding entry in bibTeX sould be: 
	```
	@article{horton2010,
	    author={Horton, JohnJ. and Rand, DavidG. and Zeckhauser, RichardJ.},
		title={The online laboratory: Conducting experiments in a real labor market},
		year={2011},
		journal={Experimental Economics},
		volume={14},
		number={3},
		pages={399-425}
	}
	```

Step 3: List Articles Not Found
-------------------------------
1. Make a separate plain text file called `not_found.txt` where you list the names of any articles you cannot find, followed by spaces and then a sentence on where you tried looking _all on one line_. 
Add enough space so that the explanation sentences all line up, e.g., 

	```
	horton2010.pdf    Tried SSRN and Experimental Economics but nothing was there. 
	davis2011.pdf     Tried SSRN and arXiv
	```
	

Step 4: Create a List of Keys
-----------------------------
1. Create a plain text document called ``keys.txt`` that lists each of the
used keys in alphabetical order, one per line with no extra spaces. 

	```	
	adams2010
	babcock1988
	charles2014
	zylland2010
	```	

1. Email me when you are done. 
