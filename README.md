# RIP-REALM
RNA-Interference Prediction based on Regression and Linear Models
The selection of an effective siRNA sequence for optimized systemic silencing remains a major bottleneck for potential applications RNAi-based products in the field (Dalakouras et al., 2018, Schwartz et al., 2020, Hendrix et al., 2021). The role of 22nt siRNA in triggering a systemic RNAi in the whole plant is well documented and requires the action of the RDR6 polymerase that is likely responsible for the amplification, the transitivity, and the systemic spread of RNAi (McHale et al., 2013, Taochy et al., 2017, Chen et al., 2018). However, the recruitment of RDR6 can occur with any-sized sRNA that contains an asymmetric bulge in its duplex structure (Manavella et al., 2012; Dalakouras et al., 2016, 2018). In this context, coupling the increasing genomic resources for fruit trees to the development of robust in silico tools to predict siRNAs species with high silencing efficiency with a systemic potential is a significant priority. Algorithms like Support Vector Machines (SVM) can be trained and tested over a sequence dataset, which has already been experimentally validated. Once the best prediction parameters are set up, they can be used to predict siRNAs from long dsRNA sequences. Sequence composition features have historically represented most of the critical features used in the SVM pipeline as di- and tri-nucleotide counts, global and local GC content, duplex flexibility, and thermodynamics stability (Sciabola et al., 2021; Shabalina et al., 2006). But recent studies have demonstrated the pivotal role of the target accessibility and siRNA 5’ composition for incorporating into the Argonaute (AGO) protein active site as essential criteria to assess the silencing property of the siRNA sequence (Gago-Zachert, 2019). 
Recently developed  in silico tools have strategized a hybrid-SVM-based prediction based on efficacy scores from previously designed models (nonspecific and toxic siRNAs removal, intended versus unintended target transcripts, RISC loading efficacy of the siRNA, target site accessibility, highly specific siRNA) combined with training datasets (siRNA) that had empirically demonstrated efficacious systemic silencing of predicted siRNA (Ahmed et al., 2020). A correlation coefficient greater than 0.7 between the measured and predicted efficacy of the siRNA candidate was observed, here we are trying to do best.
