# AI Use Log
-Log 1 — strip()
    Tool/model & version: GPT-5.6 Luna
    What I asked for: what does "strip" mean in the counting code
    Snippet of prompt(s): to not include whitespace like \n
    What I changed before committing: nothing
    How I verified correctness (tests, sample data): ran test and made sure no errors
- Log 2 — P13: Reading files
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to use with open() and read() to read a file
    Snippet of prompt(s): how do I open practice.txt and print its contents using with open() and read()
    What I changed before committing: added the file-opening and reading code
    How I verified correctness (tests, sample data): ran the code and checked that the contents of practice.txt printed correctly
- Log 3 — P13: read(), readline(), and readlines()
    Tool/model & version: GPT-5.6 Luna
    What I asked for: the difference between read(), readline(), and readlines()
    Snippet of prompt(s): why do readline() and readlines() return nothing after using read()
    What I changed before committing: tested the functions separately using comments to turn commands on and off
    How I verified correctness (tests, sample data): ran each function separately and compared what each one returned
-Log 4 — P14: Storing file contents
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to store the contents of a file in a list after reading it
    Snippet of prompt(s): how do I use readlines() to store each line in a list and then work with the list after the file closes
    What I changed before committing: assigned the result of readlines() to a list variable
    How I verified correctness (tests, sample data): printed the list and checked that each line was stored as an item
-Log 5 — P14: join()
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to use join() to print a list of file lines in the original format
    Snippet of prompt(s): how does "".join() work with a list of lines from a file
    What I changed before committing: used join() to combine the lines
    How I verified correctness (tests, sample data): compared the output to the original practice file
-Log 6 — P15: for loops with files
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to use a for loop to process each line of a file
    Snippet of prompt(s): how do I use a for loop with an open file to print each line
    What I changed before committing: added a for loop inside the with open() block
    How I verified correctness (tests, sample data): ran the code and checked that each line of the file was printed
-Log 7 — P15: Extra newlines
    Tool/model & version: GPT-5.6 Luna
    What I asked for: why printing file lines creates extra newlines
    Snippet of prompt(s): why are there blank lines between each line when I print the file
    What I changed before committing: used rstrip() to remove the newline from each line before printing
    How I verified correctness (tests, sample data): ran the program and confirmed that the extra blank lines were removed
-Log 8 — P15: Rosalind #4
    Tool/model & version: GPT-5.6 Luna
    What I asked for: help solving Rosalind #4 using a file and a loop
    Snippet of prompt(s): how can I print only the even-numbered lines from the file using a counter
    What I changed before committing: added a counter and a condition to determine which lines to print
    How I verified correctness (tests, sample data): tested it with the Rosalind sample dataset and compared the output with the expected result
-Log 9 — P16: split()
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to use split() to loop through individual words
    Snippet of prompt(s): how does for word in line.split() work and why does leaving the parentheses empty split on whitespace
    What I changed before committing: used split() inside the for loop
    How I verified correctness (tests, sample data): ran the code with the Rosalind #5 sample data and checked that each word printed separately
-Log 10 — P17/P18: Dictionaries
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to create, access, and update a Python dictionary
    Snippet of prompt(s): how do dictionary keys and values work, and how do I add or update a key:value pair
    What I changed before committing: created the dictionary and added/updated key:value pairs
    How I verified correctness (tests, sample data): printed specific dictionary values and checked that they matched the expected sequences
-Log 11 — P18: Rosalind #5
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to use a dictionary to count how many times each word occurs
    Snippet of prompt(s): how do I check if a word is already in the dictionary and increase its count if it is
    What I changed before committing: added the dictionary membership check and count update
    How I verified correctness (tests, sample data): ran the code with the Rosalind sample dataset and checked the word counts
-Log 12 — P19: count()
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to modify the dictionary solution to use count()
    Snippet of prompt(s): how can I use count() to count words that are not already in the dictionary
    What I changed before committing: added count() inside the condition that checks whether the word is already present
    How I verified correctness (tests, sample data): ran the program and compared the counts with the expected results
-Log 13 — P20: Installing Biopython
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to test whether Biopython installed correctly
    Snippet of prompt(s): give me a brief test to be sure biopython is installed correctly
    What I changed before committing: added the suggested import/test
    How I verified correctness (tests, sample data): ran the test and made sure there were no import errors
-Log 14 — P21: Seq
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to use the Biopython Seq object
    Snippet of prompt(s): how do I use Seq to transcribe DNA into RNA
    What I changed before committing: imported Seq and used its sequence functions
    How I verified correctness (tests, sample data): tested the code with the practice sequence and checked the resulting RNA
-Log 15 — P21: Rosalind #7
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to modify the transcription solution so it reads the sequence from a file
    Snippet of prompt(s): how can I read the Rosalind DNA sequence from a file instead of copying it directly into the code
    What I changed before committing: changed the code to read the sequence from the practice file
    How I verified correctness (tests, sample data): tested the code using the practice dataset and checked the RNA output
-Log 16 — P21: Rosalind #8
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to translate an RNA sequence into a protein using Biopython
    Snippet of prompt(s): how do I use Seq to translate RNA into protein for Rosalind #8
    What I changed before committing: used the appropriate Biopython translation function
    How I verified correctness (tests, sample data): ran the code with the sample sequence and checked the protein output
-Log 17 — P22: SeqIO
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to use SeqIO.parse() to read a FASTA file
    Snippet of prompt(s): how do I use SeqIO.parse() to loop through each sequence in a FASTA file
    What I changed before committing: imported parse and used it in a for loop
    How I verified correctness (tests, sample data): ran the code with the practice FASTA file and checked the sequence IDs
-Log 18 — P23: GC content
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to calculate GC content using Biopython
    Snippet of prompt(s): how do I use gc_fraction() to calculate the GC content of each sequence
    What I changed before committing: imported gc_fraction() and used it on each sequence
    How I verified correctness (tests, sample data): ran the program and checked the GC percentages
-Log 19 — P23: Finding maximum GC content
    Tool/model & version: GPT-5.6 Luna
    What I asked for: how to find the sequence with the highest GC content
    Snippet of prompt(s): how do I keep track of the highest GC content and the ID of the sequence while looping through the FASTA file
    What I changed before committing: added variables for the maximum GC value and corresponding sequence ID and updated them when a higher value was found
    How I verified correctness (tests, sample data): ran the code with the Rosalind #9 sample dataset and compared the final ID and GC content with the expected output
-Log 20:
    Tool/model & version: GPT-5.6 Luna
    What I asked for: can you help me make a log of my AI usage based on what I've asked you so far and based off of my coding assignment
    How I verified correctness: read through all the logs and made sure they aligned with what I had asked
