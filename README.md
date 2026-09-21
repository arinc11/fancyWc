# fancyWc
A Node.js command that counts lines and words in a text file.

fancyWc is a Node.js command that extends the basic wc -l command. The original wc -l command counts the number of lines in a text file. fancyWc extends wc by the number of lines and the number of words in the file.

The command can be run from the terminal using:

node fancyWc.js <filename>

Example:

node fancyWc.js example.txt

The program reads the specified file and displays the number of lines and words.

What commands it combines: fancyWc is an extension of the wc -l command rather than a combination of two separate commands. It keeps the line-counting functionality of wc -l and adds word counting as an additional feature.

2. AI-Assisted Programming
What I asked AI: I asked AI for help understanding the assignment, how wc -l works, and how to extend its basic behavior using Node.js. I also asked AI for suggestions for test scenarios and possible edge cases.

Where AI helped: AI helped me understand how process.argv can be used to receive a filename from the terminal and how fs.readFileSync() can be used to read the file. AI also suggested testing a normal text file, an empty file, a nonexistent file, and running the command without providing a filename.

Where I had to think independently: I had to create and run the program, understand its actual behavior, and make changes based on the results of my testing. I also had to decide how to handle edge cases and verify that the changes worked in my own terminal.

What AI got wrong or missed: I didn't have any issues with the AI and my code. In face, it helped me with a syntax 
