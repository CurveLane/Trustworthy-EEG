## Trustworthy AI + EEG Papers

---

### 1. EEG + Trustworthy Papers

These papers combine EEG-related tasks with trustworthy AI methods, including Dongrui Wu's work and others. They are categorized by their function:

---

### 1.1 Privacy

- **Identity Protection**  
  - **User Identity Protection in EEG-Based Brain–Computer Interfaces**  
    *Description*: Uses error-minimizing perturbation to remove user identity while maintaining task accuracy.
  - **Protecting Multiple Types of Privacy Simultaneously in EEG-Based Brain-Computer Interfaces**  
    *Description*: Designs perturbations to protect multiple types of private information, including user identity, gender, and BCI-experience, while maintaining primary BCI task performance. Demonstrates a significant reduction in classification accuracy for private attributes without affecting the main BCI task.

---

### 1.2 Security

- **Adversarial Attacks and Defenses**  
  - **FGSM**
    - **On the Vulnerability of CNN Classifiers in EEG-Based BCIs**  
      *Description*: Explores White/Grey/Black box attacks using unsupervised FGSM. This is an early work by Dongrui Wu and his students.
  - **CW Attack**
    - **White-Box Target Attack for EEG-Based BCI Regression Problems**  
      *Description*: Utilizes modified CW and FGSM methods for white-box attacking regression models like Ridge regression and MLP.
  - **DeepFool**
    - **Universal Adversarial Perturbations for CNN Classifiers in EEG-Based BCIs**  
      *Description*: Uses DeepFool-modified method to create real-time adversarial perturbations for EEG-based CNN classifiers.
  - **Poisoning Attack & Backdoor**
    - **EEG-Based Brain–Computer Interfaces are Vulnerable to Backdoor Attacks**  
      *Description*: Proposes using narrow period pulse for poisoning attacks to create backdoors in EEG-based BCI models. The backdoor key does not need to be synchronized with the EEG trials, making it easy to implement.
    - **Active Poisoning: Efficient Backdoor Attacks on Transfer Learning-Based Brain-Computer Interfaces**  
      *Description*: Explores backdoor attacks in Transfer Learning for EEG-based BCIs by actively poisoning source-domain data with specific patterns. It targets TL models to embed backdoors while maintaining high performance on benign samples, exposing a serious security risk in BCIs.
  - **Adversarial Defense Benchmark**
    - **Adversarial Robustness Benchmark for EEG-Based Brain–Computer Interfaces**  
      *Description*: Explores multiple classical and state-of-the-art adversarial defense approaches in EEG-based BCIs. Establishes a comprehensive benchmark on adversarial robustness for EEG-based BCIs, focusing on convolutional neural networks and EEG datasets.
  - **Square Wave Attack**
    - **SSVEP-Based Brain-Computer Interfaces are Vulnerable to Square Wave Attacks**  
      *Description*: Proposes using square wave signals as adversarial perturbations to attack SSVEP-based BCIs. These perturbations are easy to generate and apply, and can mislead the classifier into any target class. This exposes a significant security vulnerability in SSVEP-based BCIs.
  - **Adversarial Artifact Detection**
    - **Adversarial Artifact Detection in EEG-Based Brain-Computer Interfaces**  
      *Description*: Explores adversarial detection techniques for EEG-based BCIs. Verifies the effectiveness of multiple detection approaches against both white-box and black-box attacks, showing that white-box attacks are easier to detect.

---

### 1.3 Review Papers

- **Systematic Review**  
  - **Adversarial Attacks and Defenses in Physiological Computing: A Systematic Review**  
    *Description*: A comprehensive review of adversarial attacks and defenses in physiological computing, focusing on EEG and other physiological signals.

---

### Notes

- All papers are under the **EEG + Trustworthy** category as they combine EEG tasks with trustworthy AI methods.
- Descriptions are added for better understanding and categorization.
- Make sure to organize the files in the corresponding folders in your local or GitHub repository.
