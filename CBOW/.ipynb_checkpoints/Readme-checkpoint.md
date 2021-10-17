## CBOW (Continuious Bag Of Words)
The CBOW model architecture tries to predict the current target word (the center word) based on the source context words (surrounding words). Considering a simple sentence, “the quick brown fox jumps over the lazy dog”, this can be pairs of (context_window, target_word) where if we consider a context window of size 2, we have examples like ([quick, fox], brown), ([the, brown], quick), ([the, dog], lazy) and so on. Thus the model tries to predict the target_word based on the context_window words.


In this noetbook we have tried to implement the CBOW model architecture on wiki dataset from kaggle
the link to dataset ---> https://www.kaggle.com/rohitgr/wikitext