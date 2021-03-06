# Bracket Program 5000
A tournament bracket software supporting arbitrary high elimination.
meaning it supports triple elimination, quad elim etc as well as single & double.

### What it does
 - bracket generation and viewing
 - supports arbitrarily high elimination
 - match reporting
  - projected bracket by seed
  - bracket saving/loading
  - player placing when bracket is complete
  - avoiding rematches in losers bracket when possible
  
### What it doesn't do (yet)
 - support for match scores (ex 3-1)
 - easily reorder participants

### What it will never do
 - manage setups / timeslots etc.
 - support other formats like round robin

### Dependencies
Python==3.6.1

wxPython==4.0.0a2

Pillow==4.1.0

NOTE: Pillow >= 4.2 is broken because of https://github.com/python-pillow/Pillow/issues/2614. if you encounter this problem, downgrading pillow to an older version will work. Supposedly this has been fixed in future versions (I am not sure which version it is fixed in however)

Other versions may work but are untested.

### Screenshots
The gui
![Gui](docs/examples/gui.png?raw=true "GUI")


full screenshots of a triple elimination bracket

Winners Bracket
![Winners bracket](docs/examples/winners.png?raw=true "Winners Bracket")
Losers Bracket
![Losers bracket](docs/examples/losers.png?raw=true "Losers Bracket")
Losers 2x Bracket (when a player loses in losers bracket)
![Losers 2x bracket](docs/examples/losers2x.png?raw=true "Losers 2x Bracket")
Finals Bracket (when there is 3 players left, similar to Grand Finals)
![Finals bracket](docs/examples/finals.png?raw=true "Finals Bracket")
