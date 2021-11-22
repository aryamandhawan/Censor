# cenosr

Governments and social media providers are working to combat harsh, abusive, and profane language as a violation of free expression. But these are mostly limited to such violations in textual forms.
With the new mode of communication and the world pivoting to online medium such as video conferencing for communication in everyday life, there is offensive content or in general curse words that goes unflagged in speech that might lead to conflict caused by offensive content about religion, race, and inter-group difficulties.
Also, for creating a safe environment for children in learning over zoom meetings or even during day to day media browsing there is no guarantee what they might stumble upon and parents have no control over what their children might hear or come across. 
With profanity and hate speech colluding not only textual but also speech and audio in most online videos there is strong need for a robust method that can be deployed on end systems with parents being in control of what is right and what should be censored for their children is an urgent matter that has gone unattended to. 


Currently there are many proposed methods to flag and censor hate speech and offensive words in text and in social media posts but there is none that a user can implement at their own end for censoring such words and phrases in real time over speech. These are often deployed at a company's discretion and with rules that they deem fit without an end user’s say in it. What happens if a service does not offer this?

Also, some companies (intel bleep) that are working on this problem do not provide much access to users and are limited to being implement at the content providers end.

I propose to use a neural network model that leverages transfer learning from ResNet18 to identify not only spoken words as offensive but censor them in real time speech. This model could then be delivered in the form of an application that the users can implement at their own end systems and also define custom rules for parental control etc.

The problem at hand is of developing a novel machine learning model to detect spoken words and censor curse words in audio data containing human speech. This project is an early version of an attempt and the report summarizes the methodology used, experimental setup and the outcomes of proposed approach.

Datasets - 1. Speech Commands dataset - https://www.tensorflow.org/datasets/catalog/speech_commands
           2. Swear Words dataset     - https://github.com/theabuseproject/tapad
