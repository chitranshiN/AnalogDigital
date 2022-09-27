# AnalogDigital

Use Google Colab to run AnalogDigital.ipynb file. Upload the demo folder on google drive. 
Mount google drive on the Colab, use path of demo folder to run test


The function countLine() :
1.Takes 2 arguments as input, one is path of directory, and second argument is optional argument for extention of the filename and default value for second argument is ".txt”.

2.Function reads all the file present in the directory and the sub directory and append the name of files with matching extention into the list "names" and append number of lines present in file with the matching extention into the list "lines".

3.Function uses recursion method if it encounters any sub directory and calls itself with the path of sub directory and provided extension.


Output:
Finally, we return the names and the count of all the files found with matching extention in the directory and sub directories, then we return total number of lines in all the files and then average count of lines per file.
