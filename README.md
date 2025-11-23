# Evolution of Vision: From CNNs and YOLO to Vision Transformers

## 👥 Collaborators
This project was developed in collaboration by the following individuals:
* **Bokor Ámos Márk** (Neptun code: **AAEN0P**)
* **István Gellért Knab** (Neptun code: **BWKUGQ**)
---
### 📝 Project Overview
Deep learning-based approaches have revolutionized the field of computer vision, achieving unprecedented breakthroughs in recent years. The turning point came in 2012 when AlexNet[^1], a deep convolutional neural network developed by Krizhevsky et al., won the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) by a remarkable margin of over 10 percentage points compared to traditional methods[^2] . This watershed moment demonstrated that deep learning architectures could dramatically outperform hand-crafted feature extraction techniques that had dominated the field for decades. Following AlexNet's success, a cascade of innovations emerged, including deeper architectures like VGG and ResNet, region-based detection methods such as R-CNN and Fast R-CNN, and real-time detection frameworks like YOLO (You Only Look Once). 

More recently, the introduction of Vision Transformers (ViT) has challenged the long-standing dominance of convolutional architectures by applying attention mechanisms originally designed for natural language processing to image understanding tasks. These transformer-based models have shown competitive or superior performance across various benchmarks, suggesting a potential paradigm shift in how we approach visual recognition problems. The evolution from purely convolutional approaches to hybrid and attention-based architectures reflects the field's continuous pursuit of more effective representation learning strategies. Today's state-of-the-art systems combine insights from multiple architectural innovations, leveraging both the spatial inductive biases of CNNs and the flexible attention mechanisms of transformers. This rapid progression has enabled practical applications ranging from autonomous driving and medical image analysis to augmented reality and robotics. 

In this homework project, we explore and compare these paradigm-shifting architectures by implementing both classification and object detection tasks. For image classification, we develop solutions using both a custom Convolutional Neural Network (CNN) and a Vision Transformer (ViT) approach. Similarly, for object detection, we implement and compare YOLO v11, representing the state-of-the-art in real-time convolutional detection, against a Vision Transformer-based detection method. This comparative analysis allows us to empirically evaluate the strengths and trade-offs between traditional convolutional architectures and modern attention-based transformers across fundamental computer vision tasks.

#### **Task 1: Image Classification**

<table>
<tr>
<td width="300">
<img src="https://cdn.prod.website-files.com/614c82ed388d53640613982e/6475ee4ab445d8fcfe8b8c45_what%20is%20image%20classification.webp" alt="Image Classification" width="300">
</td>
<td>

This task involves training a model to assign a **label** to an entire input image from a predefined set of categories. The goal is to determine **what** is present in the image (e.g., "cat," "dog," "car"). 

**Implementation:** The task was implemented using two different architectures:
* A **custom Convolutional Neural Network (CNN)** model.
* A **Vision Transformer (ViT)**-based solution.
* *Implementation File:* `classification.ipynb`

</td>
</tr>
</table>

#### **Task 2: Object Detection**

<table>
<tr>
<td width="300">
<img src="https://deeplobe.ai/wp-content/uploads/2023/06/Object-detection-Real-world-applications-and-benefits.png" alt="Object Detection" width="300">
</td>
<td>

This task is more complex, as it involves training a model not only to classify objects but also to **localize** them within the image. The output typically includes a **bounding box** around each detected object and its corresponding class label. The goal is to determine **where** objects are and **what** they are. 

**Implementation:** The detection task was also solved using two modern approaches:
* An implementation based on the **YOLO v11** model (You Only Look Look Once).
* A **Vision Transformer**-based detection solution.
* *Implementation File:* `image_detection.ipynb`

</td>
</tr>
</table>

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

[^1]: Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). ImageNet classification with deep convolutional neural networks. In *Advances in neural information processing systems* (pp. 1097-1105).
[^2] Szemenyei, M. (2025). Computer Vision Systems - Lecture Notes. Budapest University of Technology and Economics, Department of Control Engineering and Information Technology. https://deeplearning.iit.bme.hu/Public/CVS/notesFull.pdf

