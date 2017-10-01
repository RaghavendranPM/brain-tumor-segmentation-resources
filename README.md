# brain-tumor-segmentation-resources

# TODO
data pre processing, reference:

this uses brats 2013 data, tested and able to correctly process all image data

https://github.com/cvdlab/nn-segmentation-for-lar

tested, doesn't run has bugs, still trying to make this work

https://github.com/naldeborgh7575/brain_segmentation

process our data:

--- convert all chinese character file names to english

--- skull strip

tried this: https://github.com/GUR9000/Deep_MRI_brain_extraction

I don't think this works well with our data, the t2 result is very dark

works well with data from here: https://www.nitrc.org/frs/?group_id=48

I have uploaded results in the predictions folder

Oct 1

Tried Nipype with FSL.BET (Brain Extraction Tool), result uploaded to t2_skull_stripped.nii.gz

works well upon initial inspection

--- downsize x and y dimensions (brats 2013 x,y is 160,216, brats 2015 is 240, 240, ours is 640,640)

--- make more layers, z dimension (brats 2013 had 176 layers, 2015 had 155 layers, ours only 24)

--- then feed all data to the pre-processing pipeline similar to github examples.

# MRI basics
https://www.youtube.com/watch?v=CKbemQBAzUE

# Tutorials
https://blog.dataversioncontrol.com/best-practices-of-orchestrating-python-and-r-code-in-ml-projects-f28f3a879484

# Neuroscience software
http://neuro.debian.net/

https://miykael.github.io/nipype-beginner-s-guide/installation.html

https://miykael.github.io/nipype_tutorial/

# BRATS data
https://www.smir.ch/

# Promising
https://github.com/nilearn/nilearn

https://github.com/Kamnitsask/deepmedic

https://github.com/zsdonghao/u-net-brain-tumor

https://github.com/ellisdg/3DUnetCNN

# Segmentation
https://github.com/fabianbormann/Tensorflow-DeconvNet-Segmentation

https://github.com/naldeborgh7575/brain_segmentation

https://github.com/e271141/BRATS

https://github.com/kaspermarstal/BrainNet

https://github.com/jocicmarko/ultrasound-nerve-segmentation

https://github.com/pietz/brats-segmentation

https://github.com/GUR9000/Deep_MRI_brain_extraction


# Resources
https://github.com/desimone/segmentation-models

https://github.com/madlymissyou/deep-learning-for-neuroimage

https://github.com/jindongwang/transferlearning

https://github.com/dformoso/machine-learning-mindmap

https://github.com/mnielsen/neural-networks-and-deep-learning
