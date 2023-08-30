# Detecting-Speech-Disorders-and-Determining-their-Severity-for-Treatment-Using-CRNNs-and-Unsupervised

Dysarthria is a common speech disorder that poses a challenge when diagnosing it due to its similarity to other disorders. This project investigates the use of deep learning to detect and rank the severity of dysarthria in an audio clip of a patient speaking. The TORGO database is employed to teach the model, which includes audio clips of speakers, labeled with whether they have dysarthria or not. Unsupervised clustering is used on the positive audio samples to generate severity labels for the samples in the dataset. Audio is preprocessed into mel spectrograms, allowing us to take advantage of conventional image processing techniques. A modified version of a CRNN (convolutional recurrent neural network), is used to extract sequential and image features from the audio. After training, the model is able to detect if an audio clip of a patient's speech is positive or negative for dysarthria, and if positive, it can classify them into one of five treatment groups. The results of this model imply that merging models where LSTM layers and CNN layers process the inputs simultaneously and combine their outputs can be far more effective than having LSTMs process the outputs of CNNs. Furthermore, the use of unsupervised clustering can prove to be effective in labeling unclassified data.


Contributors: Akshay Anand, Vibhor
