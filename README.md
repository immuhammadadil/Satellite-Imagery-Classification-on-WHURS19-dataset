# Satellite-Imagery-Classification-on-WHURS19-dataset

**Deep Learning classification Model**
This repository contains jupyter notebook for satellite imagery classification using deep learning model "EffecientNet". 
Reference of Effecientnet paper: https://arxiv.org/abs/1905.11946

**Dataset**
The dataset used in this paper is WHU-RS-19 dataset. WHU-RS19 is a set of satellite images exported from Google Earth, which provides high-resolution satellite images up to 0.5 m. Some samples of the database are displayed in the following picture. It contains 19 classes of meaningful scenes in high-resolution satellite imagery, including airport, beach, bridge, commercial, desert, farmland, footballfield, forest, industrial, meadow, mountain, park, parking, pond, port, railwaystation, residential, river, and viaduct. For each class, there are about 50 samples. It’s worth noticing that the image samples of the same class are collected from different regions in satellite images of different resolutions and then might have different scales, orientations and illuminations.

Dataset Link: https://drive.google.com/drive/folders/16a9HRnhd2EcM_4CnCFpQL1xCJFUb6VA6?usp=sharing

Dataset is divided into training and validation data. There are almost 10 validation samples of each class.

**Resuts**
We have achieved the validation accuracy of 93% afer just 20 epochs.
