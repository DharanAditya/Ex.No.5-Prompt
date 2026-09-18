# EXP-5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios

**Name:** Dharan Aditya S

**Reg No:** 212223040035

## AIM

To compare different prompting techniques and evaluate their effectiveness in solving a real-world engineering problem using ChatGPT.

## AI TOOL REQUIRED

* ChatGPT

## PROJECT TITLE

**Automated Food Quality Analysis Using YOLOv8 and Machine Learning**

## PROBLEM STATEMENT

Manual inspection of fruits and vegetables for freshness and spoilage is time-consuming and may produce inconsistent results. The objective of this project is to develop an automated system that uses computer vision and machine learning to detect and classify food items as **fresh or spoiled** from images or webcam input.

## SELECTED ENGINEERING SCENARIO

The selected engineering scenario is **automatic detection and classification of fresh and spoiled fruits and vegetables using computer vision**.

The same problem is given to ChatGPT using different prompting techniques to compare the quality of the generated solutions.

---

## EXPERIMENT PROCEDURE

### Step 1 – Select the Engineering Problem

The engineering problem selected from the project is the automatic detection and classification of fresh and spoiled fruits and vegetables.

### Step 2 – Write the Base Prompt

A simple prompt was created without using advanced prompting techniques.

### Step 3 – Apply Different Prompting Techniques

The same engineering problem was rewritten using different prompting techniques.

---

## 1. Naïve / Base Prompt

**Prompt:**

> How can I detect whether fruits and vegetables are fresh or spoiled using computer vision?

### ChatGPT Response

Computer vision can be used to identify whether fruits and vegetables are fresh or spoiled by analyzing their images. The system can use image preprocessing, feature extraction and machine learning or deep learning models.

A camera can capture the food image, and the image can be processed to identify features such as color, texture and shape. A trained classification model can then classify the food as fresh or spoiled.

---

## 2. Straightforward Prompt

**Prompt:**

> Suggest a computer vision method to detect fresh and spoiled fruits and vegetables using YOLOv8 and machine learning.

### ChatGPT Response

A suitable approach is to use **YOLOv8** for object detection and a machine learning classifier for freshness classification.

The system can follow these steps:

1. Collect images of fresh and spoiled fruits and vegetables.
2. Annotate the images for object detection.
3. Train a YOLOv8 model.
4. Detect the food item from an input image.
5. Extract relevant features such as color, texture and shape.
6. Use a machine learning classifier to classify the food as fresh or spoiled.
7. Display the prediction to the user.

---

## 3. Role-Based Prompt

**Prompt:**

> Act as a computer vision engineer. Design a simple system using YOLOv8 and machine learning to detect fresh and spoiled fruits and vegetables. Explain the dataset requirements, model training, image processing and final prediction steps.

### ChatGPT Response

As a computer vision engineer, the system can be designed using the following pipeline:

**Input Image → YOLOv8 Detection → Feature Extraction → ML Classification → Fresh/Spoiled Result**

### Dataset

The dataset should contain images of different fruits and vegetables in both fresh and spoiled conditions.

### YOLOv8

YOLOv8 can detect and locate the food item in the image using bounding boxes.

### Feature Extraction

Important visual features such as:

* Color
* Texture
* Shape
* Surface appearance

can be extracted from the detected region.

### Classification

A machine learning model such as Random Forest can classify the detected food item as fresh or spoiled.

### Output

The system displays the detected food item along with its freshness status.

---

## 4. Few-Shot Prompting

**Prompt:**

> Examples:
> Example 1: A bright red tomato with smooth skin → Fresh
> Example 2: A tomato with dark spots and wrinkles → Spoiled
> Example 3: A yellow banana with black patches → Spoiled
>
> Based on these examples, design a computer vision approach using YOLOv8 and machine learning to classify fruits and vegetables as fresh or spoiled.

### ChatGPT Response

The examples indicate that visual characteristics such as color, spots, wrinkles and surface condition can help identify freshness.

A suitable approach is:

1. Use YOLOv8 to detect the fruit or vegetable.
2. Crop the detected region.
3. Preprocess the cropped image.
4. Extract visual features.
5. Train a classifier using fresh and spoiled examples.
6. Predict the freshness of a new input image.
7. Display the result.

The model should be trained using a sufficiently large and diverse dataset to improve generalization.

---

## 5. Step-by-Step Prompting

**Prompt:**

> Develop a step-by-step solution for an automated food quality analysis system. The system should accept an image or webcam input, detect fruits and vegetables using YOLOv8, classify them as fresh or spoiled using machine learning, and display the result. Mention important preprocessing, training and evaluation steps.

### ChatGPT Response

### Step 1 – Data Collection

Collect images of fresh and spoiled fruits and vegetables.

### Step 2 – Data Annotation

Annotate the food objects using bounding boxes and assign appropriate classes.

### Step 3 – Image Preprocessing

Resize images and apply suitable preprocessing techniques before training.

### Step 4 – YOLOv8 Training

Train YOLOv8 using the annotated dataset to detect fruits and vegetables.

### Step 5 – Object Detection

When an image or webcam frame is provided, YOLOv8 detects the food object.

### Step 6 – Feature Extraction

The detected region can be analyzed for visual characteristics such as color and texture.

### Step 7 – Classification

A machine learning classifier such as Random Forest can classify the food as fresh or spoiled.

### Step 8 – Evaluation

Evaluate the system using accuracy, precision, recall and F1-score.

### Step 9 – Final Output

Display the detected food item and its freshness status to the user.

---

# COMPARISON / EVALUATION TABLE

| Prompting Technique    | Quality   | Accuracy  | Depth     | Clarity   | Usefulness |
| ---------------------- | --------- | --------- | --------- | --------- | ---------- |
| Naïve / Base Prompt    | Medium    | Medium    | Low       | Medium    | Medium     |
| Straightforward Prompt | Good      | Good      | Medium    | Good      | Good       |
| Role-Based Prompt      | Very Good | Very Good | High      | Very Good | Very Good  |
| Few-Shot Prompting     | Very Good | Very Good | High      | Good      | Very Good  |
| Step-by-Step Prompting | Excellent | Very Good | Very High | Excellent | Excellent  |

---

# ANALYSIS AND OBSERVATIONS

The experiment shows that the quality of ChatGPT's response depends significantly on how the engineering problem is presented.

The **Naïve / Base Prompt** produced a general answer with limited technical details. It was useful for understanding the basic concept but was not sufficient for implementing the complete engineering solution.

The **Straightforward Prompt** produced more relevant information because it specified YOLOv8 and machine learning.

The **Role-Based Prompt** produced a more structured engineering solution by asking ChatGPT to respond from the perspective of a computer vision engineer.

The **Few-Shot Prompt** improved the response by providing examples of fresh and spoiled food. This helped ChatGPT understand the expected classification pattern.

The **Step-by-Step Prompt** produced the most complete response because it clearly defined the input, processing pipeline, models and expected output.

### Key Observation

Improved prompts generally produced more detailed, accurate and useful responses than the naïve prompt. However, the naïve prompt can still be effective when only a simple and general explanation is required.

---

# FINAL SELECTED PROMPTING TECHNIQUE

**Step-by-Step Prompting** was selected as the most effective technique for this engineering problem because it provided:

* Better structured responses
* Higher technical depth
* Clear implementation steps
* More relevant engineering information
* Easier conversion into an actual project workflow

---

# REFINED / FINAL PROMPT

> Act as a computer vision engineer and design an automated food quality analysis system using YOLOv8 and machine learning. The system should accept an image or webcam input, detect fruits and vegetables, and classify each detected item as fresh or spoiled. Provide the solution step-by-step, including dataset preparation, image annotation, preprocessing, YOLOv8 training, feature extraction, machine learning classification, model evaluation, and final result display. Keep the solution practical and suitable for implementation as an engineering project.

---

# ENGINEERING VALIDATION

The proposed solution is technically feasible because:

1. **YOLOv8** can be used for detecting and locating food objects.
2. Image processing can be used to extract visual characteristics.
3. A machine learning classifier such as **Random Forest** can be used for freshness classification.
4. Images can be obtained from datasets, cameras or webcams.
5. Performance can be evaluated using accuracy, precision, recall and F1-score.
6. The system can provide the final freshness prediction through a graphical interface.

The prompting experiment demonstrates that providing **specific requirements, technical constraints and step-by-step instructions** results in more useful AI-generated engineering solutions.

---

# CONCLUSION

The experiment successfully compared different prompting techniques for solving an engineering problem related to automated food quality analysis. The results showed that improved prompts generally produced more accurate, detailed and useful responses than naïve prompts. Among the tested techniques, **Step-by-Step Prompting** provided the most structured and implementation-oriented solution.

Therefore, clearly defining the problem, required technologies and expected output is important for obtaining effective results from ChatGPT.

# RESULT

**The prompt for the above-mentioned engineering problem was executed successfully, and different prompting techniques were compared based on quality, accuracy, depth, clarity and usefulness.**
