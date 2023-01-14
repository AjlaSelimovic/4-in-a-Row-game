# 4-in-a-Row-game


![image](https://user-images.githubusercontent.com/92023522/211146248-fb9d10d5-310b-4fbe-bb76-4cbb3a7440b9.png)





# About the Project
4-in-a-Row // Connect Four is a two-player connection board game, in which the players choose a color and then take turns dropping colored tokens into a vertically suspended grid. Whichever player manages to connect 4 tokens of the same color horizontally, vertically or diagonally wins the game.

This project was implemented in Ruby programming language, for purposes of IT 305 Programming Languages course at International Burch University.

Team members: 
[Dženeta Džananović](https://github.com/dzenetadz)

[Amina Kodžaga](https://github.com/aminakodzaga)

[Ajla Selimović](https://github.com/AjlaSelimovic)


#This implementation has a `FourInARow` class with a constructor that initializes the board with the specified number of rows
 and columns and sets the current player to `:red`. The `play` method runs a loop where each iteration represents a turn for the
 current player. The player is prompted to enter a column number, and the `drop_piece` method is called to place the piece at the bottom of the
 chosen column. The `check_win` method is then called to check if
 the current player has won the game by getting four pieces in a row horizontally, vertically, or diagonally.
 If a win is detected, the loop is broken and the current player is declared the winner.
 If all cells on the board are filled and no win is detected, the game is declared a tie and the loop is broken.

There is a new instance variable called @moves which is a hash that stores the history of moves for each player. 
The key of the hash is the player's color (either :red or :yellow) and the value is an array of column numbers representing the moves made by that player.
For example, if the red player makes the first move in column 3 and the yellow player makes the second move in column 4, 
the @moves hash will be { red: [3], yellow: [4] }. If the red player then makes the third move in column 2, the @moves hash will be { red: [3, 2], yellow: [4] }.
At the end of the game, the @moves hash is printed to the console along with the list of moves made by each player.


# About Ruby
A dynamic, open source programming language with a focus on simplicity and productivity. It was created in 1993 by Yukihiro Matsumoto of Japan. It has an elegant syntax that is natural to read and easy to write.

Ruby has features that are similar to those of Smalltalk, Perl, and Python. Perl, Python, and Smalltalk are scripting languages. Smalltalk is a true object-oriented language. Ruby, like Smalltalk, is a perfect object-oriented language.

**Features of Rubby** :


Ruby is a general-purpose, interpreted programming language.

Ruby is a true object-oriented programming language.

Ruby is a server-side scripting language similar to Python and PERL.

Ruby can be used to write Common Gateway Interface (CGI) scripts.

Ruby can be embedded into Hypertext Markup Language (HTML).

Ruby has a clean and easy syntax that allows a new developer to learn very quickly and easily.

Ruby has similar syntax to that of many programming languages such as C++ and Perl.

Ruby is very much scalable and big programs written in Ruby are easily maintainable.

Ruby can be used for developing Internet and intranet applications.

Ruby can be installed in Windows and POSIX environments.

Ruby support many GUI tools such as Tcl/Tk, GTK, and OpenGL.

Ruby can easily be connected to DB2, MySQL, Oracle, and Sybase.

Ruby has a rich set of built-in functions, which can be used directly into Ruby scripts.


# How to run
To run the project, you will first need to install Ruby. You can find detailed instructions [on this link](https://rubyinstaller.org/downloads/).

Instructions to run: in a terminal window at the folder of the project type:  ruby 4game.rb
