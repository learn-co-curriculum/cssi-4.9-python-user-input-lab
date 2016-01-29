

## User Input Mini App
Let's build a simple input/output app. The main objective is to create an application that _takes in user input, does something with that input, and then prints out an output_.

### Get User Input
The first thing we need to do is take in user input with the `raw_input()` method. When an executed Python program hits the method `raw_input()`, the program pauses and waits for the user to enter text into the terminal.

The way `raw_input()` takes in data from the user is important to remember. It does not interpret the data entered, it merely returns exactly what the user enters, the raw data. The second thing to remember is that `raw_input()`  takes exactly one line of input. Once the user presses enter, what is on that line is what raw_input() returns.

### The Challenge: A Visit to My Favorite City
Let's build an application to plan tourists' visits to your favorite city. Create a new file with `touch trip.py` in terminal. Open `trip.py` with Atom to start writing your program - `open Atom trip.py`.

Ask the user where they would like to stay, what sites they want to visit, what food they want to eat, and how many nights they want to stay. For each question, take input from the user and store it in a variable. <img src="https://s3.amazonaws.com/after-school-assets/greetings.jpg" align="right" width="300" hspace="20">

Once you have that input stored, use string methods (upper(), lower(), capitalize(), etc) to put the input in the proper format. You can always take a look at the Python documentation [here](https://docs.python.org/2/library/stdtypes.html) to learn more about string methods you can use.

Your final output should use *string interpolation* to output the data in a full summary of their trip itinerary. The output should look like this:

Destination: Washington DC
Sites:
 - Visiting the Washington Monument
 - Visiting the Air And Space Museum
 - Visiting the White House
Food: Burgers and Fries
Nights: 3

Remember, you can execute your code by typing `python trip.py` in terminal from inside the directory of this lab. Good luck!

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/cssi-4.9-python-user-input-lab' title='User Input Mini App'>User Input Mini App</a> on Learn.co and start learning to code for free.</p>
