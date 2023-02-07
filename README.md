# Pineapple


The library for scalable and enriched max-p regionalization.

## Modules

###PRUC
###SMP
###EMP

## How to use

###EMP
The implementation of the FaCT algorithm has been packaged into the EMP.jar package. It is assumed that the data required for the experiments is in the directory ./data. To run the experiments, use the command:
```
java -jar EMP.java
```
The 10 experiments described in the experiment section for the EMP problem will be carried out one by one.

To reproduce the results about the impact of the threshold value and scability for the MP-regions implementation, use the command:
```
java -jar MP.java
```