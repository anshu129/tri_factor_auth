# Tri Factor Auth

## Overview

The "Tri Factor Auth" project introduces an advanced authentication mechanism integrating keystroke dynamics and CAPTCHA systems. This solution focuses on distinguishing between human users and sophisticated bots by leveraging human typing behavior and advanced synthetic data generation techniques. The system incorporates cutting-edge methodologies, such as Generative Neural Networks (GNN) and Hidden Markov Models (HMM), to achieve robust bot detection and authentication.

## Key Features

### 1. Keystroke Dynamics-Based Authentication
- **Human-Like Synthetic Data Generation**: Utilizes Generative Neural Networks (GNN) to generate realistic keystroke data, capturing individual typing behaviors and universal patterns.
- **Temporal Dependency Modeling**: Employs Hidden Markov Models (HMM) to capture sequential typing dependencies.

### 2. Multi-Layered Security
- **CAPTCHA Integration**: Enhances traditional CAPTCHA systems by incorporating passive behavioral biometrics.
- **Sophisticated Detection**: Identifies bots trained to mimic human typing patterns using machine learning classifiers like SVM, Random Forest, and LSTM.

### 3. Advanced Synthetic Data Techniques
- **Data Augmentation**: Generates diverse keystroke dynamics datasets to train robust detection models.
- **User-Specific Models**: Supports personalized authentication by modeling individual typing behaviors.

### 4. Scalability and Flexibility
- **Cross-Device Adaptability**: Designed for desktop, mobile, and tablet environments.
- **Language and Regional Independence**: Can be extended to multilingual and multicultural typing patterns.

## Implementation Details

### Technical Methodologies
- **Generative Neural Networks (GNN)**: Creates synthetic keystroke data that mimics human typing behavior.
- **Hidden Markov Models (HMM)**: Captures temporal dependencies in typing patterns to distinguish human and bot behaviors.
- **Long Short-Term Memory (LSTM)**: Models sequential data for accurate bot detection.

### Data Features
- **Hold Latency**: Duration a key is pressed.
- **Inter-Key Latency**: Time interval between consecutive key presses.
- **Press Latency**: Time from a key press to its release.
- **Release Latency**: Time from releasing one key to pressing the next.

## Advantages

1. **Enhanced Security**: Combines biometrics with CAPTCHA for robust authentication.
2. **Realistic Data Simulation**: Produces high-quality synthetic data for training models.
3. **Scalability**: Handles large-scale deployments and diverse datasets.
4. **User-Friendly**: Operates unobtrusively in the background, providing a seamless user experience.
5. **Robust to Attacks**: Resists adversarial attempts and advanced bot evasion techniques.

## Applications

- **Secure Web Authentication**: Enhances login systems with biometric validation.
- **Fraud Detection**: Identifies suspicious activities in financial and e-commerce platforms.
- **Continuous Authentication**: Monitors user behavior for real-time identity verification.
- **CAPTCHA Systems**: Strengthens CAPTCHA challenges against automated bot attacks.

## Future Scope

- **Cross-Platform Integration**: Adapting to various devices and environments.
- **Advanced Privacy Techniques**: Incorporating differential privacy for data protection.
- **Multi-Factor Authentication**: Combining keystroke dynamics with other biometric methods.
- **Global Usability**: Expanding to diverse languages, regions, and cultural typing patterns.

## Research Contributions

- Developed five synthetic data generation methods for keystroke dynamics.
- Designed a robust bot detection framework trained on both real and synthetic data.
- Demonstrated high accuracy using advanced classifiers like LSTM and Random Forest.

## Results

- **High Accuracy**: Achieved up to 100% accuracy in detecting bots using LSTM.
- **Generalization**: Models trained on synthetic data performed effectively across diverse datasets.
- **Robustness**: Resistant to adversarial attacks and advanced bot simulations.

## References

This project builds on extensive research in behavioral biometrics, synthetic data generation, and advanced machine learning methodologies. For a comprehensive list of references, consult the project report.

---

**Contact Information**: For inquiries, reach out to Deepanshu Sharma at [129deepanshusharma@gmail.com].

