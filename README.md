crytopp-5.6.2-for-arm
=====================

Modify GNUmakefile to applicable to the ARM plantform.
修改源码包中的GNUmakefile文件,使其适用于ARM平台.


Compile the source codes after modified GNUmakefile with arm-linux-gnu-g++ tools-links, and move head files and libs into 
ARM development-envirement after doing MAKE && MAKE INSTALL.

I have inserted compile argument "-fPIC" into this ARM GNUmakefile to avoid some compile WARNING/ERROR


使用arm-linux-g++进行编译, install后将库和头文件放入arm开发环境对应的目录中
增加-fPIC编译参数,使其能够进行动态编译并非固定内存地址寻址.


You can contact me when there are some questions:
Email:gukaiqiang@gmail.com
