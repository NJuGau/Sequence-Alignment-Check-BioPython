# Sequence-Alignment-Check-BioPython

#Aim:
This code snippet is an experiment to test whether a test dataset is aligned with genomic data from another organism. In this case, we can check the alignment between a test dataset with Influenza A Virus and Zaire Ebola Virus from NCBI.

#Method:
This program works by iterating through all dataset available for both virus dataset and set of test dataset. Then, each test sequence will be locally aligned with both of virus dataset. The best alignment for both viruses will be shown and it will show the verdict. If both percentage is less than 50 percent, then we cannot confidently say that the test data is similar to either of viruses. Next, the better virus alignment will be shown and it can also detect whether a 100% sequence match occurs.

#Future Improvement:
In the future, this program can also be improved to find the similarity more precisely with other sequence alignment method. Moreover, some constraints such as when a sequence cannot be said to be the same as either viruses can be researched further.
