# MySimpleGirlfriend_2017
[![Packagist](https://img.shields.io/badge/Python-2.7-blue.svg)]() 
[![Packagist](https://img.shields.io/badge/Tensorflow-0.1.0-blue.svg)]()</br>   

<p align="center">
  <img src="https://github.com/SunnerLi/MyGirlfriend_2017/blob/master/img/result.png"/>
</p> 

<br/>

Abstract
---
In 2016, I use telegram API to build a simple girlfriend chatbot. The bot can send me a sticker to celebrate my birthday.
This year, I build another girlfriend chatbot based on facebook messenger API.
The girlfriend can take the simple conversation with me.
In the implementation, we use two usual conversation training data and one song lyrics training data to train the response generation model.
The whole stickers are collected over the telegram platform.  

<br/>

Idea
---
<p align="center">
  <img src="https://github.com/SunnerLi/MyGirlfriend_2017/blob/master/img/idea.jpg"/>
</p> 

<br/>

The idea is shown above. After I type the sentence, it will be sent to the localhost by the tunnel server. The intent prediction model is a RNN-based architecture. 
After the intent is determined, the seq2seq model is used to generate the response.  

<br/>

Notice
---
In this project, the written seq2seq model will be used. However, after the update of tensorflow version 1.0.0, the written model had been removed. To make sure you can run the program correctly, you should check the version of the tensorflow.    
Maybe I will re-write with keras in the future...    

<br/>

License
---
This project isn't open source.
