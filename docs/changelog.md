Change log dicemechanicsim v0.97:

* Most variables have been moved to the top for quick and easy manipulation.
* NPC scoring is now relational to the player.
* The scoring table now matches the first publishing of Midnight Riders and
  is represented by data20171030-1553.zip.
* Groundwork for informed decisions (AI) has been introduced, but the data
  is not yet implemented.
* Battles do not result in point loss.
* NPC probability can be finely tuned and the result is stated at the end.
* Swapped Madness and Reputation order.

Change log plotcsv v1.0:

* Accept filename argument to analyze data of arbitrary csv files.

Change log dicemechanicsim v0.96:

* Python 3 only.  See the python 2 section to modify the code for python 2.
* Runs plotdicemechanic at completion.

Change log plotdicemechanic v1.0:

* Parse csv file to output graph as .png file with matplotlib.

Change log dicemechanicsim v0.96:

* Added a new scoring table.
* Changed game order to separate points from opponent.
* Static NPC choices can easily be set for player 1, late game, or all players.

Change log plotdicemechanic v0.5:

* Parse csv file to output graph as .html file with plotly.
* html file can export graph as a png or svg.

Change log dicemechanicsim v0.95:

* Outputs to a .csv file with a name based on the local time in native python.
* Static options for number of player and individual player choice are optional.
