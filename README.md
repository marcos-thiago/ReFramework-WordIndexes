# ReFramework-WordIndexes
Solution to a problem presented in a real interview, using ReFramework, PDF file, text files and MS Excel. 

You are free to use your own creative solutions but the following needs to be applied and show in your coding.
-	RE – Framework
-	Using a Queue
-	Best practices and standards
-	Effiency

1.	Creating the queue <br>
a.	Read the contents of the extracted zip folder (RPA – UiPath – Test\1_Question) <br>
b.	Add all the .txt files to the queue by adding the filename to the transaction specific content.<br><br>
2.	Processing the queue<br>
a.	Read the transaction item and retrieve the filename<br>
b.	Filenames that contain a digit, rename the file by removing the digits.<br>
c.	Filenames that has no digit, rename the file by appending the index of the transaction number followed by a “_” separator. e.g. 1_Filename.txt<br>
		    i.	Transaction number should start at 1.<br>
d.	Move the file (.txt file) to a new folder Output/Files Moved/<br>
e.	Read the file WordIndexes.xlsx <br>
f.	Retrieve the Word Index based on the filename <br>
g.	Read the Trump Ipsum - Make placeholder text great again.pdf file and retrieve the word based on the index from step 2.f. <br>
h.	Write the word to a .txt file called Answer <br><br>
3.	Format the Answer.txt file so that all the words are in 1 paragraph. 
