# HR-Diagram

Determioning the distance and ages of clusters NGC2243 and NGC6231. 

This reposotory contains:
1. The guide as to which has to be done
2. The jupyter file that contains all the coding 
3. The Final report in which the data analysis was done.

The Guide informs what must be done to achieve the end goal, which is: You use B and V magnitudes for as many stars as possible in an open cluster, and then construct the color-magnitude diagram. This diagram can then be used to determine the distance to and the age of the cluster.

The jupyter file has detailed headlines that informs what the following code section does, the files used was obtainted from a CMD site (http://stev.oapd.inaf.it/cgi-bin/cmd). This site needs various inputs that are described in the guide, when all the needed information is inserted, an .dat file can be downloaded. This file contains various coloums, however we are only intersted in certain coloums. Therefore an dataframe is created such that each colom is indexed, and the unnessacery coloms are dropped.

Then computing and analysis is only done with the relevant coloms, the dataframe contains more than one cluster information, thus it has to be sub-divided into the correct sections.


The final report includes an introduction, methoddology, results, result discussion and an conclusion of all the gatherd data.