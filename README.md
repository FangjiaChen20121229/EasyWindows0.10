Hello and welcome.😀😀 What you are looking at is a python window library. This file will show you how you will use this window library. 
Since this window library is not yet released in pip, please move the file to your project directory. Since this library uses pyarmor for encryption, you may not be able to properly read the error feedback that python 
gives you. We will inform you about common errors in the following sections.

This library contains two types of pop-up windows.There is a class in this program - WindowsSetting.It helps you to modify some information of the window.
Let's start by creating a msgbox!
msgbox:
msgbox full name of the message box, you can display a message to the user in the msgbox, now the msgbox can use WindowsSetting.title to change the title, WindowsSetting.msg to change the message displayed, WindowsSetting.msgcolor to change the color of the message. WindowsSetting.bgcolor to change the background color, WindowsSetting.font to change the font. Of course, you can also change the font size (int) via WindowsSetting.fontsize
Finally you can build your window using BuildWindow.msg_window
enterbox:
The operation of enterbox is similar to msgbox, except that it cannot display text at the moment. You can use WindowsSetting.button to change the text of the button, WindowsSetting.enterbox_x and WindowsSetting.enterbox_y to change the length and width of the input box. the value of enterbox will be obtained automatically for you, you only need to change the start and end position ( The default start value is '1.0' and the end value is '10.0'). After the user has finished typing, the data will be saved as a string in str_input. For your testing purposes, we will output the retrieved value.
Any suggestions please contact
:ningbojiahong@yeah.net
Thanks!
