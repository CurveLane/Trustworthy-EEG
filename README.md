## Trustworthy AI + EEG Papers

---

### 1. EEG + Trustworthy Papers

These papers combine EEG-related tasks with trustworthy AI methods, including Dongrui Wu's work and others. They are categorized by their function:

---

## EEG + Trustworthy Papers Overview

| **Category**          | **Paper Title**                                                                  | **Description**                                                                                                               | **Publication (Year)**           |
|-----------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| **Privacy**           | **User Identity Protection in EEG-Based Brain–Computer Interfaces**               | Introduces error-minimizing perturbations to anonymize EEG data by removing user identity features while preserving task performance. | *IEEE Transactions on Neural Systems and Rehabilitation Engineering* (2023) |
| **Privacy**           | **Protecting Multiple Types of Privacy Simultaneously in EEG-Based BCIs**          | Develops a method to safeguard multiple private attributes, including identity, gender, and BCI-experience, without affecting primary BCI task accuracy. | *arXiv preprint* (2023) |
| **Security**          | **On the Vulnerability of CNN Classifiers in EEG-Based BCIs**                     | Investigates White/Grey/Black box adversarial attacks using unsupervised FGSM, highlighting vulnerabilities in CNN-based EEG classifiers. | -                                |
| **Security**          | **White-Box Target Attack for EEG-Based BCI Regression Problems**                 | Utilizes modified CW and FGSM techniques to perform white-box attacks on regression models such as Ridge regression and MLP.   | -                                |
| **Security**          | **Universal Adversarial Perturbations for CNN Classifiers in EEG-Based BCIs**     | Proposes a real-time adversarial attack method using DeepFool to generate perturbations that mislead CNN classifiers.          | -                                |
| **Security**          | **EEG-Based Brain–Computer Interfaces are Vulnerable to Backdoor Attacks**        | Demonstrates the feasibility of poisoning attacks that implant backdoors in EEG models using unsynchronized narrow pulse perturbations. | -                                |
| **Security**          | **Active Poisoning: Efficient Backdoor Attacks on TL-Based Brain-Computer Interfaces** | Examines the security risks in Transfer Learning for EEG BCIs by selectively poisoning source-domain data to embed backdoors.  | -                                |
| **Security**          | **Adversarial Robustness Benchmark for EEG-Based Brain–Computer Interfaces**      | Establishes a comprehensive benchmark for evaluating adversarial defenses in EEG-based BCIs using multiple convolutional neural networks. | -                                |
| **Security**          | **SSVEP-Based BCIs are Vulnerable to Square Wave Attacks**                        | Introduces a practical adversarial attack using square wave signals to mislead SSVEP-based BCIs, exposing critical security flaws. | -                                |
| **Security**          | **Adversarial Artifact Detection in EEG-Based Brain-Computer Interfaces**          | Investigates adversarial detection mechanisms for EEG BCIs, showing effectiveness against white-box and black-box attacks.     | -                                |
| **Review Paper**      | **Adversarial Attacks and Defenses in Physiological Computing: A Systematic Review** | Provides a detailed review of adversarial attack strategies and defense mechanisms in physiological computing, with a focus on EEG systems. | -                                |

---

## Trustworthy Methods Overview

| **Category**           | **Paper Title**                                                          | **Description**                                                                                              | **Attack Type / Defense**                | **Publication (Year)**         |
|------------------------|--------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|------------------------------------------|--------------------------------|
| **Adversarial Attack** | **Intriguing Properties of Neural Networks**                             | Investigates the vulnerability of neural networks to small adversarial perturbations using **L-BFGS optimization**. | **Adversarial Attack**                   | *ICLR (2014)*                   |
| **Adversarial Attack** | **Towards Evaluating the Robustness of Neural Networks**                  | Proposes the **CW attack** method for generating imperceptible adversarial examples that mislead neural networks.   | **Adversarial Attack**                   | *IEEE Symposium on Security and Privacy (2017)* |
| **Black-Box Attack**   | **Practical Black-Box Attacks against Machine Learning**                  | Demonstrates black-box adversarial attacks using **training sample augmentation** and transferability.             | **Black-Box Attack**                     | *ASIA CCS (2017)*               |
| **Adversarial Attack / Defense** | **Towards Deep Learning Models Resistant to Adversarial Attacks** | Introduces **Projected Gradient Descent (PGD)**, a powerful iterative method to find adversarial examples by maximizing loss. | **Adversarial Attack / Defense**          | *ICLR (2018)*                   |
| **Privacy Defense**    | **Unlearnable Examples: Making Personal Data Unexploitable**             | Proposes **error-minimizing perturbations** that make personal data unlearnable, preventing exploitation and ensuring privacy. | **Privacy Defense**                      | *ICLR (2021)*                   |

