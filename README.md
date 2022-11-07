# Comparative-Analysis-of-Detection-and-Classification-of-Lungs-Cancer
MS Thesis Methodoly and Experiments

====================================================ABSTRACT=================================================

This study holds a comparative analysis of various techniques implemented with various models in order to detect and classify lungs cancer. 
This study has been conducted in order to provide a comprehensive view of performances among different techniques and models of CNN. 
The objective of this study was to explore the potential of CNN as feature extractor as well as classifier. 
In addition to this, it was also aimed to include Radiomics module to compare its results with deep learning techniques. 
The study was divided in three experiments. Each experiment was further divided in four modules. The modules include pre-processing, f
eature extractor, classification and ensemble. For each feature extractor module of each experiment, a separate technique and model of 
CNN are implemented. These include two deep learning methods and Radiomics. The features extracted from these feature extractor modules
are then sent into a classification module. The classification module is same for all the experiments and is a combination of two 
deep learning techniques and models and one standard machine learning classifier. Three results were obtained for each experiment. 
Ensemble technique was applied on these results to bring stability and robustness in the model. 
It was observed that Radiomics should be included, in addition to deep learning techniques for feature extractor as 
it gives quantitative features specific to ROI, if annotations and segmentations are provided.
Deep learning performs exceptionally well even when there are no annotations and segmentations provided. 
It can be used for extracting qualitative features. SVM gives better and stable results in classification t
han deep learning. Ensemble removes variance and brings stability in a model. It gives more reliable results.
Hence, any model which include deep learning and Radiomics as feature extractor, SVM as classifier and then Ensemble 
applied on it would have likely chance to provide best and stable results.  
