# Pavement-Defect-Datasets-Anomaly-Segmentation
Description  
  The pavement defect datasets are used to evaluate anomaly segmentation methods. It cantains three pavement datasets with different texture backgrounds and challenges.   
IPAS dataset  
  The inlaid patch anomaly segmentation (IPAS) dataset is collected on highways. The original images are cropped into 256x256, where 500 non-defective images are randomly selected for training, and 450 non-defective and 150 defective images are utilized for testing. As a common pavement defect, the accurate detection of inlaid patches is significant for pavement assessment. The color and texture of collected inlaid patches share high similarities with the backgrounds. Moreover, there are many interference factors in backgrounds, such as oil, rain stains, road markings, gravel, and fallen paint during patching. These challenges make anomaly segmentation more difficult. By establishing this inter-class ambiguous dataset, we can assess the ability of anomaly segmentation algorithms to reconcile the contradiction between generalization and reconstruction fidelity.  
Crack500 dataset  
  The Crack500 dataset is collected on campus by Yang. et al. [1], containing cement, gravel, and asphalt pavements. In our experiment, the Crack500 dataset is reorganized to construct the anomaly segmentation dataset. The reorganized training dataset comprises 700 non-defective images, and 150 non-defective and 150 defect images are utilized to assess the performance of the detection approaches. The backgrounds of images in this dataset exhibit significant variances, which pose challenges to anomaly segmentation. In addition, the topological structures of the cracks show significant diversity. For example, the shape and width vary randomly.  
GAPs dataset  
  The German asphalt pavement distress (GAPs) dataset [2] contains six types of pavement defects marked with the bounding box, such as cracks, potholes, and mosaic patches. In our implementation, the original images are cropped to 256x256, and then annotated at the pixel level. Finally, the training dataset comprises 700 non-defective images, while the test dataset consists of 150 defective images and 150 non-defective images. The morphologies of defects in this dataset are varied. The holes are mainly round or oval, while the repairs are banded, and the cracks are irregularly linear. In addition, defects such as holes often appear in a small local area.  

Download   
  Please send the registration by eamil to wyanyan@stumail.neu.edu.cn to get the password to unzip the zip file (for academic use only).  






----------
[1] Feature pyramid and hierarchical boosting network  
[2] Improving visual road condition assessment by extensive experiments on the extended gaps dataset
