# present-encrypted-image-classification-using-alexnet-and-mobilenet
Present Encrypted Image Classification: S-box Redundancy Analysis

# Encrypted Image Classification: S-box Redundancy Analysis

## Project Description
This project implements closed-set classification of CIFAR-10 images encrypted using the PRESENT cipher with modified S-box configurations. The experiment investigates whether **redundancy in the S-box** (specifically, repeating one hexadecimal value twice) greatly affects security of PRESENT CIPHER.

## Objective
- **Classify CIFAR-10 images into 4 distinct buckets:**
  1. PRESENT encrypted with standard S-box
  2. PRESENT encrypted with modified S-box 1 (redundancy pattern)
  3. PRESENT encrypted with modified S-box 2 (redundancy pattern)
  4. PRESENT encrypted with modified S-box 3 (redundancy pattern)
- **Analyze how S-box redundancy impacts security of PRESENT CIPHER**
- **Evaluate classification performance using AlexNet and MobileNetV2 architectures**
