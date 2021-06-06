All code for the original LXMERT can be downloaded using this link: https://github.com/airsplay/lxmert.

1. Folders "1img_model" and "3img_model" only contain files of the original LXMERT model that were modified for our datasets. 

2. Folder "attention_scores_extraction" contains only the files of the original model, that were modified for extracting attention matrices from all of the LXMERT's attentive layers.

3. Folder "extract_visual_feats" contains the file for running the visual feature extraction from our images for LXMERT, with the correctly modified Makefile.config for the caffe version used in the bottom-up-attention model. 
The file should be copied into the following folder of the model's project: https://github.com/peteanderson80/bottom-up-attention/tree/master/caffe.
