## :hourglass: Guess It App (단어 맞히기 게임 앱) :hourglass:
Udacity 과정 Lesson 5 실습 (링크 : https://www.udacity.com/) <br>
This is the toy app for lesson 5 of the [Android App Development in Kotlin course on Udacity](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012)

## Descriptions
**Guess It** is a word guessing app you can play with one or more friends. <br/> 
To play, hold the device in landscape, facing away from you with your thumbs on the **Skip** and **Got It** buttons. <br/>
Your friends can then give you clues to help you guess the word. <br/>
If you get the word right, press **Got It**. If you're stuck, press **Skip**. <br/>
The game runs for the specified time and then shows you your score.

## :bulb: Focused on: App Architecture (UI Layer) :bulb:
* I've Covered
   * **Application Architecture**
   * **ViewModel**
   * **LiveData**
   * **Data Binding**
   * **MVVM**
   * **Encapsulation**
   * **CountDownTimer**
   * **Buzzing(permission.VIBRATE)**

## Playing the App

* **Pressing the <i>GOT IT</i> button**
  * This increases the current score below the timer
<img width="250" alt = "pressing got it" src = "https://user-images.githubusercontent.com/49539592/92930375-f282c580-f47c-11ea-944a-21a2708dbdf4.gif">
<br/>

* **Pressing the <i>SKIP</i> button**
  * This decreases the current score below the timer
<img width="250" alt = "pressing skip" src = "https://user-images.githubusercontent.com/49539592/92929362-615f1f00-f47b-11ea-9839-b962a52b277e.gif">
<br/>

* **Buzzing : Additional Feature**
  * CORRECT_BUZZ_PATTERN : When you get the right answer
  * PANIC_BUZZ_PATTERN : When you doesn't have enough time (You can specify the time)
  * GAME_OVER_BUZZ_PATTERN : When the game has finished (You can also specify the time)
<br/>
