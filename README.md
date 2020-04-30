# Introduction
While looking for the solution for this problem initially I was going towards NER way to solve it. But after reading different kernals and blog. I could figure out we can perform Q&A approch.

Clap for : This wonder full artical https://www.kaggle.com/jonathanbesomi/question-answering-starter-pack. Though I've made my on changes in training model.

Approach
We have:

Question: sentiment column (positive or negative), which I've converted into is positive, is negative or is neutral. Just to make it feel like a question.
Context: text column
Answer: selected_text column
Note :
Please make sure while working on this problem your internet must be off. This is one of requirement on submittion our code base.


#Downloads : 

https://www.kaggle.com/jonathanbesomi/transformers-pretrained-distilbert  (Pre-trained Model)
https://www.kaggle.com/jonathanbesomi/simple-transformers-pypi (Required lib to install)
