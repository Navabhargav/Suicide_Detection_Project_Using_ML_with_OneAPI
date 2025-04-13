# Suicide_Detection_Project_Using_ML_with_OneAPI
<img src="https://static.vecteezy.com/system/resources/previews/022/148/383/original/label-with-rope-noose-in-a-stop-sign-text-stop-suicide-ask-for-help-concept-of-suicide-prevention-help-with-depression-saving-mental-health-design-for-poster-banner-sticker-etc-vector.jpg" width="400" height="400">


# Introduction
In recent times, the increasing number of student suicides worldwide has highlighted a critical problem that demands our attention. This project, "Suicide Detection for Students using Student Forums," aims to leverage technology to address this pressing issue. By harnessing the power of natural language processing (NLP) and sentiment analysis, we seek to identify potential signs of emotional distress and suicidal tendencies within student forum discussions.

# Problem Statement <img src="https://user-images.githubusercontent.com/72274851/222214323-923a3fe7-56e9-4ba0-abff-162681500702.png" width="40" height="40">

Student forums serve as platforms where students express their thoughts and challenges. Detecting signs of distress and potential suicide risk within these conversations is a complex task, often overwhelmed by the sheer volume and subtlety of cues.

# Solution <img src="https://user-images.githubusercontent.com/72274851/222216353-58874ba5-d9cc-4298-baab-4255bbdb0193.png" width="40" height="40">
Our solution employs advanced NLP techniques to analyze the language used in student forum posts. This approach allows us to identify patterns indicating emotional turmoil, depression, or thoughts of self-harm, enabling early intervention and support.

# Objectives <img src="https://cdn-icons-png.flaticon.com/512/2800/2800015.png" width="40" height="40">
1. Early Detection: Promptly identify potential distress signals to enable timely intervention.
2. Privacy Focused: Our system analyzes language patterns while respecting user privacy.
3. Counselor Notification: Notify school counselors discreetly when concerning language is detected.
4. Support Ecosystem: Foster effective communication between students and counselors, creating a holistic support network.

# Impact  <img src="https://www.impactmapping.org/assets/images/lightbulb.png" width="40" height="40"> 
We believe that by combining technology with empathy, we can make a significant impact on students' lives. Early intervention and emotional support are crucial factors in preventing tragic outcomes. Our system is designed to enhance educators' and counselors' ability to reach out when students need it most.

# Team Members <img src="https://camo.githubusercontent.com/012932956a1c252e20a2e296e01ef7463b9d9d33cd00f6a33d77ad88c18c646c/68747470733a2f2f636f6e646974696f6e2d616c7068612e636f6d2f736f6674776172652f696d616765732f676974757365722e706e67" width="40" height="40"> 


🤺 Alvis Abreo

🤺 Saiyam Chettri

🤺 Mayur C

🤺 Reyona Ronald

# Project Overview
 
Using the power of OneAPI and Machine Learning, in our project we showcase how we can use student forums and conversation done on any microphone to detect if a student is prone to have intriguing thoughts of commiting suicide which is based on analysis of data recorded for past few days. We have also used Natural Language Processing (NLP) to add convenince to recording of data for analysis.


 
# Dependencies Used <img src="https://user-images.githubusercontent.com/72274851/222215296-64d3a566-02c2-4ff9-9b8f-9ec5096f5799.png" width="40" height="40">
 
 • sklearn
 
 • python
 
 • keras
 
 • pandas
 
 • numpy
 
 • nltk
 
 • bilstm
 
 • nodejs



# Methodology for Building <img src="https://repository-images.githubusercontent.com/273951747/c2380780-b3f6-11ea-99c3-21c2dcc9ba2c" width="60" height="50">
🔧 We chose a categorical dataset comsisting of reddit platform's data comprising of 2 columns and 2,33,338 rows available at https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch. 
🔧 Then we performed the following on the dataset:
            
          • PreProcessing of text:
                         1. Punctuation removal
                         2. Stop word removal
                         3. Tokenization
                         4. Lemmatization
                         5. Construction of word vector
                         6. Train BiLSTM model
                         7. Prediction and accuracy

          • Comment text collection

          • Construction of weighted word vector

          • Obtaining comment text representation

🔧 After this we created an online forum portal for students using nodejs, html and css where the students can register, login and use the forum to discuss things openly.

🔧 In the portal we have also integrated functionality of Natural Language Processing which allows the facility of recording voice which might be preferred which then converts to text and the same functionality is implemented.



# Implementation <img src="https://user-images.githubusercontent.com/72274851/222215440-158ffdc1-8a23-4c7f-81c2-44e864d6d043.png" width="60" height="60">

✅ Student goes and initially registers on a student forum portal after which he/she can login and access the existing posts on the portal.

✅ The student can post their posts on the forum as well.

✅ The posts can be made either by typing the text via keyboard or by using a mic.

✅ If the microphone is used the voice is then converted to text.

✅ Either ways the text is then stored in the database based on the data for each user individually.

✅ For each individual the data is then processed by summarising their data of past few days and then this data is sent to the model for processing.

✅ The model then analyses if the student is having thoughts relating to commiting suicide and if so, the counsellor is informed about the same via the stored contact information.




# Challenges Faced <img src="https://www.loginradius.com/blog/static/db8a52fc54f8db8b8c3c7c58719160a3/03979/testing-challenges.png" width="60" heights="70">

✗ To decipher a system which is convenient to register data for model prediction. 

✗ To avoid false positives and false negatives.

✗ Cultural and Contextual variables.

✗ Model Bias and Fairness.

✗ Algorithm Complexity.

✗ Improving the model.

✗ Integration and intercompatibility of diverse applications.

✗ Limited datasets available.

✗ User Acceptance and Compliances.

# Innovations & Unique Features <img src="https://knowledge.wharton.upenn.edu/wp-content/uploads/2023/03/3.15.23-scott-snyder-esg-corporate-innovation-GettyImages-1410816388.png" width="70" height="50">
Integrating suicide detection algorithm to a student forum and a microphone helps to record the data in a covenient manner rather than recording data explicitly such like a form (most of the users are reluctant about).

 
# Future Enhancements <img src="https://royalsociety.org/-/media/policy/projects/human-enhancement/human-enhancement.jpg?w=1000" width="40" height="40"> 
 The solution when integrated with NLP can be integrated in a mobile application for continous data recording and processing so that there will be continous detection. This methodology is already used by platforms like INSTAGRAM and FACEBOOK for target/niche advertising.




