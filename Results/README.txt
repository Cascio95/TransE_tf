BATCH100 folder doesn't contain the results for
batch size=100, but it contains the results for
TransE without checking the corrupted triplets 
before the epoch, batch size=300.

BATCH300 contains the results for
TransE with a check on the corrupted triplets 
before the epoch, batch size=300.