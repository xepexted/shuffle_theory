https://xepexted.github.io/shuffle_theory/
The main basis of shuffle theory is that in a certain amount of times after shuffling a deck one on top of each other, it will ultimately return to its original position. I discovered this after messing around with some cards.



     F(i)={2i−1 if 1≤i≤n/2
      {2(i−n/2) if n/2+1≤i≤n
The function is piecewise (sorry idk how to write it correctly in github)
​	
D: The original deck of cards.
n: The total number of cards in the deck.
d_i: The card at position i in the original deck.
A: The first half of the deck.
B: The second half of the deck.
k: The number of times the Faro shuffle is performed.
i: The original location of the deck
Ex: n=52
D=[1,2,3,…,52] 
A=[1,2,…,26]
B=[27,28,…,52]
F(1)=1, F(2)=3, F(27)=2, F(52)=52
After k=1: D' = [1,27,2,28,…,26,52]
​Split into Side A ([1, 27, 2, ...,]) and Side B ([28, 3, ..., 52])


<img width="456" alt="Screenshot 2025-03-23 at 9 27 36 PM" src="https://github.com/user-attachments/assets/f93f7e81-1fd4-4329-8a28-948ac9ae1db2" />


Visual representation up to 52

DISCLAIMER: I DID NOT MAKE THE WEBSITE, I HAD GROK 3 HELP WITH THE CREATION OF THE SITE
