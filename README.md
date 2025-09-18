<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# BRAIN-TUMOR-CLASSIFICATION-USING-DEEP-LEARNING-TECHNIQUES

<em>Enhancing AI For Medical Imaging</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/license/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
<img src="https://img.shields.io/github/last-commit/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies: Python, Jupyter, Tensor Flow, Keras, VGG19, Open CV</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">

</div>
<br>

---

## 📄 Table of Contents

- [Overview](#-overview)
- [Getting Started](#-getting-started)
    - [Prerequisites](#-prerequisites)
    - [Installation](#-installation)
- [Features](#-features)
- [Project Structure](#-project-structure)
    - [Project Index](#-project-index)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#-license)

---

## ✨ Overview

Brain-Tumor-Classification-Using-Deep-Learning-Techniques is a repository containing a project that automates the process of identifying and categorizing brain tumors from medical images using deep learning models. It provides a complete pipeline—from data preprocessing and augmentation to model training and evaluation—making it easier for researchers and developers to implement accurate tumor classification systems.

**Why use Deep Leanrning to Classify Brain Tumors?**

Medical  image  classification  has  gained tremendous  attention  in  recent  years,  and  Convolutional Neural  Network  (CNN)  is  the  most  widespread  neural network  model  for  image  classification  problem.  CNN  is designed  to  determine  features  adaptively  through backpropagation by applying numerous building blocks, such as  convolution  layers,  pooling  layers,  and  fully  connected layers. In this project, we mainly focused on developing a CNN model for classifying  brain tumors while also using pre trained models like VGG19 for image recognition. 

This project aims to advance medical imaging analysis with deep learning. The core features include:

- 🧠 **🔍 Model Workflow:** Seamlessly integrates data preprocessing, augmentation, and evaluation for end-to-end tumor classification.
- 🖥️ **🧬 Deep Learning Models:** Utilizes frozen convolutional neural networks for reliable and accurate detection. Uses VGG19 for image recognition
- 🚀 **⚙️ Reproducibility:** Provides a clear, extendable pipeline to facilitate research and deployment.
- 💡 **🩺 Healthcare Focus:** Designed to support medical decision-making and healthcare innovation.
- 🎯 **📊 Performance Evaluation:** Includes comprehensive model assessment to ensure robustness and accuracy.
- 📃 **🥼 Project Based on Following Research Paper:** https://www.researchgate.net/publication/338077321_Brain_Tumor_Classification_Using_Convolutional_Neural_Network

---

## 📌 Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>Jupyter Notebook-based workflow for data preprocessing, model training, and evaluation</li><li>Sequential pipeline integrating data loading, augmentation, model definition, training, and testing</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Modular code with separate notebooks for each stage</li><li>Clear variable naming and inline comments</li><li>Use of standard deep learning practices with Keras/TensorFlow</li></ul> |
| 📄 | **Documentation** | <ul><li>Basic README with project overview and dependencies</li><li>Inline markdown cells within notebooks explaining steps</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Uses Python libraries: `tensorflow`, `keras`, `numpy`, `matplotlib`, `sklearn`</li><li>Potential integration with Jupyter Notebook environment for visualization</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separate notebooks for data preprocessing, model training, and evaluation</li><li>Reusable functions for data augmentation and model architecture</li></ul> |
| 🧪 | **Testing**       | <ul><li>Limited formal testing; relies on validation accuracy during training</li><li>Potential for adding unit tests for data processing functions</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Utilizes GPU acceleration via TensorFlow backend</li><li>Model training with batch processing and early stopping</li></ul> |
| 🛡️ | **Security**      | <ul><li>No explicit security features; typical for research notebooks</li><li>Potential improvements include data validation and access controls</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Core dependencies: `jupyternotebook`, `license`, `markdown`</li><li>Deep learning: `tensorflow`, `keras` (implied from context)</li></ul> |

---

## 📁 Project Structure

```sh
└── BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques/
    ├── Brain_Tumor_Classification_Using_Deep_Learning.ipynb
    ├── LICENSE
    ├── README.md
    └── archive.zip
```

---

### 📑 Project Index

<details open>
	<summary><b><code>BRAIN-TUMOR-CLASSIFICATION-USING-DEEP-LEARNING-TECHNIQUES/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques/blob/master/Brain_Tumor_Classification_Using_Deep_Learning.ipynb'>Brain_Tumor_Classification_Using_Deep_Learning.ipynb</a></b></td>
					<td style='padding: 8px;'>- SummaryThis Jupyter Notebook serves as the core component for the brain tumor classification project, demonstrating how deep learning models are applied to identify and categorize brain tumors from medical imaging data<br>- It orchestrates the entire workflow—from data preprocessing and augmentation to model training and evaluation—highlighting the practical implementation of deep learning techniques within the broader project architecture<br>- This notebook acts as both an analytical and demonstrative tool, enabling researchers and developers to understand, reproduce, and extend the brain tumor classification pipeline.---If youd like a more detailed or technical version, just let me know!</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques/blob/master/LICENSE'>LICENSE</a></b></td>
					<td style='padding: 8px;'>- Provides the licensing terms for the project, establishing legal permissions and restrictions for software use, distribution, and modification within the overall architecture<br>- Ensures clarity on intellectual property rights and usage conditions, supporting open-source collaboration and safeguarding the projects legal integrity.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Provides an overview of the project focused on classifying brain tumors through deep learning methods, specifically utilizing frozen convolutional neural networks<br>- The content highlights the approachs purpose within the broader architecture, emphasizing its role in enabling accurate tumor detection and diagnosis, thereby supporting medical decision-making and advancing healthcare technology.</td>
				</tr>
			</table>
		</blockquote>
	</details>
</details>

---

## 🚀 Getting Started

### 📋 Prerequisites

This project requires the following dependencies:

- **Programming Language:** JupyterNotebook, Python
- **Libraries and Dependencies Used**: OpenCV, Matplotlib, Pandas, Numpy, Scikit-Learn, Tensorflow, Keras, Joblib (to save model checkpoints), Seaborn
- **Deep Learning Algorithms and Techniques Used**: Frozen Convolutional Neural Networks, VGG19 (for image recognition), Incremental Fine Tuning

### ⚙️ Installation

Build BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/muhammadhussain-2009/BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd BRAIN-Tumor-Classification-Using-Deep-Learning-Techniques
    ```
## Roadmap
- [X] **`Task 1`**: <strike>Load Dataset with Pandas, Data Cleaning, Inpection, Exploratory Data Analysis and Data Visualisation(Within Jupyter Notebook)</strike>
- [ ] **`Task 2`**: Apply Data Augmentation technqiues (cropping, resizing etc) with OpenCV's dependencies
- [ ] **`Task 3`**: Set up train, test and validation file directories for model. Configure a generator to load images in batches.
- [ ] **`Task 4`**: Feature Engineering, Build Model,  
- [ ] **`Task 5`**: Freeze Inital Layers. Apply incremental fine tuning
- [ ] **`Task 6`**: Set up different Models with VGG19 as a base and weights from previous layer. 
- [ ] **`Task 7`**: Compile models with SGD optimizer. 
- [ ] **`Task 8`**: Test and Evalaute Model 
---

## Contributing

- **💬 [Join the Discussions](https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/issues)**: Submit bugs found or log feature requests for the `Brain-Tumor-Classification-Using-Deep-Learning-Techniques` project.
- **💡 [Submit Pull Requests](https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/muhammadhussain-2009/Loan-Approval-Prediction-System/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=muhammadhussain-2009/Loan-Approval-Prediction-System">
   </a>
</p>
</details>

## 📜 License

Brain-tumor-classification-using-deep-learning-techniques is protected under the [LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
