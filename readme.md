# movieratings

A simple game that compares two movies and asks the user to guess
which has a better IMDb rating. Movies are read from movielist.txt,
and ratings are fetched from the OMDb API.

Written as an example for the PyLadies API Workshop in July 2013.

TODO:

Error checking.
 
Right now a new request is created each time information about a
movie is fetched, even if the movie already appeared in the game.
This could be done more intelligently.
