---
Name: Melanee Sanabria
Course: CIS-106
Semester: Spring 23
Instructor: R. Alberto
---
# Question 1 

| Command | Description                                        | Examples                  |
| ------- | -------------------------------------------------- | ------------------------- |
| Cat     | spits out information                              | cat cars.txt              |
| head    | first 10 lines of text                             | head -10 cars.txt         |
| tails   | last 10 lines  of text                             | tails -10 cars.txt        |
| touch   | creating a new file                                | touch forza.txt           |
| mv      | moving files to other locations                    | mv cars.txt forza.txt     |
| tree    | files in tree form                                 | tree cars.txt             |
| awk     |                                                    |                           |
| tr      | spacing letters within                             | cat cars.txt/tr -s'/n'    |
| man     | manual                                             | man -f ls                 |
| ls      | list of files                                      | ls cars.txt               |
| cut     | cutting sections out                               | cut -b 1 cars.txt         |
| cp      |                                                    |                           |
| grep    | only looking for words that are in quotation marks | grep "blood"  dracula.txt |
| mkdir   | making files                                       | mkdir forza5              |


# Question 2

#### How to work with multiple terminals open?

* when you open one terminal you can open another and put them beside each other making it easier for you to work on both sides

#### How to work with manual pages?

* using you terminal and using the man command and it will bring up the manual page 

#### How to parse (search) for specific words in the manual page

* you could use grep to look for a specific word within the manual page 

#### How to redirect output (> and |)

* when using the > it can append a file and also redirects an output to a file and the | is a straight pipe 

#### How to append the output of a command to a file

* if the file mentions "file doesn't exist" means that file isn't created 

#### How to use wildcards 

* using the star ( * ) you can search from 0 or multiple characters 
* using the question mark ( ? )you can only search for one character
* using the brackets ( [] ) you can only use 1 character that is given within the set of characters

#### How to use brace expansion?

* bracket expansion is useful for example if i did echo {A..D} it will give me {1..4}. 