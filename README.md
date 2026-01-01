# Classification-of-EMG-Signals

EMG Signal Classification for Robotic Arm and Finger Movement Control

Project Description
This project focuses on the classification of surface electromyography signals acquired from the human forearm to enable accurate control of robotic arm and finger movements. The objective is to decode neuromuscular activity generated during different hand and finger motions and translate it into reliable robotic control commands. The work demonstrates the feasibility of EMG-based human–machine interfaces for applications in prosthetics, rehabilitation, and assistive robotics.

Project Objectives
The objectives of this project are to acquire multi-channel forearm EMG signals, preprocess the data to reduce noise and artefacts, extract meaningful features from the EMG signals, classify hand and finger movements using supervised machine learning techniques, and map the classified movements to robotic arm and finger actions.

System Overview
Surface EMG electrodes are placed on forearm muscles to capture muscle activity during predefined hand and finger movements. The recorded signals are filtered, normalized, and segmented into analysis windows. Time-domain, frequency-domain, and statistical features are extracted and used as inputs to supervised classification models. The classifier outputs are then used to generate control commands for robotic arm and finger movements.

Machine Learning Methodology
A feature-based supervised learning approach is used for EMG signal classification. The models are trained to distinguish between different hand gestures, finger movements, and rest states. Performance is evaluated using classification accuracy, confusion matrices, and cross-validation to ensure robustness against EMG signal variability.

Results
The system successfully classified multiple hand and finger movements with reliable accuracy. The results confirm that forearm EMG signals can be effectively used for movement intent recognition and robotic control, supporting real-time human–robot interaction applications.

Tools and Technologies
Signal processing and analysis were carried out using MATLAB and Python. EMG preprocessing techniques included filtering, normalization, and segmentation. Classical supervised machine learning classifiers were employed for movement classification. The system is designed to interface with surface EMG sensors and a robotic arm with finger actuators.

Repository Structure
data contains raw and processed EMG datasets
preprocessing contains signal filtering and segmentation scripts
feature_extraction contains EMG feature computation code
classification contains machine learning models and training scripts
results contains evaluation metrics and visualisations
Thesis_final_Waleed.pdf contains the complete thesis report
README.md contains project documentation

Applications
This work is applicable to myoelectric prosthetic control, rehabilitation and assistive robotics, human–robot interaction, and biomedical signal processing research.

Future Work
Future improvements include deep learning-based EMG classification, subject-independent model generalisation, real-time embedded implementation, and hardware-in-the-loop robotic validation.

License
This project is shared for academic and portfolio purposes. Please cite appropriately if reused.

Author
Waleed Umer
Hamza Shabbir 
Sukaina Najm
Electrical Engineering
