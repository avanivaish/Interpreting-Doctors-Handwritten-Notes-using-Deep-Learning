# Interpreting-Doctors-Handwritten-Notes-using-Deep-Learning
1. Abstract

In today's world, handwriting is still considered an important means of expressing thoughts, ideas, and language. However, medical doctors have long been notorious for their illegible cursive handwriting, making it difficult for patients, pharmacists, and researchers to decipher their notes, lab reports, and prescriptions. According to recent studies [1], this problem has resulted in 7,000 deaths annually in developed countries like the US. The situation could be even worse in developing countries. To address this issue and make doctor's handwriting more accessible to everyone, we propose a model that employs Deep Convolutional Recurrent Neural Networks (DCRNN) to accurately predict and digitize cursive handwriting in medical notes, lab reports, and prescriptions.

2. Introduction
Key words: Data Augmentation, Optical Character Recognition, Bidirectional LSTM, Deep Learning, Prescription

Prescribing medication through handwritten prescriptions is a widely used practice, but it comes with both advantages and disadvantages. One of the major drawbacks is the illegibility of a doctor's handwriting, which often leads to medication errors. These errors can have severe consequences, including adverse effects on a patient's health and, in some cases, even death. Research indicates that the primary reason for doctors' poor handwriting is the pressure they face during busy work hours, peak periods, or due to fatigue.

To mitigate these issues, we propose a system that digitizes a doctor's prescription, making it easier for patients and healthcare professionals to understand. However, developing such a system is not straightforward, as recognizing handwritten characters poses significant challenges. Handwriting can differ widely between individuals and can be influenced by various factors, including multi-orientations, skewness of text lines, overlapping characters, and connected components. As a result, recognizing a particular handwritten character can be a challenging task.

To address this challenge, we will use deep learning models such as CNN, RNN, BLSTM, or Mobilenett, among others. We will determine the best model based on accuracy and use it to accurately predict and digitize the doctor's prescription.


3. Literature Survey

The following is the recent work, which has been carried out on the same cause:
	
Kanchan Keisham et al.[2] proposed the text-lines segmentation based on information energy which is calculated for each and every pixel and for classification and recognition, Artificial Neural Network(ANN) is used. The recognition has an accuracy of 92%.

Nibaran Das et al.[3] used the convex hull algorithm for feature extraction. For one character, total 125 features are computed by using different bays attributes of a convex hull. The experiments are carried out on a dataset of Bangla basic characters and digits.The recognition rate is 76.86% for handwritten Bangla characters and 99.45% for Bangla numerals.

Subhadip Basu et al.[4] used multi-layer perceptrons (MLPs) for classification. To recognize the complex characters, the feature set is designed by using three types of topological features i.e. longest-run features, modified shadow features and octant-centroid features. The experiments are carried out to segment and recognize Bangla characters from handwritten Bangla document.The recognition rate observed with the two-pass approach on the 300 samples is 80.58%.

Namrata Dave et al.[5] discussed various techniques which are used to segment the text-line. Three levels of segmentation i.e. text-line, word and character segmentation are explained. The various factors which affect the segmentation are explored.

Nafiz Arica et al.[6] proposed a segmentation and recognition algorithm, which is used for offline cursive handwriting recognition. For segmentation, first the image is converted into gray scale and then into binary image. Hidden Markov Model (HMM) is used for recognition of the characters .

G. Louloudis et al.[7] discussed various segmentation techniques and levels of segmentation. Hough transform method is used for text-line and word segmentation of cursive characters which are connected to each other. 

4. Existing System

There are a few existing systems that use deep learning techniques to interpret doctor's notes. One example is the "Handwritten Text Recognition for Medical Forms" system, developed by a team of researchers at the University of Michigan[8]. This system uses a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks to recognize handwritten text on medical forms, including prescriptions and medical reports.

Another example is the "Deep Learning Approach for Medical Handwriting Recognition" system, developed by researchers at the National Institute of Technology Karnataka in India [9]. This system also uses a combination of CNN and LSTM networks to recognize handwritten text in medical documents, including doctor's notes and prescriptions.

Both of these systems have shown promising results in accurately recognizing and interpreting handwritten medical text. However, there is still room for improvement in terms of accuracy and speed, and further research is needed to develop more advanced deep learning models for this task.

5. Proposed System

Our proposed system for "Interpreting Doctor notes using Deep Learning Techniques" will use a Bidirectional Long Short-Term Memory (BLSTM) network for recognizing and interpreting handwritten medical text. The BLSTM network is a type of neural network that is capable of capturing both the forward and backward temporal dependencies in a sequence of data, making it well-suited for tasks such as handwriting recognition.

The proposed system will be trained on a large dataset of handwritten medical documents, including doctor's notes, prescriptions, and medical reports. The dataset will be pre-processed to remove noise and artifacts, and the handwritten text will be segmented into individual characters.

The BLSTM network will take the segmented characters as input and output the corresponding recognized characters. The network will be trained using a combination of supervised and unsupervised learning techniques to improve its accuracy and reduce the likelihood of errors.

The proposed system will also incorporate other deep learning techniques, such as Convolutional Neural Networks (CNNs) for feature extraction and Recurrent Neural Networks (RNNs) for sequence modeling.

The ultimate goal of the proposed system is to provide an accurate and efficient solution for interpreting handwritten medical text, which will improve patient safety and healthcare outcomes. The system will be evaluated on a variety of metrics, including accuracy, speed, and robustness, to ensure its effectiveness in real-world applications.

In summary, our proposed system for "Interpreting Doctor notes using Deep Learning Techniques" using Bidirectional LSTM has the potential to significantly improve the accuracy and efficiency of interpreting handwritten medical text, and ultimately improve patient safety and healthcare outcomes.

