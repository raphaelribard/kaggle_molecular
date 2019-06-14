# kaggle_molecular
Predicting Molecular Properties

The link to the Kaggle competition is:


https://www.kaggle.com/c/champs-scalar-coupling

Tips: 

1.  The public kernels available in the kaggle competition page can provide really interesting ideas to explore: as well you run them in the cloud (Google is behind :-) but don't get too excited : it is only this config:
4 cores / 16 GB RAM / 60 minutes run-time / 1 GB scratch disk space and output);

2.  Read the rules is worth it : just realized we can be only 5 people per team...
    
    You may submit a maximum of 5 entries per day.

    You may select up to 2 final submissions for judging.
    
    And for the data hungry, be careful:
    
    EXTERNAL DATA

The following provision supersedes General Competition Rule at section 7 C below: You may use data other than the Competition Data (“External Data”) to develop and test your models and Submissions excluding data from quantum mechanics computations made specifically for the competition. However, you will (i) ensure the External Data is available to use by all participants of the competition for purposes of the competition at no cost to the other participants and (ii) post such access to the External Data for the participants to the official competition forum prior to the Entry Deadline.


OBJECTIVE : minimize the Log of the Mean Absolute Error:

              score=1T∑t=1Tlog(1nt∑i=1nt|yi−yi^|)
