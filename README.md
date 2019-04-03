# r4g_microbit_yotta_project
This is the Mbed project for the R4G Micro:bit program. It is programmed in C/C++ and utilizes the [lancester-university microbit runtime](https://lancaster-university.github.io/microbit-docs/).


### To change and build the micro:bit .hex file follow theese steps:
You can either install [yotta](http://docs.yottabuild.org/#introduction) or register at [mbed](https://www.mbed.com/)
## Install yotta
Follow the installation instructions on the yotta website or from [lancaster-university](https://lancaster-university.github.io/microbit-docs/offline-toolchains/) or from [IOT Programmer](https://www.iot-programmer.com/index.php/books/27-micro-bit-iot-in-c/chapters-micro-bit-iot-in-c/44-offline-c-c-development-with-the-micro-bit). 
Theese links are also very helpfull for learning about the microbit and how to program it in C/C++.
### clone the repository
Next, clone this repository, open yotta and navigate to the project folder.
### build the project
To build the project enter

*<b>yotta build</b>*

inside your yotta workspace. After yotta finished the build successfully you should have a <b>build</b> directory in your project folder. The .hex file you want to download to your micro:bit is the <b>r4g-microbit-combined.hex</b> file in the <b>source</b> folder inside the build/bbc-microbit-classic-gcc/ directory.
You can now change the main.cpp or header files in the <b>source</b> directory to your liking with an editor of your choice and rebuild it with *<b>yotta build</b>*.
