# sima_boggle
## Function:
For a round of Boggle: to check the validity of each player's words, score their respective lists, and declare a winner. 

__Thoughts behind how I'm going to get this to work:__

After a game of Boggle, the user will:
- input the letters used in the round of boggle from left to right, top to bottom
- input the number of players that round

The program will then prompt each user to input their words in a comma separated list. The program will compare each word of a player to the other players' lists. If the word belongs to more than half of the players, it gets removed from all lists containing the word. If not, the word is searched for in the Merriam Webster Dictionary. If that word exists, the points gained from that word (based on the word's length) are added to each player that has that word to their respective total score. 

[Rules of Boogle](https://www.fgbradleys.com/rules/Boggle.pdf)

__Class ideas:__
- Matrix
- Array List
- Score
- Initial Prompted Input
## Completed Features:
## Features in Progress:
## Future Features:
## Questions & Recommended Help:
- How can I make this more user friendly?
- What should each of my classes entail?
- How do I search the Merriam Webster Dictionary for the word? How do I rule out all informal or archaic words?
  - A potential option: use [this](https://github.com/pfeyz/merriam-webster-api) Python wrapper of the Merrian Webster API. You need to get developer keys from [here](https://www.dictionaryapi.com/) and then take a look at [this](https://github.com/pfeyz/merriam-webster-api/blob/master/examples/define.py) script, which fetches the definition for a given query (or will return `No definitions found for 'word'`). 
