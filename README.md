# A**n Electromyography system for Sitting and Walking Postures**

## Project Description
This project presents an Electromyography (EMG)-based system designed for the classification of sitting and walking postures. The system is a foundational model for lower limb prosthesis, leveraging machine learning techniques to recognize human postures with high accuracy.

## Key Features:
- **Data Collection**: EMG signals are acquired using a 4-channel Clarity Medical EMG machine, capturing muscle activity from the rectus femoris (RF), biceps femoris (BF), vastus medialis (VM), and semitendinosus (ST). 
- **Signal Processing**: Raw EMG data undergoes bandpass filtering (10-200 Hz) and notch filtering (49-51 Hz) to remove noise and enhance signal quality.
- **Feature Extraction**: A combination of time-domain (RMS, MAV, ZC), frequency-domain (mean power, peak frequency), and time-frequency features is used to create a comprehensive feature set.
- **Classification Models**: Machine learning models, including Decision Tree, SVM, KNN, and Random Forest, are trained on the extracted features.
- **High Accuracy**: The Random Forest classifier achieved an accuracy of 99.19%, demonstrating the system’s effectiveness in posture classification.


## Workflow Overview:
1. **EMG Data Acquisition**: Recording muscle activity from subjects performing sitting and walking movements.
2. **Preprocessing**: Noise removal using filters to enhance signal clarity.
3. **Feature Extraction**: Extracting meaningful features from time, frequency, and time-frequency domains.
4. **Classification**: Training and evaluating machine learning models for accurate posture recognition.

## **Deployment & Future Applications**: This system can be integrated into rehabilitation devices, prosthetics, and assistive robotics.

## 📄 Research Paper
For more details on the methodology, implementation, and results, refer to our research paper:  
[🔗 Click here to read the full paper](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003488682-40/electromyography-based-system-sitting-walking-postures-piyush-deshpande-viraj-deshpande)

## 📜 Citation
If you find this work useful, please cite our paper as follows:

Deshpande, Piyush, and Viraj Deshpande.  
*"An Electromyography Based System for Sitting and Walking Postures."*  
Advances in Computational Intelligence and Its Applications (2024): 313.  

BibTeX format:
```bibtex
@article{deshpande2024emg,
  author    = {Piyush Deshpande and Viraj Deshpande},
  title     = {An Electromyography Based System for Sitting and Walking Postures},
  journal   = {Advances in Computational Intelligence and Its Applications},
  year      = {2024},
  pages     = {313}
}


