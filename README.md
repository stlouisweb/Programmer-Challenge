# Programmer-Challenge
Programmer? accept the challenge..   
This is an experiment to try to figure out how many ways there are to skin the cat. No but really this is intended to be a personal challange and a chance to learn and share. To begin fork this repository and replace the README with info on the language you are using and how you plan to go about it, create a seperate fork for each language/stack you use.

## The Challange
Create a simple program using at least 3 different languages. Use and demonstrate OO principals, if you use libraries or frameworks explain why and your selection process.

## The Program 

`gh-search`

The program is a simple client to search for repositories on Github, Here are the requirements:

#### Command Line Tool:
- create an executable command line program that accepts standard input (STDIN), aka the stuff you type in after a command.
- The program should have two options   
  - search
  - list
- the search option is the defualt option, it has one parameter which is the query string, this is an optional parameter
  - the search option should use the github api to search for repositories and return the top 5 by number of stars
  - if github api credentials are not set the user should get a warning with instructions on how to obtain and condigure credientials.
 - All searches should be logged to some kind of database.
- the list option should list all of the recent searches, displaying the time of searchm the query and the results



#### GUI:
Same as CMD but in the browser.   
