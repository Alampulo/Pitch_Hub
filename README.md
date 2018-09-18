# Pitch_Hub

A flask application that allows users submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.
## Author

* Bryan Juma
## Description

This application enables a user :
* To see the pitches other people have posted.
* To vote on the pitch they liked and give it a downvote or upvote.
* To comment on the different pitches and leave feedback.
* To submit a pitch in any category.
* To view the different categories.

## Prerequisites
 * Install python3.6
 * Install pyperclip (Third party module)

## Installing

### Install Python3.6

	$ sudo apt-get update
	$ sudo apt-get install python3.6
	Confirm installations

	$ python3.6

	Python 3.6.5 (default, Sep 9 2018, 17:05:23)
	[GCC 5.4.0 20160609] on linux
	Type "help", "copyright", "credits" or "license" for more information.
	>>>


 ### Install Pyperclip Module

	$ python3.6 -m pip install pyperclip

## How to get the app

	$ cd Document
	$ git clone https://github.com/Alampulo/Pitch_Hub
	$ cd Pitch_Hub
## Running One Minute PItch

 	 $ python3.6 run.py /
	 $ ./run.py

## Running Test

 	$ python3.6 user_test.py

## Technology Used

* Python3.6/flask
* bootstrap
* html/css
* postgresql

## Known Bugs

* How to activate the comments and vote the pitches

## Versioning

* 5/9/2018
## Specifications

### Pitch Pool specifications
| Behavior        | Input           | Outcome  |
| ------------- |:-------------:| -----:|
| Register to be a user | Your email : jumabryan@gmail.com.com <br> Username : jon101 <br> Password :@askoe97 | New user is registered |
| Log in | Your email : jumabryan10@gmail.com <br> Password : @askoe97 | Logged in 
| Display pitch categories | Categories display on navbar | List of various pitch categories |
| See pitches from selected category | **Click** a category | Directed to a page with a list of pitches from the selected category |
| Create a pitch | **Click Add a pitch** | An authenticated user is directed to a page with a form where the user can create and submit a pitch |
| Comment on a pitch | **Click Comment** | An authenticated user is directed to a page with a form where the user can create and submit a comment on a pitch. |

## Support and contact details

* For any compliment contact.

* No. 0701323172

* email: bryanjuma10@gmail.com



## Licence

MIT License

Copyright (c) 2018 Bryan Juma

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

