# Ensemble of Convolutional Neural Networks for Disease Classification of Skin Lesions
**Problem Statement**: Fully supervised binary classification of skin lesions from dermatoscopic images. 

**Note**: The following approach won 1st place at the **2019 Computer-Aided Diagnosis: Deep Learning in Dermascopy Challenge** at [Universitat de Girona](https://www.udg.edu), during the 2018-20 Joint Master of Science in [Medical Imaging and Applications (MaIA)](https://maiamaster.udg.edu) program.  

**Data**: *Class A*: Nevus; *Class B:* Other (Melanoma, Dermatofibroma, Pigmented Bowen's, Basal Cell Carcinoma, Vascular, Pigmented Benign Keratoses) [4800/1200/1000 : Train/Val/Test Ratio]
 
**Directories**  
  ● Data I/O Functions: `scripts/dataio.py`  
  ● Preprocessing Functions: `scripts/preprocess.py`  
  ● Unsupervised Segmentation Functions: `scripts/segment.py`  
  ● Feature Computation Functions: `scripts/colorfeatures.py`               
  ● Final Feature Extraction Function: `scripts/feature_extraction.py`               
  ● Classifier Support Functions: `scripts/classify.py`  
  ● Inference Pipeline Notebook: `scripts/predict.ipynb`  
  ● Training-Validation Pipeline Notebook: `scripts/train-val.ipynb` 
