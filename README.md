# Ducky Scripts

Tutorial: Ducky Scripts

It not just bubble bath play toy, but really a keyboard in disguise. It looks like a thumb drive that has the registration of a keyboard. This allows you to connect the usb thumb drive into a target computer, and it will act like a keyboard. As you know you pretty much can do anything on a computer without lifting your hand to use the mouse. Rubber ducky allows just that, interacting with computer with just the keyboard.

In order to run ducky scripts you need a ducky device.The device is ~$45, and in my opinion, they are kind of expensive. The reason why I say that is that you can find alternatives that are much cheaper.  There are a couple of tutorials where you can use an old usb thumb drive or a raspberry pi zero for very low $$. 

## Step 1
[Download](https://github.com/hak5darren/USB-Rubber-Ducky/blob/master/duckencoder.jar) ducky encoder. Run it. 


## Step 2
Insert microsd card in computer to put scripts on. 

## Step 3
Create Ducky Scripts!
<br>
Its not too hards since the command list can be found [here](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript). The more used commands are:
- REM (add comments)
- STRING (type line exactly as is into target)
- ENTER / SPACE ("enter", "space" key)
- DELAY (delays instruction for a bit)
- GUI (cmd key on mac)

**Hello World**
>DELAY 3000

>GUI r

> DELAY 500

> STRING notepad

> DELAY 500

> ENTER

> DELAY 750

> STRING Hello World!

> ENTER
