**Steps for converting any word file to latex format in ubuntu-** <br>

1. Open the word file in google docs.
2. Download it as a html document from the file menu.
3. Install pandoc by **sudo apt-get install pandoc**.
4. Go to the folder where html file is downloaded in the step 2.
5. Convert by using **pandoc file_name.html -s -o final_filename.tex**.
6. You will see a .tex file is created in the current folder.

**Note:-** The file created in step 5 may not be fully identical to your html file so you may need to do some modifications manually.

**Steps for compiling .tex file to pdf.** <br>

1. Install latex by using command **sudo apt-get install texlive-full**.
2. Compile latex using command **pdflatex final_filename.tex**.
3. A pdf file will be generated.




