[Back to Portfolio](./)

HTML Parser
===============

-   **Class: CSCI 315** 
-   **Grade: TBA** 
-   **Language(s): C++** 
-   **Source Code Repository:** [HTML-Parser](https://github.com/JamesCalebWay/HTML-Parser)  
    (Please [email me](mailto:jcway@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The HTML parcer is a commandline application that will parse an HTML file, determine if its HTML tags are balanced, and will count the amount of visitable, unique links. The parser can handle multiple HTML files and will display each file with its associated output.

## How to compile and run the program

The easiest way to use the parser is to place your HTML files into the included `pages` folder which should be inside the same folder as the parcer `src` folder and the included makeFile. Then in a bash terminal run the make command:

```bash
make given
```
And thats it. The results will be dispayed in the terminal (Fig. 1)

When you are done run the make command:

```bash
make clean
```
This command will delete the executable file.

![parcer](/images/HTML%20Parser/Parser.png)  
Fig 1. Parcing and Crawling web page.

There are sample HTML files in the pages folder.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
