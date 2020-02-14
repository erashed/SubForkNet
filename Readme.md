# SubForkNet

Copyrights (c) 2019, Essam Rashed 
(essam.rashed@nitech.ac.jp), NITech, Nagoya, JP 

This code aims at mapping T1-w MRI image with segmented labels of different deep brain structures. The design of SubForkNet is based on unified encoders and individual decoders. This implementation is for SubForkNet (N=7, D=2) to segment brain deep regions. However, it can be easily extended to arbitrary any N and D.
 
This code is compatable with Mathematica 12.0 and byond and tested over Windows 10, Ubuntu 18.04 and OSX 10.11.6. More details are in our paper mentioned below. If you are using this code, please refer to our paper.

-> Input images are in MATLAB "*.mat" formats for easy use 

-> To Run Select Evaluation -> Evaluate Notebook 

-> If you are not familier with Mathematica Notebooks (*.nb), you can download free reader from here: http://www.wolfram.com/cdf-player/

"SubForkNet.nb"

This notebook will train the SubForkNet architecture to segment MRI head image into segmented structures. 
Input: MRI image, labels of different structures (in *.mat) formats
Output: Trained Network + loss function (training/validation) values

"arch**.nb"

These notebooks define different network architectures.

"parameters.nb"

This notebook define the experiment parameters


"Read_train_T1.nb"

This notebook is used to read the network training data (input/target)


"Test_T1.nb" & "Test_All.nb"

These notebooks are used in test the trained network using new subjects



How to use

Open in Mathematica (12.0 or above), Evalute -> Evaluate Notebook




References

* E. A. Rashed, J. Gomez-Tames, A. Hirata,
"End-to-end semantic segmentation of personalized deep brain structures for non-invasive brain stimulation,"
Neural Networks, 2020 (in press)

* E. A. Rashed, J. Gomez-Tames, A. Hirata,
"Development of accurate human head models for personalized electromagnetic dosimetry using deep learning,"
NeuroImage 202, 116132, 2019 (DOI: 10.1016/j.neuroimage.2019.116132)
