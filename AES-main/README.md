# AES Encryption & Decryption on FPGA

## University of Bahrain

### College of Information Technology

#### Department of Computer Engineering

**Prepared by:**
- Ali Hasan Salman (20182813)
- Abdulla Mohamed Hasan (20181332)
- Abdulla Naji Wafed (20186556)

**For:** ITCE 497 Senior Project  
**Academic Year:** 2023-2024 - Semester 1  
**Project Supervisors:** Dr. Reham N. Almesaeed, Dr. Abdulla Ahmed Alasaadi  
**Date of Submission:** 19/12/2023

---

## Abstract

This project focuses on implementing the Advanced Encryption Standard (AES) on a Xilinx Spartan-3AN FPGA. AES is a critical cryptographic method used to protect electronic data. Our implementation showcases the AES algorithm using Verilog, emphasizing speed, throughput, and security.

## Table of Contents

1. [Introduction](#introduction)
2. [Background and Literature Review](#background-and-literature-review)
3. [System Design](#system-design)
4. [System Implementation and Testing](#system-implementation-and-testing)
5. [Conclusion and Future Work](#conclusion-and-future-work)
6. [References](#references)

## Introduction

The Advanced Encryption Standard (AES) is a symmetric-key encryption algorithm widely adopted for securing data. AES operates on fixed-size blocks and offers varying key lengths (128, 192, 256 bits) for different security levels. This project aims to implement an efficient AES encryption and decryption system on an FPGA platform.

## Background and Literature Review

### AES Encryption Algorithm

AES operates on 128-bit data blocks and consists of a series of transformations, including:
- **SubBytes**
- **ShiftRows**
- **MixColumns**
- **AddRoundKey**

Implementing AES on FPGA provides advantages such as high throughput, low latency, and reduced power consumption.

## System Design

### FPGA Technology

We chose the DE10-Lite FPGA model for its flexibility and parallel processing capabilities, which are crucial for cryptographic applications.

### Hardware Selection

The DE10-Lite was selected for its:
- **Processing Power**: Equipped with Cyclone IV FPGA.
- **Versatility**: Supports various communication interfaces.
- **Ease of Development**: Compatible with development tools like Quartus Prime.

## System Implementation and Testing

### Component Selection and Integration

The implementation involved integrating the DE10-Lite FPGA with input/output interfaces and sensors. Key components include modules for each AES transformation.

### Testing Phases and Results

The system was tested for encryption and decryption efficacy. Results indicated high throughput and low latency. Usability testing highlighted system responsiveness and user satisfaction.

## Conclusion and Future Work

The project successfully demonstrated the implementation of AES encryption and decryption on FPGA, achieving significant performance benefits over software-based methods. Future work may explore:
- Portability across different FPGA architectures.
- Support for variable key sizes.
- Integration of additional cryptographic algorithms.

## References

1. Paar, C., & Pelzl, J. (2010). Understanding Cryptography: A Computational Perspective (2nd ed.). Cambridge University Press.
2. Behrooz, M., & Drogovan, M. (2012). High-throughput and area-efficient FPGA implementation of AES encryption algorithm. IEEE Transactions on Very Large Scale Integration (VLSI) Systems, 20(10), 1751-1764.
3. Moradi, A., & Heiskala, J. (2014). Hardware-based AES encryption with low latency and high throughput. In 2014 IEEE International Symposium on Hardware Oriented Security and Trust (HOST) (pp. 66-71). IEEE.

---

Feel free to modify any sections or add specific details relevant to your project! If you need further adjustments or additional sections, let me know!
