# Detecting-Phishing-Attack-using-ML-DL-Models
Developed a model to detect Phished emails from legitimate ones  using the Spam Assassin dataset. Extracted relevant features by processing the mails using the NLP  toolkit. Built various ML models like Naïve Bayes, Random Forest, and Voting  Ensemble with the best accuracy of ~72%, and deep learning  model like Neural Network with an accuracy of ~96%. 
### Overview

Phishing is when cybercriminals send malicious emails designed to trick people into falling for a scam. The intent is often to get users to reveal financial information, system credentials, or other sensitive data. The term “Phishing” came about in mid-1990’s, when hackers began using fraudulent emails to fish for information from unsuspecting users. Cybercriminals use phishing because it’s easy, cheap and effective. Email addresses are easy to obtain and emails are virtually free to send. With little effort and little cost, attackers can quickly gain access to valuable data. We can detect these emails and detect them as spam and reduce these attacks. To do this we can use various machine learning and deep learning models.

![amazon](https://user-images.githubusercontent.com/33484737/118261797-b1dac080-b4d1-11eb-997d-f50c1d8952ca.jpg)

### Phishector Architecture

![Algo](https://user-images.githubusercontent.com/33484737/118262889-26622f00-b4d3-11eb-94fa-76d2ddb39875.jpg)

### Email Dataset 

An experiment is conducted in order to identify the input/output behavior of the system. We have collected data from 2 different datasets. The datasets are SpamAssassin and spam/ham. These datasets are open-source and are freely available. The dataset collected in the experiment are identified and given in Table 4.1. Below table shows the total count of dataset and number of phished and legitimate emails present in those datasets which we have further used to train our model.

![Dataset](https://user-images.githubusercontent.com/33484737/118262892-26fac580-b4d3-11eb-99d7-acecebe3581b.jpg)
### Implementation

1. Accessing the .py file and running Phishector code.
![1](https://user-images.githubusercontent.com/33484737/118262860-1ea28a80-b4d3-11eb-958b-9040ab22f6ee.jpg)

2. Entering the path to the folder consisting of emails.
![2](https://user-images.githubusercontent.com/33484737/118262871-206c4e00-b4d3-11eb-9e76-286f6f923be6.jpg)

3. Menu choice available to the user.
![3](https://user-images.githubusercontent.com/33484737/118262872-2104e480-b4d3-11eb-9bee-5a782f72c750.jpg)

4. Choosing choice 1 leads to the extracted features of the emails.
![4](https://user-images.githubusercontent.com/33484737/118262873-219d7b00-b4d3-11eb-989a-536c99d187e8.jpg)

5. Choosing choice 2 provides classification using Deep learning ie Neural network.
![5](https://user-images.githubusercontent.com/33484737/118262877-22cea800-b4d3-11eb-9a22-f4c8ba2d0237.jpg)

6. Choosing choice 3 provides ML models menu.
![6](https://user-images.githubusercontent.com/33484737/118262879-23673e80-b4d3-11eb-9ceb-7e70a6acade9.jpg)

7. Choice 3 in ML models menu provides classification using Extra trees model.
![7](https://user-images.githubusercontent.com/33484737/118262881-23ffd500-b4d3-11eb-8d1d-62f3319ff764.jpg)

8. Choice 4 & 5 in ML models menu provides classification using Adaboost and Stochastic Gradient Boosting model respectively.
![8](https://user-images.githubusercontent.com/33484737/118262883-24986b80-b4d3-11eb-988f-96306bf0cd93.jpg)

9. Choice 6 & 7 in ML models menu provides classification using Voting Ensemble and Naive Bayes model respectively.
![9](https://user-images.githubusercontent.com/33484737/118262884-25310200-b4d3-11eb-88f2-bf9a8c3376cb.jpg)

10. Choice 8 in ML models menu provides classification using SVM model and choosing option 9 in ML models menu will EXIT the internal menu and go back to Main Menu.
![10](https://user-images.githubusercontent.com/33484737/118262885-25c99880-b4d3-11eb-9733-010175b4d34f.jpg)

### Evaluation Metrics

1. Graph plot of evaluation metrics vs score for different ML models on SpamAssassin dataset.
![Spam metrics](https://user-images.githubusercontent.com/33484737/118262898-28c48900-b4d3-11eb-93b0-0920211e08cc.jpg)

2. Graph plot of evaluation metrics vs score for different ML models on HSD dataset.
![HSD metrics](https://user-images.githubusercontent.com/33484737/118262893-26fac580-b4d3-11eb-961a-5b6a3e8f6eb6.jpg)

### Resukt Analysis

1. Graph plot of Machine Learning models vs Accuracy for SpamAssassin dataset.
![Spam metrics ML](https://user-images.githubusercontent.com/33484737/118262895-282bf280-b4d3-11eb-9d83-f4a5ceacb871.jpg)

2. Graph plot of Machine Learning Models vs Accuracy for HSD dataset.
![HSD ML](https://user-images.githubusercontent.com/33484737/118262894-27935c00-b4d3-11eb-9162-434503e1de2b.jpg)
