# Colorization on a Raspberry Pi
![output image]( https://qengineering.eu/github/Colorization15.webp )
## Colorization with the ncnn framework. <br/>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
Paper: https://arxiv.org/pdf/1603.08511.pdf<br/><br/>
Special made for a bare Raspberry Pi 4, see [Q-engineering deep learning examples](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html)

------------

## Dependencies.
To run the application, you have to:
- A raspberry Pi 4 with a 32 or 64-bit operating system. It can be the Raspberry 64-bit OS, or Ubuntu 18.04 / 20.04. [Install 64-bit OS](https://qengineering.eu/install-raspberry-64-os.html) <br/>
- The Tencent ncnn framework installed. [Install ncnn](https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) <br/>
- OpenCV 64 bit installed. [Install OpenCV 4.5](https://qengineering.eu/install-opencv-4.5-on-raspberry-64-os.html) <br/>
- Code::Blocks installed. (```$ sudo apt-get install codeblocks```)

------------

## Installing the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/ncnn-Colorization_Raspberry-Pi-4/archive/refs/heads/main.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip, LICENSE and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm LICENSE <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
15.jpg <br/>
17.jpg <br/>
Colorization.cpb <br/>
main.cpp <br/>
Sig17Slice.h <br/>
siggraph17_color_sim.param <br/>

------------

## Download the model weights
Before you can run the app, you have to download the model weights. The file is too large (125 MB) to be stored on GitHub (limited to 100 MB). Download location of `siggraph17_color_sim.bin` at [GDrive](https://drive.google.com/file/d/1wdlu9IpbIPeeWdkOouGcwUttKtjK9fW8/view?usp=sharing).<br>

------------

## Running the app.
To run the application load the project file Colorization.cbp in Code::Blocks.<br/> 
The app takes the b/w input file and the output file name as command line arguments.<br>
You may find the hint at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn) handy.<br/>
Do note the application takes about 10 Sec to process a single picture.

------------

### Thanks.
A more than special thanks to [***magicse***](https://github.com/magicse), who adapted the ncnn framework for this colorization app.<br>

------------

### More info.
Colorful Image Colorization [magicse](https://github.com/magicse/ncnn-colorization-siggraph17)<br>
Colorful Image Colorization [richzhang/colorization](https://github.com/richzhang/colorization)<br>
Colorful Image Colorization [Project Page](http://richzhang.github.io/colorization/) by Richard Zhang, Phillip Isola, Alexei A. Efros.

------------

![output image]( https://qengineering.eu/github/Colorization17.webp )<br>

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL)

