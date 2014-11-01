Organizing a folder of PDF articles 
-----------------------------------
1. Email me from the email address you use for your Dropbox account. 
1. I will add you as a collaborator to a folder filled with PDF files, which will usually be called `literature.` 
1. You will create a plain text bibTeX document in that same folder called `literature.bib`.   
1. For each PDF article, find the bibTeX entry somewhere online, ideally at the actual journal where that article was published. 
Make a separate plain text file called `not_found.txt` where you list the names of any articles you cannot find, followed by spaces and then a sentence on where you tried looking _all on one line_. 
Add enough space so that the explanation sentences all line up, e.g., 

	```
	horton2010.pdf    Tried SSRN and Experimental Economics but nothing was there. 
	davis2011.pdf     Tried SSRN and arXiv
	```
	
1. Each bibTeX entry equires a key. The "key" for each entry should be the name of the PDF.
For example, suppose the name of the article is `horton2010.pdf`.
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

1. Create a plain text document called ``keys.txt`` that lists each of the
used keys in alphabetical order, one per line with no extra spaces. 

	```	
	adams2010
	babcock1988
	charles2014
	zylland2010
	```	

1. Email me when you are done. 
