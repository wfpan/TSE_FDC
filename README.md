# TSE_FDC
This is the replication package for our work submitted to IEEE Transactions on Software Engineering, i.e., Weifeng Pan, Tian Wang, Hua Ming, Dae-Kyoo Kim, Zijiang Yang. XXXX. IEEE Transactions on Software Engineering, 2021, submitted. [[PDF](#)]

# FLSN
This directory contains the FLSN that we built for classes in three subject systems. To reduce the number of FLSN files for a specific subject system, we store the FLSN for all classes in a file, i.e., we build the weighted directed software network at the feature level for a specific system. Thus, to produce the FLSN for a specific class, you should use the naming system of a class in Java programming language and filter out the features that do not belong to the same class. Further, the software network in this directory is weighted and directed. Thus, when building the FLSN, you should neglect the direction and compute the sum of weight on both direction as the new weight on the edge between two features.

Each file has the following format:<br/>
*Vertices node-number<br/>
node-index-1 node-name-1<br/>
node-index-2 node-name-2<br/>
.....<br/>
node-index-node-number node-name-node-number<br/>
*Arcs<br/>
node-index node-index weight<br/>
.....<br/>

Note that we only provide the data for three subject systems; the whole data set will be available after our work's acceptance. Of course, interested readers can email us (Email: wfpan@zjgsu.edu.cn) to get the whole data set in advance. Please use your institutional email address.

# RQs
RQ1: This directory contains the experiments results that we used for answering RQ1.<br/>
RQ2: This directory contains the experiments results that we used for answering RQ2.<br/>
RQ3: This directory contains the experiments results that we used for answering RQ3.<br/>
RQ4: This directory contains the experiments results that we used for answering RQ4.

# Source Code
This directory contain the scripts to perform the experiments in RQ4, i.e., the code to build the prediction models. 

The software, SNAP, used to obtain the FLSNs for classes now is only obtained on request. Interested readers can obtain SNAP by emailing us (Email: wfpan@zjgsu.edu.cn).

# Cite our work
If you use our data set or tool, please cite our work.

Weifeng Pan, Tian Wang, Hua Ming, Dae-Kyoo Kim, Zijiang Yang. XXXX. IEEE Transactions on Software Engineering, 2021, submitted. [[PDF](#)]
