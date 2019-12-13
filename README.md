# Diamond Programming Language
![Diamond logo](/images/logo.PNG)

*Setting up:*
To install diamond onto your computer, download the installer folder. After that run install.bat, to get diamond installed once installed go to cmd and type ```python C:\diamond\dia.py -h``` for help. To run code type ```python C:\diamond\dia.py [file location here]```. After everything is done there is a test script at C:\diamond\main.d. Run that, and if it succeeds, you have installed diamond succesfully.

*Language Basics:*
The diamond language is highly based off of pascal, so it has a lot of the same syntax. The following code makes and sets two variables: 
```
software Main;
vi x, y : integer;
start { Main }
   y = 7;
   x = (y + 3) * 3;
finish.  { Main }
```

Once the program is done, you can see the values of the variables by typing ```python C:\diamond\dia.py --stack [file_location]```. 
If you are using Diamond V1.0 you will have to use y := 7;

*What will be in the future?*
I have many plans for diamond in the future. The first is to add more functions that will help a lot in making programs, like input() or print().A friend of mine is also working on server librarys for the language.

[![Run on Repl.it](https://repl.it/badge/github/crohn64/Diamond)](https://repl.it/github/crohn64/Diamond)
