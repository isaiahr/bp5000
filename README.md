# Bracket Program 5000
A tournament bracket software supporting arbitrary high elimination.
meaning it supports triple elimination, quad elim etc as well as single & double.

### What it does
 - bracket generation and viewing
 - supports arbitrarily high elimination
 - match reporting
 
### What it doesn't do (yet)
 - projected bracket by seed
 - support for match scores (ex 3-1)
 - player placing when bracket is complete
 - bracket saving/loading
 - reseeding players in losers to avoid rematches

### What it will never do
 - manage setups / timeslots etc.
 - support other formats like round robin

### Dependencies
Python==3.6.1

wxPython==4.0.0a2

Pillow==4.1.0

Other versions may work but are untested.

### Screenshots
The gui
![Gui](/docs/examples/gui.png?raw=true "GUI")


full screenshots of a triple elimination bracket

Winners Bracket
![Winners bracket](/docs/examples/winners.png?raw=true "Winners Bracket")
Losers Bracket
![Losers bracket](/docs/examples/losers.png?raw=true "Losers Bracket")
Losers 2x Bracket (when a player loses in losers bracket)
![Losers 2x bracket](/docs/examples/losers2x.png?raw=true "Losers 2x Bracket")
Finals Bracket (when there is 3 players left, similar to Grand Finals)
![Finals bracket](/docs/examples/finals.png?raw=true "Finals Bracket")
