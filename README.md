# Seq2Sef-for-Handwriting-recovery

Besma Rabhi National Engineering School of Tunis: Ecole Nationale d'Ingenieurs de Tunis. TUNISIA
# Abstract
Online signals are rich in dynamic features such as trajectory chronology, velocity,pressure and pen up/down movements. Their offline counterparts consist of a set ofpixels. Thus, online handwriting recognition accuracy is generally better than offline. Inthis paper, we propose an original framework for recovering temporal order and penvelocity from offline multi-lingual handwriting. Our framework is based on an integratedsequence-to-sequence attention model. The proposed system involves extracting ahidden representation from an image using a Convolutional Neural Network (CNN) anda Bidirectional Gated Recurrent Unit (BGRU), and decoding the encoded vectors togenerate dynamic information using a BGRU with temporal attention. We validate ourframework using an online recognition system applied to a benchmark Latin, Arabicand Indian On/Off dual-handwriting character database. The performance of theproposed multi-lingual system is demonstrated through a low error rate of pointcoordinates and high accuracy system rate.
# Architecture
![image](https://user-images.githubusercontent.com/23113833/119678842-c60ab000-be37-11eb-953c-f720fccd8e87.png)
