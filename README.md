# CreditCardRisk_ML-QML
This GitHub repository contains a set of tutorial-style scripts on machine learning and quantum machine learning, specifically tailored for credit card fraud classification. 


The datasets are acquired from  and also a lot of the coding strategies like what kind of classical benchmarks or classical machine learning techniques people use, these kind of things have been learnt from this :, to deal with imbalanced dataset, which is extremely common in rare-event simulation, i.e. those event which happen much frequently and are therefore do not have enough data. Some techniques to handle such datsets : 

The datasets used were sourced from this : [Kaggle repository](https://www.kaggle.com/datasets/mishra5001/credit-card/code). 


Another dataset I used was given in the YouTube video by Karina : https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023/data

I also generated an imbalanced synthetic Dataset, for the purpose of implementing the quantum methods because they were too slow for the large datasets coming from actual fraud detection scenario. 

Many of the coding strategies—such as the selection of classical benchmarks and commonly used machine learning techniques—were inspired by resources like this project:  https://www.kaggle.com/code/kshitijthareja/ml-project-credit-card-fraud-detection, which deals with handling imbalanced datasets. Class imbalance is a frequent challenge in rare-event simulations, where certain outcomes occur so infrequently that there is insufficient data to model them effectively. 

Several techniques for addressing imbalanced datasets were also explored through the following Kaggle notebooks: https://www.kaggle.com/code/kshitijthareja/ml-project-credit-card-fraud-detection, https://www.kaggle.com/code/marcinrutecki/smote-and-tomek-links-for-imbalanced-data, https://www.kaggle.com/code/marcinrutecki/best-techniques-and-metrics-for-imbalanced-dataset.  


These resources were instrumental in shaping the approach taken in this project.


One great resource to understand the difference of various machine learning approaches is available in https://pyimagesearch.com/2024/09/16/credit-card-fraud-detection-using-spectral-clustering/ 

**Review**
One article of great importance : Quantum computing for finance, D. Herman, C. Googin, X. Liu, Y. Sun, A. Galda, I. Safro, M. Pistoia & Y. Alexeev 
Nature Reviews Physics 5, 450–465 (2023). 

**QISKIT**
In this repo, I tried to implement quantum kernel based support vector machines and the variational quantum classifier initially with QISKIT, but as always the case with QISKIT, none of the old things work, lot of deprecations and new modules etc and there is a new QISKIT now : https://pypi.org/project/qiskit/, https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.ZZFeatureMap,  Unfortunately, I did not have the time to go through a lot of documentation to figure everything out.  https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.ZZFeatureMap

**Open-Source GitHub Repo**

These are the resources that were used to create this repo, they have also been referenced inside these python notebooks. 
https://github.com/neuralsorcerer/variational-quantum-classifier/blob/main/main.ipynb
https://towardsdatascience.com/a-simple-introduction-to-quantum-enhanced-svm-bee893a4377c/
https://github.com/nagarx/Quantum-KNN-Classifier-using-Qiskit/blob/main/q-KNN.ipynb
https://www.datacamp.com/tutorial/k-means-clustering-python?


**PennyLane** Tutorials and lectures

https://pennylane.ai/qml/demos/tutorial_kernel_based_training
https://medium.com/@devmallyakarar/quantum-support-vector-machines-qsvm-using-qiskit-eee347e81d83
https://imbalanced-learn.org/stable/introduction.html#problem-statement-regarding-imbalanced-data-sets
SO for the VQC, I shifted to Pennylane : https://pennylane.ai/qml/demos/tutorial_variational_classifier.
https://www.youtube.com/watch?v=GSGM8iV8ZRU

 **D-Wave**
 
 https://www.youtube.com/watch?v=SWW7Gpg30Nw

**Quantum Finance** 

https://www.youtube.com/watch?v=6LITc_Rp5c4

**Swiss Bank** 

https://www.swissbanking.ch/_Resources/Persistent/2/8/0/e/280e835f95ee449a7306046260cb6b0bbd0736b2/Expert%20report%20for%20Quantum%20Computing%20in%20Banking.pdf


