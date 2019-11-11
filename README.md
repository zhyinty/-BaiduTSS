# 1 . Introduce

This is a ue4 plugin for user to easy use baidu AI TSS to convert text to voice. you can test to voice at https://ai.baidu.com/, now, the service is free but qps limited(5 qps for normal user).


# 2. Usage

##  2.1 Register the baidu accout and create application

You need to register your owned baidu accout, you can find it https://ai.baidu.com/, after you have succesful register the accout, you can get in to console and choose this

![1.png](./Image/1.png)

Then, you need to create your applicaiton .
![2.png](./Image/2.png)

After you create the application, you can jump to application info to get your owned AppID、API Key、SecretKey
![3.png](./Image/3.png)

## 2.2 Set in Project

After you Enable the Plugin, you can Open Project Setting And find Plugins/Text To Voice

![4.png](./Image/4.png)

Fill your AppID、API Key、 SecretKey and click RequestToken， If Successed, You can see the token is auto filled, otherwise please check you input or network

## 2.3 Create Sound Text Object

You can create sound object is Misc / Sound Text， now it only support chinese and english

![5.png](./Image/5.png)

After you created it, you can set your text in Text , you can also changed the Speed 、Intonation 、Volume Or Player Sound Fx 

![6.png](./Image/6.png)

After you fill your text, you can click generate voice to generate the sound, it will be in same dir of the sound text object 
![7.png](./Image/7.png)

After you save the file, you can change the name or move it to other dir.
