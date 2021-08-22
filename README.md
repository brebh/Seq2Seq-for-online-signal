# Seq2Seq-for-Handwriting-recovery

Besma Rabhi National Engineering School of Tunis: Ecole Nationale d'Ingenieurs de Tunis. TUNISIA
# Abstract
Online signals are rich in dynamic features such as trajectory chronology, velocity,pressure and pen up/down movements. Their offline counterparts consist of a set ofpixels. Thus, online handwriting recognition accuracy is generally better than offline. Inthis paper, we propose an original framework for recovering temporal order and penvelocity from offline multi-lingual handwriting. Our framework is based on an integratedsequence-to-sequence attention model. The proposed system involves extracting ahidden representation from an image using a Convolutional Neural Network (CNN) anda Bidirectional Gated Recurrent Unit (BGRU), and decoding the encoded vectors togenerate dynamic information using a BGRU with temporal attention. We validate ourframework using an online recognition system applied to a benchmark Latin, Arabicand Indian On/Off dual-handwriting character database. The performance of theproposed multi-lingual system is demonstrated through a low error rate of pointcoordinates and high accuracy system rate.
# Architecture
![image](https://user-images.githubusercontent.com/23113833/119678842-c60ab000-be37-11eb-953c-f720fccd8e87.png)

# Citation

If you find this article useful in your research, please consider citing:
Rabhi, Besma; Elbaati, Abdelkarim; Boubaker, Houcine; Alimi, Adel M. (2020): Temporal Order and Pen Velocity Recovery for Character Handwriting Based on Sequence to Sequence Gated Recurrent Unit Model. TechRxiv. Preprint. https://doi.org/10.36227/techrxiv.13072193.v1 

# Notes
Inside test folder, you find the .ipynb file to test the framework based on the models puted on the folder model.
Just you change the adresse files. For example the variable Save_folder contains the folder of the predicted signal.
the variable model_train_path contains the trained model
the offline handwriting to be recovered must be on the folder redraw.

# Models
you can access to our drive that contain the third model which is a big file.
Link : https://drive.google.com/file/d/1Pv1Mp3-N-zmV3cmAXWBACQnkhk2fB3pu/view?usp=sharing&fbclid=IwAR3LAltSY31gkojeRANXqy3_e4Xt9e4YLRaeN17PVLwaTrsJk8jMg3LPfxk
