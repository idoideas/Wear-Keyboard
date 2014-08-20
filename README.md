Wear-Keyboard
=============

Simple Activity-Based keyboard to implement in Android Wear apps and can help your users to input texts without using voice commands.

Currently supporting only rectangular watches, Support for round watches will come after their release if needed.

Tested on LG G Watch, 2014.

How can I test it before I implement this?
=============
This Github repo is also an Example project. Fork this project and open it with Android Studio or InteliJ. Connect your Android Wear watch to PC using their adapters, And run the app.

If it doesn't opened automatically on the watch after running, Just using the voice command "Ok Google, Start Keyboard", Or choose "keyboard" at the "Start..." menu.

How to implement it in my app?
=============

1.Download and add "rect_activity_main.xml" (https://github.com/idoideas/Wear-Keyboard/blob/master/src/main/res/layout/rect_activity_my.xml) to your project's layout folder.

2.Download and add "MyActivity.java" (https://github.com/idoideas/Wear-Keyboard/blob/master/src/main/java/idoideas/com/keyboard/MyActivity.java) to your project's java folder.

3.Add "android.permission.VIBRATE" permission to your project's AndroidManifest.xml.

4.Add activity attributes in your AndroidManifest.xml as you wish (Example: https://github.com/idoideas/Wear-Keyboard/blob/master/src/main/AndroidManifest.xml).

5.Start "MyActivity" activity whenever you want to open the keyboard. (For example, When you click a button or clicking an EditText)

6.Use the "OK" button's "OnClickListener" (And the string "TextInput") in "MyActivity.java" to use the the text that the user typed.

It's that simple.

How should I use it?
=============
You can use it as freely as you want, Even change the design of the layout and the code of the java file.

But, Please notify in your Google Play Description That the keyboard your using in your Android Wear app is "Based on Wear-Keyboard by Ido Ideas" and link to this github repo (https://github.com/idoideas/Wear-Keyboard).

Contact
=============
You can contact me through email: Idoideasmail@gmail.com

You can also send me emails about what you liked, what you didn't liked and what I need to change and I'll respond to all of them.
