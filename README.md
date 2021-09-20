# Spam Detector for YouTube Comments #

Project - 1 <br>
UCS757 - Building Innovative Systems <br>

## Overview: ##
It is a responsive web application and the purpose of this project is to detect that a YouTube comment is a spam or not. This project will help most of the users who wants to avoid and get rid of spam, they need clear and simple guidelines on how to behave.

### Live Link: https://sdyc.herokuapp.com/ ###
(Sample Data already enclosed in this github-repo)

### I/O Screenshot :<br/> ###
#### Input-1 (Not Spam) ####
![1](https://user-images.githubusercontent.com/43958244/133942116-a751a3eb-869d-4e38-a367-7c26983d9e62.png)
<br>
<br>
Output-1
![1-output](https://user-images.githubusercontent.com/43958244/133942176-935f3854-391c-42cd-b1ef-c03eae874d0a.png)
</br>
#### Input-2(Spam) ####
![2](https://user-images.githubusercontent.com/43958244/133942222-0b4276a8-515d-4b84-9df4-fa89ff9b690e.png)
<br>
<br>
Output-2
![2-output](https://user-images.githubusercontent.com/43958244/133942243-c4774aaa-71c4-4fbc-ae73-03c5dfbbf48f.png)
</br>
### Summary :<br/> ###

- Having a proper dataset which provides us the spam comments from YouTube helps us in training those dataset and then testing with our own sample. Firstly, data preprocessing is done followed by creating a bag of words model and then finally training and testing using Multinomial Naive Bayes which gave an accuracy of around 94%. <br>

- With the help of flask I developed the structure of our web application and deployed it on a cloud platform known as Heroku.<br>

- Finally we were able to distingiush a comment from YouTube is a SPAM or NOT SPAM (HAM). <br>

### Novelty :<br/> ###
-	Since, YouTube is considered to be 2nd largest search engine where any inappropriate messages/comments can disturb the user experience. Therefore, our project serves a provides a cakewalk for such problem.<br>

- This project can be made as a base for various other fields where people wants to get rid of the spam such as mails, messages, etc. <br>
