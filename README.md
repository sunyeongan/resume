# Hello SeonYeong !

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.


# Personal Information
- **Name**

  SeonYeong, An  
- **Education** 


  Department of Software, College of Information Science, Hallym University
- **Blog**


  https://seonybob3210.tistory.com 
- **Email**


  asy10092@gmail.com 
  
## Project
- ## App
  - ### [Amata (On-going)](https://github.com/sunyeongan/Amata)
    > This is a location-based to-do list.
  - ### [COOKKUUG](https://github.com/2022-SwUnivHackaton-COOKKUG/cookkug)
    > 'What do you eat?' Stop worrying now! You can see a recipe composed of simple ingredients in about 30 minutes for jachisaeng. And social media where  you take pictures of your dishes
 - ## Web
   - ### [Chuncheon_Jade_Project](https://github.com/sunyeongan/Chuncheon_Jade_Project)
      > Chuncheon tourism website leaving for jade. Front Development: Bootstrap, Backend development: JSP
 - ## System Programming 
    - ### [Mafia Chatting Game](https://github.com/sunyeongan/Univ_lecture/tree/master/SystemProg_2021/Project)
      > Mafia chat game using socket communication.
 - ## AI  
    - ### [Find a filter that improves handwriting recognition rate](https://github.com/sunyeongan/Mnist_Convolution_filter_recognition)
      > By applying various filters (blurring, sharpening, low-frequency filters, etc.) to handwriting written directly on the paint board, which one has the       highest handwriting recognition rate is compared. After training with the Tesorflow mnist dataset, we test the handwritten photo with the filter applied.
    - ### [Psychological Tendency Prediction](https://github.com/sunyeongan/ML/tree/master/dacon/psy_tendency)
    - ### [House Price Prediction](https://github.com/sunyeongan/ML/tree/master/DT/HousePricePrediction)
    - ### [Customer Satisfaction Prediction](https://github.com/sunyeongan/ML/tree/master/DT/Customer_Satisfaction)

## Contribution

### Euphony 
1) Sample App Proposal 


    > Wave-Show-Card helps visually impaired people listen to the show card. 🛒


    - https://github.com/euphony-io/wave-show-card
    - https://github.com/euphony-io/euphony/issues/178
- [PR] show card android receiver 

  > We built and applied euphony-listener in java to implement a sound wave signal receiver app suitable for the Euterpe team. Since it is an app for the visually impaired, it is possible to receive sound wave signals with a single touch.
  - https://github.com/euphony-io/wave-show-card/issues/4
- [Feat] Develop Text to Speech 
  > When the web show card sends a sound wave signal, the app receives it, and the received string is played back by voice.


  - https://github.com/euphony-io/wave-show-card/issues/15 
- [PR] Converting Android receiver code to kotlin (jetpack compose)

  > The sound wave signal receiver app implemented in Java has only UI implemented using compose.
  - https://github.com/euphony-io/wave-show-card/pull/18
- [Code Reiview] :

  
  - https://github.com/euphony-io/wave-show-card/pull/8#pullrequestreview-1051135746
  
  
  - https://github.com/euphony-io/wave-show-card/pull/14#pullrequestreview-1052701521
2) Add Euphony Issue Templete
    > Updated latest issue template with customizable web form fields

    - https://github.com/euphony-io/euphony/pull/176
    - https://github.com/euphony-io/euphony/issues/137
    - https://github.com/DahyeonWoo/issue-template-tutorial/commit/16f3e64d545f045138fe6443c871551565d76d4c
3) Add an advanced log for calling listen() without permission

    > Euphony calls listen() to check for audio permissions. We found that the Euphony sample app is forced to close when the user does not accept the audio        permission request and runs it. As a workaround for listen() , it prints an error log notifying the user that the required permission has not been accepted. And I uploaded the test code of listen() after receiving a review from the maintainer.
    - https://github.com/euphony-io/euphony/pull/217
    - https://github.com/euphony-io/euphony/issues/205
### OpenStack
- Update irc.rst to refelct MacOS and matrix client


  > This change updates the setup IRC on Mac OS section.
and also add another IRC chat with Matrix introduces
by zuul commnuity.
  - https://review.opendev.org/c/openstack/contributor-guide/+/842849
