# Network-Intrusion-Detection-System
## BUSINESS CONTEXT:
With the enormous growth of computer networks usage and the huge increase in the number of
applications running on top of it, network security is becoming increasingly more important. All
the computer systems suffer from security vulnerabilities which are both technically difficult and
economically costly to be solved by the manufacturers. Therefore, the role of Intrusion Detection
Systems (IDSs), as special-purpose devices to detect anomalies and attacks in the network, is
becoming more important.

The research in the intrusion detection field has been mostly focused on anomaly-based and
misusebased detection techniques for a long time. While misuse-based detection is generally
favored in commercial products due to its predictability and high accuracy, in academic research
anomaly detection is typically conceived as a more powerful method due to its theoretical
potential for addressing novel attacks.

Conducting a thorough analysis of the recent research trend in anomaly detection, one will
encounter several machine learning methods reported to have a very high detection rate of 98%
while keeping the false alarm rate at 1%. However, when we look at the state of the art IDS
solutions and commercial tools, there is no evidence of using anomaly detection approaches, and
practitioners still think that it is an immature technology. To find the reason of this contrast, lots
of research was done done in anomaly detection and considered various aspects such as learning
and detection approaches, training data sets, testing data sets, and evaluation methods

## BUSINESS PROBLEM:
The task to build network intrusion detection system to detect anamolies and attacks in the
network. There are two problems.

1. Binomial Classification: Activity is normal or attack
2. Multinomial classification: Activity is normal or DOS or PROBE or R2L or U2R

Please note that, currently the dependent variable (target variable) is not definied explicitly.
However, you can use attack variable to define the target variable as required

## DATA AVAILABILITY:
This data is KDDCUP???99 data set, which is widely used as one of the few publicly available data sets
for network-based anomaly detection systems.

For more about data: [Click here](http://www.unb.ca/cic/datasets/nsl.html)

### For a more rigorous dive refer to the document [here](https://github.com/roderick0411/Network-Intrusion-Detection-System/blob/main/Hints%20for%20Final%20Projects%20%20-%20Network%20Intrusion%20Detection.pdf)
