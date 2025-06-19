
---

### ✅ Azure AI Fundamentals Practice Questions

**Question 1**

For each of the following statements, select Yes if the statement is true. Otherwise, select No.
NOTE: Each correct selection is worth one point.

**Statements**

* A bot that responds to queries from internal users is an example of a natural language processing workload.
* A mobile application that displays images relating to an entered search term is an example of a natural language processing workload.
* A web form used to submit a request to reset a password is an example of a natural language processing workload.

---

**Question 2**

Select the phrase that correctly completes the sentence.
**Natural language processing can be used to**

* classify email messages as work-related or personal.
* predict the number of future car rentals.
* predict which website visitors will make a transaction.
* stop a process in a factory when extremely high temperatures are detected.

---

**Question 3**
What is an example of a Microsoft responsible AI principle?

A. AI systems should use black-box models.
B. AI systems should treat people fairly.
C. AI systems should NOT reveal the details of their design.
D. AI systems should protect the interests of developers.

---

**Question 4**

You have a dataset that contains experimental data for fuel samples.
You need to predict the amount of energy in kilojoules that can be obtained from a sample based on its measured density.

Which type of AI workload should you use?

A. Classification
B. Clustering
C. Knowledge mining
D. Regression

---

**Question 5**

Match the principles of responsible AI to appropriate requirements.
To answer, drag the appropriate principles from the column on the left to its requirement on the right. Each principle may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content.

NOTE: Each correct selection is worth one point.

**Principles**
* Fairness
* Privacy and security
* Reliability and safety
* Transparency

**Requirements**

* The system must not discriminate based on gender, .
* Personal data must be visible only to approved users.
* Automated decision-making processes must be rec[ordable to] identify why a decision was made.

```pgsql
+----------------------------+-------------------------------------------------------------+
|         Principle          | Requirement                                                 |
+----------------------------+-------------------------------------------------------------+
| Fairness                  | The system must not discriminate based on gender, race, etc.|
+----------------------------+-------------------------------------------------------------+
| Privacy and security      | Personal data must be visible only to approved users.       |
+----------------------------+-------------------------------------------------------------+
| Transparency              | Automated decision-making processes must be recorded to     |
|                            | identify why a decision was made.                          |
+----------------------------+-------------------------------------------------------------+
```

---

**Question 6**

Complete the sentence.

Counting the number of animals in an area based on a video feed is an example of

* forecasting.
* computer vision.
* knowledge mining.

---

**Question 7**

What should you use to extract details from scanned images of contracts?

A. Azure AI Immersive Reader
B. Azure AI Document Intelligence
C. Azure AI Search
D. Azure OpenAI

---

**Question 9**

Complete the sentence.

Computer vision capabilities can be deployed to

* develop a text-based chatbot for a website.
* identify anomalous customer behavior on an online store.
* integrate a face detection feature into an app.
* suggest automated responses to incoming email.

```pgsql
+----------------+       +-----------------------------+       +---------------------------+
| News articles  | --->  | Filter (Entity recognition) | --->  | Assess (Sentiment analysis) |
+----------------+       +-----------------------------+       +---------------------------+
                                                                      |
                                                                      v
                                      +----------------+         +----------------------+
                                      | Negative       |         | Positive             |
                                      | coverage        |         | coverage             |
                                      +----------------+         +----------------------+
                                            |                           |
                                            v                           v
                                  +------------------+       +-------------------------+
                                  | Send alert       |       | Add to press book       |
                                  +------------------+       +-------------------------+

```
---

**Question 10**

You are authoring a Conversational Language Understanding application to support a music festival.
You want users to be able to ask questions about scheduled shows, such as: "Which act is playing on the main stage?"

The question "Which act is playing on the main stage?" is an example of which type of element?

**Options:**
A. a domain
B. an utterance
C. an intent
D. an entity

---

**Question 11**

You are building a Conversational Language Understanding model for a human resources department.
You want to ensure that the model detects when employees are outside the intended scope of the model.

What should you do?

**Options:**
A. Create a new model.
B. Create a prebuilt task entity.
C. Add utterances to the None intent.
D. Export the model.

---

Sure! Based on the images, here's a **visually clear and easy-to-understand** version of the question and its multiple-choice options for students:

---

### **Question 12**

You used **Natural Language Processing (NLP)** to process a Microsoft news article.
The NLP system returned the following types of information from the text:

📝 Example Output:

```
now                → DateTime  
students           → PersonType  
teachers           → PersonType  
distance learning  → Skill  
Today              → DateTime-Date  
classrooms         → Location  
classmates         → PersonType  
education          → Skill  
Microsoft          → Organization  
175                → Quantity-Number  
183,000            → Quantity-Number  
```

### ❓**Which type of natural language processing was performed?**

</br>

### ✅ Options:

**A.** Translation
**B.** Sentiment analysis
**C.** Key phrase extraction
**D.** Entity recognition ✅ ← *Correct Answer*

</br>

### 💡 Why it's **D. Entity recognition**:

The system identified and **tagged entities** such as:

* People (`students`, `teachers`)
* Organizations (`Microsoft`)
* Dates and quantities (`Today`, `175`, `183,000`)
* Skills (`education`, `remote learning`)

This is a classic example of **Entity Recognition**, where the system classifies elements in text into predefined categories.

---

**Question 13:**

Here's a **clean and easy-to-read table** for **Question 13** that will help students quickly understand and select the correct answers:

---

### **Question 13**

**For each of the following statements, select *Yes* if the statement is true. Otherwise, select *No*.**

| Statement                                                                                       | Yes ✅ | No ❌ |
| ----------------------------------------------------------------------------------------------- | ----- | ---- |
| The Azure AI Language service can identify in which language text is written.                   | ✅     |      |
| The Azure AI Language service can detect handwritten signatures in a document.                  |       | ✅    |
| The Azure AI Language service can identify companies and organizations mentioned in a document. | ✅     |      |

</br>

### ✅ Correct Answers Explanation:

* ✔ **Yes**: Language detection is a built-in feature of Azure AI Language.
* ❌ **No**: Detecting handwritten signatures is a task for **computer vision**, not the Language service.
* ✔ **Yes**: Entity Recognition (a feature of Azure AI Language) identifies companies, people, and locations.

---

**Question 14**

For the following statements, select Yes if the statement is true. Otherwise, select No.
Correct selection is worth one point.

**Statements:**

* Named entity recognition can be used to retrieve dates and times in a text string.
* Key phrase extraction can be used to retrieve important phrases in a text string.
* Key phrase extraction can be used to retrieve all the city names in a text string.

---

**Question 15**

You need to generate images based on user prompts.

Which Azure OpenAI model should you use?

**Options:**

A. Whisper
B. GPT-3
C. GPT-4
D. DALL-E

---

**Question 16**

Select Yes if the statement is true. Otherwise, select No.

**Statements:**

* A transformer model architecture uses self-attention.
* A transformer model architecture includes an encoder block and a decoder block.
* A transformer model architecture includes an encryption block or a decryption block.

---

**Question 17**

Select Yes if the statement is true. Otherwise, select No.

**Statements:**

* You can fine-tune some Azure OpenAI models by using your own data.
* Pretrained generative AI models are a component of Azure OpenAI in Foundry Models.
* To build a solution that complies with Microsoft responsible AI principles, you must build and train your own model.

---

**Question 18**

Which two actions can you perform by using the Azure OpenAI DALL-E model? Each correct answer presents a complete solution.

**NOTE:** Each correct answer is worth one point.

**Options:**

A. Modify images.
B. Detect objects in images.
C. Create images.
D. Generate captions for images.
E. Use optical character recognition (OCR).

---

**Question 19**

(Dropdown menu) refers to a multi-dimensional vector assigned to each word or token in a large language model (LLM).

**Options in the dropdown:**

* An embedding
* Attention
* A completion
* A transformer

---

**Question 20**

Select the answer that correctly completes the sentence.
**Sentence to complete:**

You can modify the [Dropdown menu] parameter to produce more deterministic responses from a chat solution that uses the Azure OpenAI service.

**Options in the dropdown:**

* Frequency penalty
* Max response
* Stop sequence
* Temperature

---

**Question 21**

Complete the sentence.
**Sentence to complete:**

Implementing filters to block harmful content as part of a chat solution that uses generative AI is an example of the [Dropdown menu] Microsoft responsible AI principle.

**Options in the dropdown:**

* accountability
* fairness
* privacy and security
* transparency

---

**Question 22**

What should you do to ensure that an Azure OpenAI model generates accurate responses that include recent events?

**Options:**

A. Add training data.
B. Add few-shot learning.
C. Modify the system message.
D. Add grounding data.

---

**Question 23**

You deploy Azure OpenAI in Foundry Models to generate images.
You need to ensure that the service provides the highest level of protection against harmful content.

What should you do?

**Options:**

A. Customize a large language model (LLM).
B. Configure the Content filters settings.
C. Change the model used by the Azure OpenAI service.
D. Configure the system prompt.

---

**Question 24**

You have the following apps:

* **App1:** Uses a set of images of tumors to identify whether the tumors are benign or malignant and suggest a treatment.
* **App2:** Uses images from cameras to track individual livestock as they move around a farm.
* **App3:** Identifies brands in photographs of billboards.

What does each app use? To answer, select the appropriate options in the answer area.

**NOTE:** Each correct selection is worth one point.

**Answer Area:**

App1: [Dropdown]
App2: [Dropdown]
App3: [Dropdown]

**Options for each dropdown:**

* Image classification
* Linear regression
* Object detection
* Optical character recognition (OCR)

</br>

✅ Hint:
Image classification – Classifies images into categories (e.g., tumor type)
Linear regression – Predicts numeric values (not suitable here)
Object detection – Finds and tracks specific items in an image
Optical character recognition (OCR) – Extracts text from images

---

**Question 25**

You have the following apps:

* **App1:** Understands the public perception of a brand or topic.
* **App2:** Applies profanity filters to speech-to-text.

What does each app use? To answer, select the appropriate options in the answer area.

**NOTE:** Each correct selection is worth one point.

**Answer Area:**

App1: [Dropdown]
App2: [Dropdown]

**Options for each dropdown:**

* Captioning
* Language detection
* Language learning
* Named Entity Recognition (NER)
* Sentiment analysis

---

**Question 26**

What are two tasks that can be performed by using the Azure AI Vision service? Each correct answer presents a complete solution.

**NOTE:** Each correct selection is worth one point.

**Options:**

A. Translate the text in an image between languages.
B. Train a custom image classification model.
C. Detect faces in an image.
D. Recognize handwritten text.

---

**Question 27**

Which action can be performed by using the Azure AI Vision service?

**Options:**

A. identifying breeds of animals in live video streams
B. creating thumbnails for training videos
C. extracting key phrases from documents
D. extracting data from handwritten letters

---

**Question 28**

What is the maximum image size that can be processed by using the prebuilt receipt model in Azure AI Document Intelligence?

**Options:**

A. 5 MB
B. 10 MB
C. 50 MB
D. 100 MB

---

**Question 29**

Capturing text from images is an example of which type of AI capability?

**Options:**

A. object detection
B. text analysis
C. image description
D. optical character recognition (OCR)

---

**Question 30**

Select Yes if the statement is true. Otherwise, select No.

**Statements:**

* Object detection can identify the location of a damaged product in an image.
* Object detection can identify multiple instances of a damaged product in an image.
* Object detection can identify multiple types of damaged products in an image.

---

**Question 31**

You send an image to an Azure AI Vision API and receive back the annotated image shown in the following exhibit.

![b9f3d90b-bec8-4086-a627-caee273a2081](https://github.com/user-attachments/assets/ce25ba80-30d3-45f3-8490-36c95c3e3bae)

> Image shows `banana: 97.99%`, `orange: 96.77%`, `apple: 98.21%`

Which type of computer vision was used?

**Options:**

A. face detection
B. object detection
C. optical character recognition (OCR)
D. image classification

---

**Question 32**

Which Azure service can use the prebuilt receipt model in Azure AI Document Intelligence?

**Options:**

A. Azure AI Vision
B. Azure AI Foundry Service
C. Azure Machine Learning
D. Azure AI Custom Vision

---

**Question 33**

You need to convert handwritten notes into digital text.

Which type of computer vision should you use?

**Options:**

A. optical character recognition (OCR)
B. object detection
C. facial detection
D. image classification

---

**Question 34**

You have the following dataset:

| Household Income | Postal Code | House Price Category |
|---|---|---|
| 20,000 | 55555 | Low |
| 23,000 | 20541 | Middle |
| 80,000 | 87960 | High |

You plan to use the dataset to train a model that will predict the house price category of houses.

What are Household Income and House Price Category? To answer, select the appropriate options in the answer area.

**NOTE:** Each correct selection is worth one point.

**Answer Area:**

Household Income: [Dropdown]
House Price Category: [Dropdown]

**Options for each dropdown:**

* A feature
* A label

---

**Question 35**

For a machine learning process, how should you split data for training and evaluation?

**Options:**

A. Use labels for training and features for evaluation.
B. Randomly split the data into columns for training and columns for evaluation.
C. Randomly split the data into rows for training and rows for evaluation.
D. Use features for training and labels for evaluation.

---

**Question 36**

What is an example of a regression model in machine learning?

**Options:**

A. predicting the sale price of a house based on historical data, the size of the house, and the number of bedrooms.
B. dividing the student data in a dataset based on the age of the students and their educational achievements.
C. identifying subtypes of spam email by examining a large collection of emails that were flagged by users.
D. identifying population counts of endangered animals by analyzing images.

---

**Question 37**

Which Azure Machine Learning capability should you use to quickly build and deploy a predictive model without extensive coding?

**Options:**

A. ML pipelines
B. Copilot
C. DALL-E
D. automated machine learning (automated ML)

---

**Question 38**

What is a form of unsupervised machine learning?

**Options:**

A. clustering
B. binary classification
C. regression
D. multiclass classification

---

**Question 39**

During the process of Machine Learning, when should you review evaluation metrics?

**Options:**

A. After you clean the data.
B. After you test a model on the validation data.
C. Before you choose the type of model.
D. Before you train a model.

---

**Question 40**

Select the answer that correctly completes the sentence.

**Answer Area**

When evaluating the performance of a model, the ______ displays the predicted and actual positives and negatives by using a ....

**Dropdown Options (for the first blank):**

* AUC metric
* confusion matrix
* ROC curve
* threshold

---

**Question**

**Partial Sentence:**

_______ automatically identifies and tags elements within images for better ...

**Dropdown Options:**

* Content safety
* Image analysis
* Optical character recognition (OCR)
* A small language model (SLM)

---

**Question 43**

You are developing a natural language processing solution in Azure. The solution will analyze customer reviews and determine how positive or negative each review is.

This is an example of which type of natural language processing workload?

**Options:**

A. entity recognition
B. key phrase extraction
C. sentiment analysis
D. language detection

---

**Question 44**

Azure OpenAI in Foundry Models _______

**Options to complete the sentence:**

* supports the deployment of GPT-based models.
* provides capabilities exclusively for vision-related tasks.
* provides capabilities exclusively for speech-related tasks.
* requires manual infrastructure management for scalability.

---

**Question 45**
**Sentence to complete:**

_______ models can be used to predict the sale price of auctioned items.

**Dropdown Options (to fill the blank):**

* Classification
* Clustering
* Regression

---

**Question 46**
**Sentence to complete:**

_______ converts spoken audio into text.

**Dropdown Options (to fill the blank):**

* Azure AI Language
* Azure AI Speech
* Azure AI Vision
* Azure OpenAI in Foundry Models
