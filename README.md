# Feature-Selection-Project


# Student Resource 3

## 📌 Description

> The Student Resource 3 consists of two learning resources teaching on Feature Selection and below are more details into it. 

---

## 📚 Project Overview

**Student Resource 3** is a machine learning learning resource focused on **Feature Selection** and the different approaches used to identify the most relevant features for a machine learning model.

The resource is divided into **two versions**, with each version approaching Feature Selection from a different perspective. Together, they cover the purpose of feature selection, its importance in machine learning, statistical techniques, and the major categories of feature selection methods.

The project is designed to build an understanding of **why feature selection is necessary, how relevant features can be identified, and how different selection techniques can be applied to machine learning problems.**

---

# 📖 Version 1

## Overview

**Version 1** introduces Feature Selection from a practical machine learning perspective. It focuses on identifying useful features, understanding why unnecessary features should be removed, and exploring commonly used techniques for selecting features.

The version also introduces the idea that feature selection can contribute to better model performance, reduce computational requirements, and simplify machine learning models.

### Topics Covered

* Meaning of a feature in machine learning
* Definition and purpose of Feature Selection
* Reasons for selecting relevant features
* Feature Selection and model performance
* Curse of Dimensionality
* Computational efficiency
* Variance Threshold
* K-Best Feature Selection
* Statistical techniques for evaluating features
* Recursive Feature Elimination (RFE)
* Boruta Feature Selection
* Feature importance
* Shadow features
* Relationship between feature and target variable types
* Feature selection before model and hyperparameter selection
* Importance of avoiding unnecessary features and data leakage

### Techniques Explored

**Variance Threshold**

Examines the amount of variation within a feature. Features with extremely low or zero variance may provide little useful information for prediction.

**K-Best**

Selects the top *K* features according to an appropriate statistical scoring method.

The statistical measure depends on whether the input features and target variable are categorical or numerical.

**Recursive Feature Elimination (RFE)**

Uses a machine learning estimator to repeatedly evaluate feature importance and remove less important features until the desired feature set is obtained.

**Boruta**

Uses randomized **shadow features** as a reference for determining whether original features contain sufficient importance to be retained.

---

# 📘 Version 2

## Overview

**Version 2** expands the study of Feature Selection by organizing the techniques into broader categories and examining the advantages and limitations of each approach.

It focuses on **Supervised and Unsupervised Feature Selection**, while providing greater detail on **Filter, Wrapper, and Embedded methods**.

### Topics Covered

* Need for Feature Selection
* Meaning of Feature Selection
* Importance of Feature Selection
* Curse of Dimensionality
* Computational cost
* Feature Selection statistics
* Categorical and numerical variables
* Supervised Feature Selection
* Unsupervised Feature Selection
* Filter Methods
* Wrapper Methods
* Embedded Methods
* Advantages and limitations of each method

### Techniques Explored

**Filter Methods**

Feature selection is performed using statistical or mathematical characteristics of the data rather than relying directly on a machine learning model.

Techniques explored include:

* Information Gain
* Chi-Squared Test
* Fisher's Score
* Missing Value Ratio

**Wrapper Methods**

Feature subsets are evaluated using a machine learning model to determine which combination of features produces useful results.

Techniques explored include:

* Forward Selection
* Backward Selection
* Exhaustive Feature Selection
* Recursive Feature Elimination (RFE)

**Embedded Methods**

Feature selection occurs as part of the model-training process.

Techniques explored include:

* L1 Regularization / Lasso
* L2 Regularization / Ridge
* Elastic Net
* Decision Tree-based methods
* Random Forest-based methods

---

# 🔎 Topics and Techniques Across Both Versions

Across Version 1 and Version 2, Student Resource 3 explores the following major areas:

| Area                               | Topics / Techniques                                                       |
| ---------------------------------- | ------------------------------------------------------------------------- |
| **Feature Selection Fundamentals** | Meaning, purpose, importance, relevant vs. irrelevant features            |
| **Dimensionality**                 | Curse of Dimensionality                                                   |
| **Statistical Selection**          | Variance Threshold, K-Best, Information Gain, Chi-Squared, Fisher's Score |
| **Missing Data**                   | Missing Value Ratio                                                       |
| **Model-Based Selection**          | RFE, Wrapper Methods                                                      |
| **Automated Selection**            | Boruta and Shadow Features                                                |
| **Sequential Selection**           | Forward Selection, Backward Selection                                     |
| **Combinational Selection**        | Exhaustive Feature Selection                                              |
| **Regularization**                 | Lasso, Ridge, Elastic Net                                                 |
| **Tree-Based Selection**           | Decision Trees, Random Forests                                            |
| **Selection Categories**           | Supervised and Unsupervised Feature Selection                             |
| **Statistical Variables**          | Categorical and Numerical Inputs/Outputs                                  |

---

# 🗂️ Repository Navigation

> You will find 4 files in this repository plus the readme file. Two of the files are the documentations and the other two files are python files which are the code replications of the project.

---

# 💡 Key Takeaways

## From Version 1

* Feature Selection helps identify variables that provide meaningful information to a machine learning model.
* Not every available feature is necessarily useful for prediction.
* Removing unnecessary features can reduce computational requirements and simplify the learning process.
* Different statistical techniques are appropriate for different combinations of categorical and numerical variables.
* **Variance Threshold** can eliminate features with little or no variation.
* **K-Best** selects a specified number of highly relevant features according to a scoring method.
* **RFE** uses model-based feature importance to progressively remove less useful features.
* **Boruta** compares original features against randomized shadow features to determine their relevance.

## From Version 2

* Feature Selection can be approached through **Supervised** and **Unsupervised** methods.
* Supervised selection uses the target variable, while unsupervised selection does not require one.
* **Filter methods** rely primarily on statistical characteristics of the data.
* **Wrapper methods** evaluate feature subsets through a machine learning model.
* **Embedded methods** perform feature selection during model training.
* Filter methods are generally faster and more scalable but do not directly account for model-specific feature interactions.
* Wrapper methods are more closely connected to model performance but can be computationally expensive.
* Embedded methods provide a middle ground by incorporating feature selection into the learning process.

---

# 🎯 Overall Learning Outcome

By completing both versions of **Student Resource 3**, the learner should develop a clearer understanding of **why feature selection matters, how relevant features can be identified, and how different feature selection approaches differ in their methodology, computational requirements, and relationship with machine learning models.**

The two versions collectively provide a foundation for making more informed decisions about **which features should be retained, evaluated, or removed before and during machine learning model development.**

---

## 📝 Conclusion

Student Resource 3 provides a structured exploration of **Feature Selection in Machine Learning**, progressing from fundamental concepts and individual techniques in Version 1 to a broader classification and comparison of selection methods in Version 2.

Together, the resources demonstrate that effective feature selection is not simply about reducing the number of columns in a dataset. Rather, it is about identifying and retaining the features that provide meaningful value to the machine learning task.
