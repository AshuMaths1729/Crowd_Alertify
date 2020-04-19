# Crowd Alertify
As part of the SAMHAR-COVID-19 Hackathon

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![hackathon](https://img.shields.io/badge/Hackathon-SAMHAR--COVID--19-yellow)](https://samhar-covid19hackathon.cdac.in/)
[![vs-code](https://aleen42.github.io/badges/src/visual_studio_code.svg)](https://code.visualstudio.com/)
[![torch](https://img.shields.io/badge/Build%20with-PyTorch-orange)](https://pytorch.org/)

___

An intelligent system that - 
* Sees and predicts number of people in front of it.
* Alerts if number of people surpass a set threshold.

___

Data on which the model is trained is from ShanghaiTech can be found here:
https://drive.google.com/file/d/16dhJn7k4FWVwByRsQAEpl9lwjuV03jVI/view

Trained Model can be found here: 
https://drive.google.com/file/d/1W58cGbFr2SJvOmBoPu-quIjO5i9g4hFL/view?usp=sharing

Used the state-of-the-art CSRNet to train the model.

MAE recorded is 75%, which can be increased more after more Indian crowd related data, specific to the cause.

___
## To-Do:
* Train on more specific data like video streams, to get better model's performace.
* Use various other hyperparameters involved in the CSRNet.
* Deploy the trained classifier on to a drone or a surveillance camera for implementation.


___
## Team A_Cube
* Ashutosh Agrahari
* Ankur Veer
* Anshuman Singh
