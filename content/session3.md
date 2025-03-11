+++
date = '2025-03-03T17:00:00-05:00'
draft = false
title = 'Cyber Physical Systems: Applications in Audiology and Smart Health'
featured_image = 'https://ub-escgroup.github.io/ai-heartech/images/cyber_physical_systems_header.jpg'
+++

## Session Overview

Our third Audiology Workshop featured Alexander Gheardi presenting on Cyber Physical Systems (CPS) with a focus on smart health applications in audiology. This session explored the integration of physical sensors with AI techniques, emphasizing the complete pipeline from data collection to inference in health-related contexts.

## Anatomy of Smart Health Systems

Alexander introduced the fundamental components of cyber physical systems, highlighting their critical role in modern healthcare applications. A complete smart health system consists of four key elements:

{{< figure src="https://ub-escgroup.github.io/ai-heartech/images/cps_anatomy.png" title="Anatomy of a Smart Health System" width="100%" >}}

1. **Physical Sensors**: Devices that capture physiological or environmental data
2. **Data Preprocessing**: Filtering and cleaning techniques to enhance signal quality
3. **Feature/Domain Extraction**: Transformation of raw data into meaningful representations
4. **Inference**: AI models that interpret the features to make predictions or classifications

To illustrate this framework, Alexander demonstrated how a simple optical system using a green LED and photodiode can establish a relationship between photoplethysmography (PPG) signals and cardiac arrhythmia through appropriate preprocessing and AI techniques.

## Sensing Modalities for Health Applications

The presentation covered various sensing modalities applicable to audiology and broader health monitoring:

- **Acoustic**: Active or passive spectrogram analysis
- **Optical**: LED/laser-based measurements or camera imaging
- **Electrical**: Impedance, EEG, ECG, EOG, EMG measurements
- **Movement**: IMU-based motion tracking
- **Ambient**: Temperature, pressure, and environmental sensing

{{< figure src="https://ub-escgroup.github.io/ai-heartech/images/observables.png" title="Observable Physical Characteristics for Health Monitoring" width="100%" >}}

Alexander highlighted several physiological characteristics that can be monitored with these modalities, including:

- Eye measurements (pupil size, ERG, gaze)
- Heart activity (BPM, ECG, PPG)
- Brain activity (EEG)
- Muscle activity (EMG, EIT)
- Skin properties (tissue spectra, moisture, temperature)

## Data Preprocessing Techniques

A significant portion of the presentation focused on preprocessing techniques essential for effective health monitoring systems:

- **Frequency Filtering**: High-pass, low-pass, band-pass, and band-stop filters
- **Blind Source Separation**: PCA and ICA for isolating signals from noise
- **Beamforming**: Directional signal processing (analogous to "pointing the ear")
- **Statistical Approaches**: Moving averages, Wiener filters, and spectral estimation

{{< figure src="https://ub-escgroup.github.io/ai-heartech/images/normalization.png" title="Data Normalization Approaches for Consistent Learning" width="100%" >}}

Alexander emphasized the importance of normalization in preparing data for AI systems, discussing various approaches including max normalization, min-max scaling, and z-standardization. He noted that normalization provides the consistency necessary for effective machine learning, especially when absolute scale is less important than relative patterns.

## Machine Learning Approaches

The presentation covered the spectrum of machine learning approaches relevant to audiology applications:

### Machine Learning vs. Deep Learning

Alexander differentiated between traditional machine learning and deep learning approaches:

- **Traditional ML**: Engineers define simple features, and models learn relationships between these features and targets
- **Deep Learning**: Multi-layered networks learn features and their relationships simultaneously, enabling direct mapping from raw inputs to desired outputs

### Supervised vs. Unsupervised Learning

The discussion included various learning paradigms:

- **Supervised Learning**: Models trained with labeled data (95% of health applications)
- **Unsupervised Learning**: Pattern discovery in unlabeled data
- **Hybrid Approaches**: Combining unsupervised methods for understanding data structure with supervised techniques for targeted outcomes

### Reinforcement Learning for Adaptive Systems

Alexander introduced reinforcement learning as a promising approach for audiology applications, particularly for adaptive sound therapy:

{{< figure src="https://ub-escgroup.github.io/ai-heartech/images/reinforcement.png" title="Reinforcement Learning Framework for Adaptive Sound Therapy" width="100%" >}}

- Systems learn through reward-based feedback
- Particularly useful for optimizing sequences of decisions with long-term outcomes
- Applicable to personalized tinnitus treatment through sound stimulation

## Discussion: Applications in Audiology

The presentation sparked rich discussion about potential applications in audiology:

### Tinnitus Treatment System

Dr. Wei Sun proposed developing a comprehensive tinnitus management system incorporating:
- Matching algorithms to characterize individual tinnitus profiles
- Adaptive sound generation using reinforcement learning
- Monitoring tools to track treatment efficacy

Elizabeth clarified that current tinnitus noise generators primarily aim to distract rather than mask, emphasizing the need for nuanced approaches to sound therapy.

### Objective Response Measurement

The group discussed using multiple sensor types to objectively measure patient responses to audio stimuli:
- EEG for neural response characterization
- Heart rate and galvanic skin response for discomfort assessment
- Pupillometry for cognitive effort measurement

### Over-the-Counter Hearing Aid Programming

The team explored how AI could enhance self-fitting of OTC hearing aids:
- Noise-canceling technology to improve testing accuracy
- Algorithms for appropriate gain selection based on user feedback
- Virtual environments to simulate real-world listening conditions

## Future Directions

The workshop identified several promising research avenues at the intersection of cyber physical systems and audiology:

1. **Multimodal Sensing**: Combining acoustic, physiological, and behavioral measurements for comprehensive assessment
2. **Reinforcement Learning**: Developing adaptive algorithms for personalized sound therapy optimization
3. **Miniaturization**: Creating wearable, unobtrusive monitoring solutions for continuous assessment
4. **Hybrid Learning Models**: Using advanced AI approaches that reduce dependence on large labeled datasets

The next workshop is scheduled for two weeks later and will focus on the integration of these concepts into practical applications for hearing health care.

---

*This seminar series represents a collaboration between the Audiology and AI research groups at our institution. For inquiries about attending future sessions, please contact the department office.*