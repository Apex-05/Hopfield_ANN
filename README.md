# ANN with Hopfield Layer Integration

**Note:**
- Incomplete Project  
- Future work may correct the Hopfield layer instability and enable proper adversarial testing.


This project explores integrating a **Hopfield layer** into a standard **Artificial Neural Network (ANN)** for image classification using the **MNIST dataset**.
The goal was to test whether Hopfield-based associative memory could improve model accuracy and robustness against adversarial attacks.

### What Was Implemented

* Baseline ANN using **PyTorch**.
* Hopfield-augmented ANN using the **hflayers** library.
* Training and evaluation on **MNIST**.
* Attempted **adversarial robustness testing** with **Foolbox**.

### What Did Not Work
* **Hopfield layer** integration caused unstable gradients and inconsistent training results.
* **Foolbox adversarial testing** did not run successfully due to compatibility issues with PyTorch.
### Summary

The baseline ANN trained and performed well (~97% accuracy), while the Hopfield-integrated model showed no clear improvement and was harder to train.
Adversarial robustness evaluation remains incomplete due to library conflicts.


