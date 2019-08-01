# SubForkNet
(to be updated...)

Copyrights (c) 2019, Essam Rashed 
(essam.rashed@nitech.ac.jp), NITech, Nagoya, JP 

This code aims at mapping T1-w MRI image with segmented labels of different deep brain structures. The design of SubForkNet is based on unified encoders and individual decoders. This implementation is for SubForkNet (N=7, D=2) to segment brain deep regions. However, it can be easily extended to arbitrary any N and D.
 
This code is compatable with Mathematica 12.0 and byond and tested over Windows 10 and Ubuntu 18.04. More details are in our paper mentioned below. If you are using this code, please refer to our paper.

-> Input images are in MATLAB "*.mat" formats for easy use 
-> To Run Select Evaluation -> Evaluate Notebook 

-----------------------------------------------------
"SubForkNet4.nb"

This notebook will train the SubForkNet architecture to segment MRI head image into segmented structures. 
Input: MRI image, labels of different structures (in *.mat) formats
Output: Trained Network + loss function (training/validation) values


-----------------------------------------------------
How to use

Open in Mathematica (12.0 or above), Evalute -> Evaluate Notebook
-----------------------------------------------------
Reference

E. A. Rashed, J. Gomez-tames, A. Hirata
"End-to-end semantic segmentation of personalized deep brain structures for non-invasive brain stimulation"
submitted for publication  (Aug. 2019)
