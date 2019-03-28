# Ducky Scripts

Tutorial: Ducky Scripts

It not just bubble bath play toy, but really a keyboard in disguise. It looks like a thumb drive that has the registration of a keyboard. This allows you to connect the usb thumb drive into a target computer, and it will act like a keyboard. As you know you pretty much can do anything on a computer without lifting your hand to use the mouse. Rubber ducky allows just that, interacting with computer with just the keyboard.

In order to run ducky scripts you need a ducky device. The device is ~$45, and in my opinion, they are kind of expensive. The reason why I say that is that you can find alternatives that are much cheaper.  There are a couple of tutorials where you can use an old usb thumb drive or a raspberry pi zero for a very low price. 

## Step 1
[Download](https://github.com/hak5darren/USB-Rubber-Ducky/blob/master/duckencoder.jar) ducky encoder. This is a jar file so we will be using this in step 4 when compiling our script.  

## Step 2
Insert microsd card in computer to put scripts on. 

## Step 3
Create Ducky Scripts!
<br>
Its not too hards since the command list can be found [here](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript). <br>
The more used commands are:
- REM (add comments)
- STRING (type line exactly as is into target)
- ENTER / SPACE ("enter", "space" key)
- DELAY (delays instruction for a bit)
- GUI (cmd key on mac)

**Hello World**
>DELAY 3000 <br> GUI r <br> DELAY 500 <br> STRING notepad <br> DELAY 500 <br> ENTER <br> DELAY 750 <br> STRING Hello World!<br> ENTER

This gets saved in a plain text file!
<br>
OR you can view and use the many ducky scripts from [here](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payloads)

## Step 4
Its time to compile your ducky script. Here you would transfer the text file to your microsd card that will be used inside of your ducky.

**Note** 
we are running the jar on the textfile then we save it to the sd card which is Volumes but could be different for you. Then we ouput it with inject.bin. 

To run the jar file:
- java -jar ~/path/to/jar/duckencoder.jar -i ~/path/to/duckyscript/yourscript.txt -o /Volumes/NO\ NAME/inject.bin


## Step 5
Go test it!
Insert sd in rubber ducky. Try try putting it in your computer usb and see if it works!





