# Natural Language Processing with Probabilistic Models

# Week 01  
Auto correct is an application changes misspelled words into correct ones  
e.g. Happy birth day <u>deah</u>!  
    deah->dear  
How dose it work?  
1- identify the misspelled word  - deah   
2- find strings n edit distance away - _\_eah_  /  _d_ar_ /  _de_r_   
3- filter candidates -  (find words that may be instead of it [dear,dean,etc..] )  
4- calculate word probabilities? Which is most probably to be there.

## Building a model  
### 1- identify the misspelled word? HOW  
.. check if word is not in the dict of words.  
```python  
if word not in vocab: # deah
	misspelled = True # deah is misspelled
```
### 2- Find strings n edit distance away   
edit distance of 1/2/3/..  
how many operations done to convert string to another  
#### Operations :
1- (remove a letter) e.g.  `hat` : `at` , `ha` , `ht`  
2- (insert a letter) e.g.  `to` : `top` , `two`  
3- (switch 2 adjacent letters) : remove+insert e.g. `eat` : `ate`,`tea`  
4- (replace  change 1 letter to another) e.g. `jaw` : `jar` , `paw`  
Summarize of operations (insert, remove, switch, replace) 4 operations.  
by combining those operations you can find a number [n] of edits for each string.
for auto correct n is one to three edits  
### 3- Filter candidates 
such as step no.1 check each word you got from the operations you made to get several combination of possible words and check each of them is it in the vocab/dict or not!
### 4- Calculate the probabilities  
