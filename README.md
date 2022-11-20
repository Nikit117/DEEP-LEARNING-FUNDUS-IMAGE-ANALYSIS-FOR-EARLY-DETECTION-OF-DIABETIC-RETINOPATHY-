# DEEP-LEARNING-FUNDUS-IMAGE-ANALYSIS-FOR-EARLY-DETECTION-OF-DIABETIC-RETINOPATHY
The main causing of visual loss in the world is diabetic retinopathy. In the initial stages of this 
disease, the retinal microvasculature is affected by several abnormalities in the eye fundus such 
as the microaneurysms and/or dot hemorrhages, vascular hyper permeability signs, exudates, and 
capillary closures. Micro-aneurysm dynamics primarily increase the risk that the laser photo 
coagulation requires progression to the level. Diabetic retinopathy lesions are commonly accepted 
to be reversed and the progression of the retinopathy can only be slower during the early stages of 
the disease. The identification by repeated examination of patients affected of these initial lesions 
(mainly Micro aneurysms and small blood cells) is expected as a new possibility of improving 
retinopathy treatment. Floating and flashes, blurred vision, and loss of sudden vision can be 
common symptoms of diabetic retinopathy
## 1.1 Project Overview
Diabetic Retinopathy (DR) is a common complication of diabetes mellitus, which causes lesions 
on the retina that affect vision. If it is not detected early, it can lead to blindness. Unfortunately, 
DR is not a reversible process, and treatment only sustains vision. DR early detection and treatment 
can significantly reduce the risk of vision loss. The manual diagnosis process of DR retina fundus 
images by ophthalmologists is time, effort and cost-consuming and prone to misdiagnosis unlike 
computer-aided diagnosis systems.
Transfer learning has become one of the most common techniques that has achieved better 
performance in many areas, especially in medical image analysis and classification. We used 
Transfer Learning techniques like Inception V3, Resnet50, Xception V3 that are more widely used 
as a transfer learning method in medical image analysis and they are highly effective.
## 1.2 Purpose
 The Proposed work intends to automate the detection and classification of diabetic
retinopathy from retinal fundus image which is very important in ophthalmology. Most of the
existing methods use handcrafted features and those are fed to the classifier for detection and
classification purpose. Recently convolutional neural network (CNN) is used for this classification
problem but the architecture of CNN is manually designed. In this work, a genetic algorithm based
technique is proposed to automatically determine the parameters of CNN and then the network is
used for classification of diabetic retinopathy. The proposed CNN model consists of a series of
convolution and pooling layer used for feature extraction. Finally support vector machine (SVM)
is used for classification. Hyper-parameters like number of convolution and pooling layer, number
of kernel and kernel size of convolution layer are determined by using the genetic algorithm. The
proposed methodology is tested on publicly available Messidor dataset. The proposed method has
achieved accuracy of 0.9867 and AUC of 0.9933. Experimental result shows that proposed auto
tuned CNN performs significantly better than the existing methods. Use of CNN takes away the
burden of designing the image features and on the other hand genetic algorithm based methodology
automates the design of CNN hyper-parameters.
