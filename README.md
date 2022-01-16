# "Hacking" Wordle

The goal is to obtain the best solution in [wordle](https://wordle.danielfrg.com/), the metric that I'm going to use is the **Shannon entropy**.

$$ S = \sum_{i} -p_{i} log_{2}\left ( p_{i} \right ) $$
## How Wordle works

The goal of the game is to find the daily word. We have 6 tries and the word lenght is 5 characters.

![alt text](./wordle_image.jpg)

When we make a try every letter is going to be colored, if the color is <font color="green"> green means that the letter is correct </font>, if it is <font color="orange">orange means that the letter is in the word but not in that position</font> and finally if the letter is <font color="grey">grey, the letter is not contained on the word</font>.
