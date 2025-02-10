# Identifying Non-Functional Requirements from Mobile Apps User’s Reviews using Deep Learning
#### Faculty of Engineering and Technology Master of Software Engineering
#### <a href="https://www.birzeit.edu/ar"> Birzeit University </a>
#### Supervisor: Dr. Abualseoud Hanani
#### Student name: <a href="https://www.linkedin.com/in/nasriladaa/" > Nasri Ladaa </a>

## Abstract
Nowadays, smartphones are so essential without them life seems impossible.
The number of useful information carried by users reviews every day is
huge. The traditional way of extracting requirement-related information from a
huge number of reviews is not possible. Hence, Natural Language Processing
(NLP) and Machine Learning (ML) techniques were used to solve this problem
and make it easier for the requirement engineer to benefit from the large amount
of user reviews. <br><br>
In this thesis, some of the state-of-the-art techniques in NLP were applied
for automatically classifying user’s reviews into requirement-related information
such as usability, reliability, performance, security, functional requirements,
and others. Some of the word embedding vectorization methods such as GPT3,
Word2Vec, GloVe, FastText, BERT, Dbert were used to represent the user’s text
reviews. The resulting feature vectors were used to extract the target software requirement
information with some of the traditional machine learning classifiers,
such as Random Forest, Naïve Bayes, and Artificial Neural Network (ANN) and
some deep learning classifiers such as Deep Neural Network (DNN), and Convolutional
Neural Network (CNN). <br><br>
In order to build and test the proposed systems, a dataset collected and used
in a previous study conducted by Al-Kilani was used. This dataset consists of
1061 annotated user’s reviews for apps in the healthcare domain. To make the
dataset larger and wider, another 1693 reviews were collected and manually
annotated form apps in different domains.<br><br>
A set of experiments were conducted using Al-Kilani dataset and the extended
dataset, The extended dataset includes Al-Kilani dataset and 1693 newly
v
collected reviews. To make the results comparable with the previous results
achieved by Al-Kilani, some of the experiments were conducted to recognize
three major classes (reliability, usability, and performance), and the others are
designed to recognize six classes (reliability, usability, performance, security,
functional requirements, and others).<br><br>
For the three classes experiments, the results show that the deep learning based
techniques (SL CNN, ML CNN, DNN) outperform the traditional techniques.
The best accuracy achieved by the Random Forest classifier trained and
evaluated on the TF-IDF features is 58%, compared with 82% achieved by the
DNN classifier trained on GPT3. Similarly, the deep learning techniques outperform
the traditional techniques in the six classes experiments, with the best
accuracy of 56% compared with 49% achieved by the random forest.

## Six used classes in the experiments:

### Usability
Degree to which a product or system can be used by specified users to achieve specified goals with effectiveness, efficiency and satisfaction in a specified context of use. Example: ”I have to navigate into three pages before reach my appointment page”


### Reliability
Degree to which a system, product or component performs specified functions under specified conditions for a specified period of time. Example: “After clicking on start call button the app crashes”


### Portability
Degree of effectiveness and efficiency with which a system, product or component can be transferred from one hardware, software or other operational or usage environment to another. Example: “On my tablet it worked fine but on the phone nothing appeared”


### Performance
Performance relative to the amount of resources used under stated conditions.
Example:“ I have to wait 10 seconds to see all my notifications”
Learnability
Degree to which a product or system can be used by specified users to achieve specified goals of learning to use the product or system with effectiveness, efficiency, freedom from risk and satisfaction in a specified context of use. Example:“I used many similar apps all of them have quick tutorial to get started”


### Compatibility
Degree to which a product, system or component can exchange information with other products, systems or components, and/or perform its required functions, while sharing the same hardware or software environment. Example:“My live match are not synced with FIFA official schedule”


### Security
Degree to which a product or system protects information and data so that persons or other products or systems have the degree of data access appropriate to their types and levels of authorization. Example:“This app allow weak password”


### Functional Requirements
Things that system shall allow, be able to do, may be able to do. Example:“Can you add Call ambulance button so we can make emergency calls faster”


### Others
Include emotional expressions and not related functional or nonfunctional requirements. Example:“Cool”, “I like this App.”
For more details you can refer to :
[4] International Organization for Standardization, 2016. Systems and Software Engineering: Systems and Software Quality Requirements and Evaluation (SQuaRE): Measurement of System and Software Product Quality. ISO.
