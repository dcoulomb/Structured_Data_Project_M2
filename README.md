# Structured Data

This is a master project for the class **Structure Data** hold by Florence d'Alché Buc and Slim Essid at *M2 Data Siences - Université Paris-Saclay*.

We worked on the following article:

Su, H., Heinonen, M., & Rousu, J. (2010, September). Structured output prediction of anti-cancer drug activity. In *IAPR International Conference on Pattern Recognition in Bioinformatics* (pp. 38-49). Springer Berlin Heidelberg. (http://link.springer.com/chapter/10.1007/978-3-642-16001-1_4)

The goal was to implement the methods presented in the paper and to comment the results we obtained. 

## References

To do that, the authors shared with us their work and we used a lot of what they did:

Here is the GitHub repository in reference: https://github.com/hongyusu/Molecular_Classification

The folder /references contains:
- the original matlab code they shared with us
- the article in reference

Thanks a lot to them.

## Files & Folders

- MST_MMCRF.ipynb: implements the Max-margin Conditionnal Random Fields (MMCRF) algorithm to resolve the problem
- SVM.ipynb: implements a Support Vector Machine (SVM) classifier to to resolve the problem
- spanning_tree.py: implements the maximum-weight spanning tree algorithm (open-source code from the 'NetworkX' package: https://networkx.readthedocs.io/en/latest/_modules/networkx/algorithms/tree/mst.html#maximum_spanning_tree)
- /data_clean: contains the dataset used in the above notebooks
- /report: contains our conclusions (based on our own work). It is actually the report that we gave to our Professors
- /references: contains the original MATLAB code from Juho Rousu (Department of Computer Science, Aalto University).

### Special note:

In case you wish to use any of the present material, **please ask the authors to refer to the book chapter (Rousu et al, 2007) introducing MMCRF**.
In order to cite, please refer to: https://scholar.google.fr/scholar?hl=fr&q=Structured+Output+Prediction+of+Anti-cancer+Drug+Activity&btnG=&lr=.


