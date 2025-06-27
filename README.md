# Phase 1 - Redundancy Analysis of PRESENT
Present Encrypted Image Classification: S-box Redundancy Analysis

## Project Description
This project implements closed-set classification of CIFAR-10 images encrypted using the PRESENT cipher with modified S-box configurations. The experiment investigates whether **redundancy in the S-box** (specifically, repeating one hexadecimal value twice, thus intentional pertubation in the S-box to eliminate unique values) greatly affects security of PRESENT CIPHER.

## Objective
- **Classify CIFAR-10 images into 4 distinct buckets:**
  1. PRESENT encrypted with standard S-box
  2. PRESENT encrypted with modified S-box 1 (redundancy pattern - Value of 3 replaced with 1)
  3. PRESENT encrypted with modified S-box 2 (redundancy pattern - Value of 3 replaced with 2)
  4. PRESENT encrypted with modified S-box 3 (redundancy pattern - Value of 3 replaced with 5)

- **Analyze how S-box redundancy impacts security of PRESENT CIPHER**

- **Evaluate classification performance using AlexNet and MobileNetV2 architectures**
