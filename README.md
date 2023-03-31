# Data-bias

The Perspective API is a very powerful tool that I have never used before. In this project, I used it to complete the detection and evaluation of the toxicity of web messages. I first used the API to detect the toxicity of each message, and then set a b-standard above which all messages are considered toxic. Finally, I compared the existing data with the data from the API and got an overlap rate of 0.93. This result tells me that although API has a high correct rate, it is prone to false negative. i.e., toxic comments are considered as normal comments.
