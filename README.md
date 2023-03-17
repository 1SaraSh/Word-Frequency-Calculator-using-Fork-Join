# Word-Frequency-Calculator-using-Fork-Join

The aim of this project is to implement a word frequency calculator using the Fork/Join framework in Java.(Netbeans version 12.5 was formally used).The program should be able to read in multiple text files from a directory and calculate the frequency of the words "then" and "and" in each file. The program will use the Fork/Join framework to parallelize the frequency calculation across multiple files. The program should print the frequency values of each word in each file to the console. 
Number of cores you need to use, and Threshold can be editted depeding on your preference and the files themselves
<br><br>
<p>_<b>The program will be reading text files from the dataset provided in the source code for this assignment.</b>_</p>

The file has a collection of <b>TEXT</b> files. The directory used in this example is:<br>
<i>"C:\\Users\\saraa\\OneDrive\\Desktop\\Distributed Systems\\Dataset\\train1".</i>
<br>
<p>Please specify your own directory with your text files, or the text files provided in "dataset" Folder. Edit the code in the areas with an X, with your preferred directory.</p> 
<p><i>Note: All of "dataset" folder content is taken from Wikipedia.</i></p>

<h3>Run</h3>
Starting the program is simple, it will run all of the files and calculate the "and" and "then" words. 
<br><br>

<h3> Display:</h3>
It will display the frequency of your word in each file, and print it. Also the execution time will be printed. 
_Note: Time is calculated from start of ForkJoinPool till after printing._
          
