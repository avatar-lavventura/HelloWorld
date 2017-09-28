## HelloWorld Assignment 
# Due Date: 4.10.2017 00:00

-----------

You can just drag files into the github page after you commit README.md file.
https://help.github.com/articles/adding-a-file-to-a-repository/

If you like to commit through console:

```
mkdir homework && cd homework
git clone https://github.com/CMPE250-Fall-2017-Bogazici/helloworld-<username>.git
#Create your file called helloworld.cpp
git add helloworld.cpp
git commit -m "first commit"
git push -u origin master	
git config credential.helper store #Do this only one time to save your username and password into current repository. 
```

Terminal: Getting started with Git, helpful guide: 
- https://stackoverflow.com/documentation/git/218/getting-started-with-git
- https://try.github.io/levels/1/challenges/1

Your Submission:
A single .cpp file called `helloworld.cpp`. When we run your code it should print on the console "HelloWorld".
