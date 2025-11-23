## 🤖 Machine Vision Project: Classification and Object Detection

This repository contains the implementation and resources for two key machine vision tasks: **Image Classification** and **Object Detection**.

---

### 👥 Collaborators

This project was developed in collaboration by the following individuals:

* **Bokor Ámos Márk** (Neptun code: **AAEN0P**)
* **István Gellért Knab** (Neptun code: **BWKUGQ**)

---

### 📝 Project Overview

This repository focuses on applying and implementing machine learning techniques to solve two fundamental problems in the field of computer vision.

#### **Task 1: Image Classification**

<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.superannotate.com%2Fblog%2Fimage-classification-basics&psig=AOvVaw170Omqbqivo0EDEnSzCKDp&ust=1763989412852000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCNDYteaqiJEDFQAAAAAdAAAAABAE" alt="Image Classification" style="float:right; width:300px; margin-left:20px;">

This task involves training a model to assign a **label** to an entire input image from a predefined set of categories. The goal is to determine **what** is present in the image (e.g., "cat," "dog," "car"). 

**Implementation:** The task was implemented using two different architectures:
* A **custom Convolutional Neural Network (CNN)** model.
* A **Vision Transformer (ViT)**-based solution.

* *Implementation File:* `classification.ipynb`

#### **Task 2: Object Detection**

<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fdeeplobe.ai%2Fexploring-object-detection-applications-and-benefits%2F&psig=AOvVaw0P4jmqgURYv6p0VYTHXx3k&ust=1763989429788000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCNDhne2qiJEDFQAAAAAdAAAAABAE" alt="Object Detection" style="float:right; width:300px; margin-left:20px;">

This task is more complex, as it involves training a model not only to classify objects but also to **localize** them within the image. The output typically includes a **bounding box** around each detected object and its corresponding class label. The goal is to determine **where** objects are and **what** they are. 

**Implementation:** The detection task was also solved using two modern approaches:
* An implementation based on the **YOLO v11** model (You Only Look Once).
* A **Vision Transformer**-based detection solution.

* *Implementation File:* `image_detection.ipynb`

---

### 🚀 Getting Started (Plug and Play)

This project is designed to be **plug and play**. The environment setup and all necessary shell commands are integrated directly within the Jupyter Notebook files.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/istvan-knab/machine_vision_homework_projects.git
    cd machine_vision_homework_projects
    ```
2.  **Open the Notebooks:**
    Launch your Jupyter environment (or use a compatible online platform like Google Colab) and open either `classification.ipynb` or `image_detection.ipynb`.
3.  **Run the Cells:**
    Simply run the cells in the notebook sequentially. The initial cells will automatically execute the necessary **environment setup**, install dependencies, and prepare the software for execution.
