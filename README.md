# EEG-Data-Analysis

This research explores the development and analysis of a hybrid EEG-based model
 combining Wavelet and Fourier transforms with Generative Adversarial Networks
 (GANs) for effective classification of mental states. EEG data, featuring both task
based (math) and relaxation states, were processed and enhanced through feature
 engineering using Wavelet and Fourier transformations, allowing for the extraction of
 relevant frequency and power characteristics. A comprehensive dataset was constructed
 by merging EEG data and subject metadata, followed by label encoding and one-hot
 encoding of categorical attributes to enhance classification performance.
 To address class imbalances and enhance the model's robustness, a GAN was
 employed, leveraging a generator to create synthetic data representations and a
 discriminator to classify real versus generated data. The discriminator was further
 adapted for binary classification of mental states, achieving notable accuracy in
 distinguishing task-based (math) versus relaxation states. The proposed model
 demonstrates the utility of hybrid spectral feature extraction and GAN-based data
 augmentation in EEG classification tasks, offering potential for applications in real
time mental state monitoring and neurofeedback systems.
