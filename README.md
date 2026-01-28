# Food/Fruit Recognition and Calorie Estimation (2026)

**Project Type:** Computer Vision | AI & Smart Computing
**Goal:** Automate dietary tracking, enhance nutritional monitoring, and simplify personalized health management.

---

## Project Overview

Food/Fruit Recognition and Calorie Estimation is designed to automatically identify different food and fruit types in meal images and estimate their calorie content. This enables:

* Real-time feedback on daily intake
* Improved dietary choices for weight management or specific health conditions
* Long-term monitoring of consumption patterns

For example, a user or health specialist can simply take a photo of a meal, and the system will:

1. Determine whether the image contains **food** or **fruit**
2. Classify the type of fruit or food
3. Estimate calories for accurate dietary tracking

---

## Project Objectives

1. **Image Preprocessing & Feature Extraction:**
   Apply image preprocessing or feature extraction techniques to improve model accuracy where needed.

2. **Two-Stage Identification:**

   * **Stage 1:** Determine if an image contains **food** or **fruit**
   * **Stage 2:** Classify the specific category of **food** or **fruit**

3. **Stage 1 Classification:**
   Train a classification model to identify whether the given image is **food** or **fruit**.

4. **Stage 2 Classification – Fruit:**
   Train a classification model to determine the **fruit category**.

5. **Stage 2 Classification – Food:**
   Train a **one/few-shot learning model** (e.g., Siamese Network) to recognize **food categories**, enabling adaptation to novel dishes and ingredients.

6. **Binary Segmentation (Fruit):**
   Train a segmentation model to separate **fruit** from the background regardless of type.

7. **Multi-Class Segmentation (Fruit):**
   Train a multi-stage segmentation model to classify each pixel into **31 classes**:

   * Background
   * 30 different fruit categories

---


Link of Full Code :
https://github.com/FatmmaELZahraa/Computer-Vision


Link of Dataset :
https://cisasuedu-my.sharepoint.com/personal/hossamsherif_cis_asu_edu_eg/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fhossamsherif%5Fcis%5Fasu%5Fedu%5Feg%2FDocuments%2FProject%20Data%2Erar&parent=%2Fpersonal%2Fhossamsherif%5Fcis%5Fasu%5Fedu%5Feg%2FDocuments&ga=1
---

