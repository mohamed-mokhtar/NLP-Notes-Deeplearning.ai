# Natural Language Processing with Probabilistic Models
this talk about the second course  
week 01  
Auto correct is an application changes misspelled words into correct ones  
e.g. Happy birth day <u>deah</u>!  
    deah->dear  
How dose it work?  
1- identifiy the misspelled word  - deah   
2- find strings n edit distance away - _\_eah_  /  _d_ar_ /  _de_r_   
3- filter candidtes -  (find words that may be instead of it [dear,dean,etc..] )  
4- calculate word probabilites? Which is most probably to be there.
