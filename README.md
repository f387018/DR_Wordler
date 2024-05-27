# DR_Wordler
Code for generating guesses to solve NYT's Wordle puzzle

This code uses a dictionary (credit another GIT user)
Dictionary source: # https://github.com/vasu2411/Interactive_Dictionary/blob/master/data.json

The way it works is as follows:
1. When you compile and run it, it generates a first guess and prompt you for feedback
2. Input this guess into the puzzle and see the result
3. Input the "green", "yellow", "black" sequence feedback (for each letter) from the puzzle at the prompt
4. The code generates a new suggestion and prompts you for feedback again. 
5. This repeats for 6 times (as many rows as in Wordle)
