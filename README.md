# HelloWorld

You can just drag files into the github page after you commit README.md file.
https://help.github.com/articles/adding-a-file-to-a-repository/

If you like to commit through console:

```
mkdir homework && cd homework
echo "# helloworld-avatar-lavventura" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/CMPE250-Fall-2017-Bogazici/helloworld-avatar-lavventura.git
git push -u origin master —force	
```

Terminal: Getting started with Git, helpful guide: 
https://stackoverflow.com/documentation/git/218/getting-started-with-git
https://try.github.io/levels/1/challenges/1

Your Submission:
A single .cpp file called `helloworld.cpp`. When we run your code it should print on the console "HelloWorld".
