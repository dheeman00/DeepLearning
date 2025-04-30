# 📁 MNIST Test Dataset Overview

This repository includes the following binary files from the MNIST handwritten digit dataset:

---

## 🖼️ `t10k-images-idx3-ubyte`

- **Purpose**:  
  Contains the **test images** — grayscale handwritten digits.

- **Format**:  
  Binary file with **10,000 images**, each of size **28×28 pixels**.

- **Structure**:
  - **Header** (16 bytes):
    - `0–3`   → Magic number (always `2051` for image files)  
    - `4–7`   → Number of images (`10,000`)  
    - `8–11`  → Number of rows (`28`)  
    - `12–15` → Number of columns (`28`)  
  - **Data**:
    - Each pixel stored as **1 byte** (`0–255`), arranged row-wise.  
    - Each image uses **784 bytes** (`28 × 28`), uncompressed.

---

## 🏷️ `t10k-labels-idx1-ubyte`

- **Purpose**:  
  Contains the **labels** for the 10,000 test images.

- **Format**:  
  Binary file storing integer class labels from `0` to `9`.

- **Structure**:
  - **Header** (8 bytes):
    - `0–3` → Magic number (`2049` for label files)  
    - `4–7` → Number of labels (`10,000`)  
  - **Data**:
    - **1 byte per label**, each corresponding to a test image.
