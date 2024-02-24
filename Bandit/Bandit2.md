Bandit Level 2

Using ls -la, we see that there is a file called "spaces in this filename".
Trying to cat its content like below won't work:
"cat spaces in this filename"
That is because the shell interprets the space as a separator.

To fix that you can either enclose the filename in double quotes like below:
cat "spaces in this filename" 

or by escaping the space characters to let the shell treat all the characters as part of the filename.
cat ./spaces\ in\ this\ filename 


Bandit 3 pass: aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

