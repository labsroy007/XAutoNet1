# XAutoNet
The purpose of this work is to predict onset of sepsis in ICU patients 6 hours before using their physiological data and to provide diagnostic maps to clinicians or doctors for assisting them in making decisions. <br/>
The main contribution of this paper are listed below-
*	Developing a highly accurate predictive model to identify patients with sepsis at an early stage by taking a minimal number of features as input.
*	Considering the complexity of EMR data of ICU patients, a novel CNN-based autoencoder is introduced for extracting useful information, which is appropriately utilized by the model, helping it classify better.
* Implementation of proper and detailed pre-processing of data to retain important information as it belongs to critical care patients.
* Use of GradCAM for explaining the feature extraction process by Autoencoder and SHAP for digging out the hidden reasons behind the model's prediction.

For a quick walk through of our project we are providing a graphical abstract that will help you understand each process.</br>
 ![Graphical Abstract1](https://user-images.githubusercontent.com/63040034/224906743-8c0dab11-1521-4a23-b89f-12cbdef5e922.png)
</br>
The repository consists of files which are used for data analysis, data cleaning, dimensional reduction using Autoencoder and explainability files (follow the commit message of each .ipynb file).
* File 1, File 6 and File 7 are used for EDA and data cleaning.
* File 2 is the XAutoNet model stored in .h5 extension.
* File 3, File 4 and File 5 are used for dimensional reduction using autoencoder, interpretaion of the models along with abalation and comparative study.
</br>
