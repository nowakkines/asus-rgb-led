# asus-rgb-led

<p>Linux-compatible open-source libusb implementation similar to the ROG Aura Core software. Supports RGB keyboards with IDs 0b05:1854 (GL553, GL753), 0b05:1869 (GL503, FX503, GL703), 0b05:1866 (GL504, GL533, GL703, GX501, GM501), and 0b05:19b6 (GA503).</p>

## Before using
In order for it all to work, of course you need to install <a href="https://github.com/wroberts/rogauracore#installation">rogauracore</a>.<br><br>
Terminal

```
https://github.com/ap7kj/asus-rgb-led.git
```
First you have to choose the brightness! After that, choose the mode. Click on the file and select `Run as a program`<br>
<img src='https://i.ibb.co/1bnDYWG/Screenshot-from-2022-09-10-22-16-01.png'>

## Problems
If your keyboard remains dark, its brightness might have defaulted to 0. Trynna run `LEVEL 1/2/3`(Brigthness)

If your keyboard does not respond to rogauracore, it may help to send an initialisation message to the keyboard trynna to `initialize_keyboard`<br>
<img src='https://i.ibb.co/yh7K4H3/Screenshot-from-2022-09-10-22-31-14.png'>

Or trynna do this:
```
sudo systemctl restart upower.service
```

## Tips and tricks
If you can't run this file as a program, try this: `Proterties --> Permossions --> Allow executing file as program`<br>
<img
src='https://i.ibb.co/qrN2cBG/Screenshot-from-2022-09-10-22-28-06.png'
width='250'
heigth='120'><br>
Sometimes it may require a password from `sudo` to start, enter.

## Gratitude
I really thank <a href='https://github.com/wroberts'>wroberts</a> for the program, as well as the rest of the guys who took part in it.

If you want a beautiful GUI app, then email me!
