# proj2-flask README #
### Author: Shohei Etzel, sse@uoregon.edu ###

### Summary ###
A starter project for using the Flask framework. Running the project hosts a server that holds a class schedule text file along with its html and css formatting. This file can be accessed by a client and viewed on a web browser.

### Running file once in workplace ###
After cloning the git repository to your working repository, do the command "run install", and then "run make". Now your server is up and running!

("make clean" and "make veryclean are typically used before checking things into git.  'clean' should leave the project ready to run, while 'veryclean' may leave project in a state that equires re-running installation and configuration steps)

If you can run flask applications in your development environment, the
application would might be run by
`   python3 syllabus.py`
and then reached with url
`   http://localhost:5000`

(`make run` will launch the debugging server built into flask.  It
provides the best support for tracking down bugs in your server.)

## On ix.cs.uoregon.edu

You may optionally use ix for testing.  This could be of most use to
Windows users;  for MacOS users, there is very little advantage of
testing on ix over testing on MacOS.

## On your Pi

It is important to test your service on your Pi.  You should be able
to write a simple shell script that installs the latest version of
your system (by cloning your repository from github), configures it,
and launches a server for testing.   If you are not familiar enough
with Unix and with bash shell scripting to do that, work with
classmates to develop the scripts you need.  I'll contribute to that
effort, but I prefer to be part of a collaborative effort rather than
just developing the scripts myself and giving them to you.  (I'll
defintely have my own for installing and testing your projects.)


