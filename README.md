# Wikipedia Bingo
### *The excitement of Wikipedia and the trepidations of Bingo combined into one game!*

Wikipedia Bingo was created for HackSheffield 2018, see https://devpost.com/software/wikipedia-bingo for more.

### Installation

You will need Python installed on your PC.

Download the Git repository [from this link](https://github.com/Gemma-Rate/wikipedia-bingo/archive/master.zip) and extract it.

You'll need certain Python modules installed, listed in `requirements.txt`. If you have pip installed you can run:
```
pip install -r requirements.txt
```

Once thet is done open a terminal and run `python game.py`.


### Goal 
Find all the words in a column or a row to get Bingo! and win the game!

### Rules 
* Type the name of a Wikipedia article which you think will contain some of the words on your Bingo grid.
* If it contains a word that is in the grid, good job! But be careful: Every occurance of the word in the article will be counted.
* If a word is found too many times during the game, the counter will overflow and the word will be replaced! Potentially ruining a nearly finished column or row.

How many wikipedia articles will you need to visit to get Bingo!?

**Note:** There are no losers... but there are winners. Will **you** be at the top of the leaderboard?
