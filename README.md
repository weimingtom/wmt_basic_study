# wmt_basic_study
My Basic Language study

## TODO  
* (TODO) something in this: https://github.com/weimingtom/wmt_yacc_study/blob/master/README.md  
* (done) port back to C, tinybasic_cpp    
* https://github.com/Timu5/BasicSharp  
* https://github.com/microsoft/GW-BASIC  
* https://github.com/arucil/gvbasic-simulator4cpp  
* https://github.com/Klaus2m5/6502_EhBASIC_V2.22
* (TODO) tramm i8080 html emulator, Emu8080, Intel 8080 CPU Emulator  
emu8080_java_v3.rar  

## How to exit BASIC  
* SYSTEM (for pcbasic)    
* EXIT  
* QUIT  
* BYE ​​​  

## (IMP) work_emu8080  
* https://github.com/weimingtom/emu8086_playground  
* 待整理, work_emu8080_20230910.7z  
* 2kb_nasm-2.07_v3_good
* 2kb_ver8
* bootbasic
* dump_arduinobasic  

## (IMP) tinybasic csharp and cpp port  
* https://github.com/weimingtom/tinybasic_csharp  
* search baidupan, tinybasic_v3_csharp_failed.rar  
* search baidupan, tinybasic_v13_final_success.rar  
* 不过仔细想想，研究basic诸如bas-int之类的实现，其实有一点点用，因为它很有可能是可重入的  
（调用栈短而且有一个大的执行循环），类似于onscripter。相比而言，lua不太适合做成可重入抢占式，  
虽然lua是可以挂起来，不过很容易循环出不去，无法主动将其挂起
* https://github.com/weimingtom/tinybasic_cpp

## (IMP) tinybasic c and cpp port, with setbuf 0 (from BAS-INT)       
* (IMP) https://github.com/weimingtom/mt300nv2_playground/blob/master/tinybasic-pmachapman/tinybasic.c  
* (IMP) https://github.com/weimingtom/mt300nv2_playground/blob/master/tinybasic_cpp/tinybasic.cpp  

## uBASIC - A really tiny BASIC interpreter  
* https://github.com/adamdunkels/ubasic  
* http://dunkels.com/adam/ubasic/  

## picbasic  
* PIC单片机BASIC编程项目开发  

## casio basic  
* Casio卡西欧fx-5800p  

## EL_BASIC 98  
* https://github.com/tyama501/micro_e  

## N88-BASIC  
* https://github.com/barbeque/n88-basic-reference/blob/master/index.md  
* https://github.com/YutoMizutani/bowling-game-written-by-n88BASIC  
* NEC PC98  
* https://github.com/2540825244/N88-SpaceShooter  

## tinyBasic2, TinyBASIC2 with SDL and SDL_gfx functions, mod from BAS-INT      
* https://github.com/iruka-/ORANGEpico/blob/master/samples/tinyBasic2/tinybasic.c  
* https://www.raspberrypi.com/news/tinybasic-for-raspberry-pi/
* (dead) http://www.staff.city.ac.uk/afl/tinybasic/index.html  
* https://github.com/0x1abin/M5Stack_TinyBasicPlus/blob/master/M5Stack_TinyBasicPlus.ino  

## minimax8085  
* https://github.com/skiselev/minimax8085/blob/master/software/8kbasic/8kbasic-mini85.asm  
* https://github.com/skiselev/minimax8085/blob/master/software/tinybasic/tinybasic-2.0.asm  

## ATX80  
* ZX-80 computer clone with ATmega8 processor and with BASIC interpreter written in AVR assembler.  
* https://github.com/Panda381/ATX80  

## (IMP) treytomes/ecma_basic, by csharp, interpreter and script engine      
* https://github.com/treytomes/ecma_basic  
* search baidupan, ECMABasic55_v1_20221106_build_success.rar  
* search ECMABasic55_v2.rar  
* basic_编程高手箴言  

## BAS-INT (original compiled with Turbo C 2.0 under DOS, gcc mod named TinyBASIC), by C, script engine  
* https://www.drdobbs.com/cpp/building-your-own-c-interpreter/184408184  
* https://github.com/dremwilly/CANBas  
* (only exe, source not complete) 编程高手箴言_第四章  
* (support mingw, TinyBASIC.c) https://github.com/amihart/MIPSelBinaries  
* (only support DOSBOX Turbo C 2.0, TC2) https://github.com/noczero/PASCAL-DAP/blob/master/Tubes/References/HPSource/Source16/C/BAS-INT/BAS-INT.C  
* see https://cubeatsystems.com/ntbasic/resources/ntbasic-v0.1.1.tar.gz  
BAS-INT.ZIP is the original source codes from http://www.programmersheaven.com/download/16060/Download.aspx
see https://cubeatsystems.com/ntbasic/index.html  

## BAS-INT, TinyBASIC  
* 以前有本书叫《编程高手箴言》，里面提到一个basic解释器（只能加载文件），  
有人吐槽过这个代码：《用C语言写解释器（一）——我们的目标》，  
主要是缺少了一些函数导致无法编译。其实这份代码bas-int是  
来源于另一篇文章《Building Your Own C Interpreter》，  
我试过只能用Turbo C 2.0编译运行（当然运行也有问题，后面说），  
可以修改用mingw编译，但运行不出效果，有人修改过（TinyBASIC.c），  
可以运行出效果。另外运行的脚本有要求，不能在结尾回车加空行，而且要在文件最后加一个空格  
* https://www.drdobbs.com/cpp/building-your-own-c-interpreter/184408184  
* https://github.com/dremwilly/CANBas  
* (only exe, source not complete) 编程高手箴言_第四章  
* (support mingw, TinyBASIC.c) https://github.com/amihart/MIPSelBinaries  
* (only support DOSBOX Turbo C 2.0, TC2) https://github.com/noczero/PASCAL-DAP/blob/master/Tubes/References/HPSource/Source16/C/BAS-INT/BAS-INT.C  
* 运行的.bas脚本有要求，不能在结尾回车加空行，而且要在文件最后加一个空格  
* search baidupan, bas-int_v3_必须用DOSBOX_TC2编译才能运行_mingw只能编译运行tinybasic.7z  

## my_basic  
* https://github.com/paladin-t/my_basic  
* search baidupan, my_basic_v1_mingw_run_sunccess.rar  

## Proteus 7 samples, vsm for m68hc11, for 8051  

## LI-CHEN WANG's tinybasic  
* https://github.com/maly/arduino8080basic/blob/master/src/tinybasic.a80  
* Tiny BASIC Li-Chen Wang博士(华裔？)在二十世纪70年代中叶发表了第一个真正用于微处理器的BASIC版本，  
* 可以运行于任何Intel 8080及Zilog Z80 微处理器上， 需要2KB内存，使用纸带输入。  
* 最早版本Palo Alto Tiny BASIC于1976年5月发表在著名计算机杂志Dr. Dobb's。  
* 这是个自由版本，源代码中含有"All Wrongs Reserved"和"CopyLeft" 字样，  
* 表现出作者对金钱的不屑——致敬！
* 转自，你所熟悉和陌生的BASIC  
* http://blog.chinaunix.net/uid-8581780-id-347017.html  
* TINY BASIC FOR INTEL 8080  
* 我认为研究basic（旧版）也可以用来研究OS，只不过这个OS是DOS那边的闭源OS。  
* 典型例子是MS-DOS的MS-BASIC和更早期的CP/M的TINYBASIC，确实有人做8080的虚拟机来运行TINYBASIC，  
* 而8080的移植版称为Palo Alto Tiny BASIC，最早是Li-Chen Wang写的，  
* 他好像是比较早使用copyleft，所以这个Palo Alto Tiny BASIC是开源的——当然这是汇编实现的。  
* 详细可以参考这篇《你所熟悉和陌生的BASIC》

## (TODO) Intel 8080 CPU Emulator, MS 8K BASIC, Dr. Li-Chen Wang Tiny BASIC 1976 (use UPPER case)  
* https://www.tramm.li/i8080/  
* https://www.tramm.li/i8080/emu8080.html  
* MS 8K BASIC  
```
>>> r
>>> r basic.hex  
>>> g 1000
let a = 1000
print a
exit
```
* Dr. Li-Chen Wang Tiny BASIC 1976 (use UPPER case)  
```
>>> r
>>> r tinybas.hex  
>>> g 0
(!!!!!!!! below, should use UPPER CASE !!!!!!!!)  
> LET A = 1000
> PRINT A
> BYE
```
* search baidupan, emu8080_v2.rar  

## Basic 趣味程序选  

## 101 BASIC Computer Games  
* 我顺便找到一本书《101 BASIC Computer Games》，这本书比较有名，  
然后有人把它移植到CSharp和Java，在gh上：basic-computer-games。  
不过应该没有中文翻译本，配图的，我觉得很有趣，我怀疑以前图书馆会有很多这类旧书，  
毕竟我在图书馆找到过更古老的编程语言的代码书，全是示例代码。  
也可以参考这篇《复活80年代的游戏代码，它们出自第一本售出百万册的计算机书籍》  
* https://github.com/coding-horror/basic-computer-games  
* https://github.com/treytomes/ecma_basic  

## A Collection of old classic GW-Basic, BASICA, Applesoft BASIC, MSX BASIC and others.  
* https://github.com/jonatasdemello/gwbasic  

## tbi68k  
* https://www.callapple.org/extras/68000tb/  
* https://github.com/satoshiokue/TinyBASIC-EMU/blob/main/tbi68k.asm  

## tinybasic  
* https://github.com/slviajero/tinybasic  

## FreeBASIC  

## BBC Basic  
* https://www.bbcbasic.co.uk/bbcbasic.html   
* https://github.com/rtrussell/BBCSDL  
* http://8bs.com/submit/subbbcbasicemul.htm  
* http://8bs.com/submit/basicemulator.zip  

## 【熟肉】盖茨逊爆了？：C64 BASIC里隐藏的反微软彩蛋  
* https://www.bilibili.com/video/BV1RP4y1c7V8

## cbmbasic  
* https://github.com/mist64/cbmbasic

## N88-BASIC ESP32  
* https://github.com/shikarunochi/m5n88Q
* https://docs.libretro.com/library/quasi88/  

## PC-BASIC, for python3 under linux      
* https://robhagemans.github.io/pcbasic/doc/2.0/#installation  
* 用ai studio运行pcbasic，效果如下：
```
pip3 install pcbasic
pcbasic --interface=text  
和其他BASIC解释器不同，这个解释器的退出命令是SYSTEM，不是EXIT或者QUIT或者BYE  
```

## Altair BASIC  
* https://sourceforge.net/projects/memu/  
(TODO) not run success, but see asm and bin files    

## (IMP) Girlbasic2k, like TinyBasic  
* https://github.com/netspooky/hardcode/blob/master/02048/dos/girl%20basic%202kb/Girlbasic2k.asm  
* http://flatassembler.net/download.php
* (IMP) search baidupan, 2kb_ver4, for emu8080    

## BASIC-52   
* https://github.com/freecores/t51/blob/master/sw/BASIC-52.asm
* Proteus 7 Professional_SAMPLES.rar  

## bootBasic, asm  
* https://github.com/nanochess/bootBASIC  
* https://hackaday.com/2019/07/31/bootbasic-fits-your-favorite-language-in-the-boot-sector/  

## TinyBasicA64  
* https://github.com/JHelas/TinyBasicA64  

## TinyBASIC-C, basic to asm  
* https://github.com/nssilva/TinyBASIC-C  

## tinybasic example in ANTLR  
* https://github.com/antlr/grammars-v4/tree/master/tinybasic  

## go6502  
* https://github.com/hculpan/go6502    

## tastybasic  
* https://github.com/wwarthen/RomWBW/blob/master/Source/TastyBasic/src/tastybasic.asm  

## Tiny BASIC for the CS01  
* https://github.com/robfinch/Cores/blob/master/CS01/software/boot/TinyBasic.asm  

## TinyBasic65002  
* https://github.com/freecores/rtf65002/blob/master/software/asm/TinyBasic65002.asm  

## IntyBASIC  
* https://github.com/nanochess/IntyBASIC
* https://github.com/jefftranter/6800/blob/master/sbc/software/tinybasic.asm  

## EhBASIC for 6502  
* https://github.com/Klaus2m5/6502_EhBASIC_V2.22/blob/master/basic.asm  
* https://github.com/Juan-Gg/microcoded6502/blob/master/Assembly%20programs/GraphicsV29.asm  

## MacでbootBASIC  
* https://fukuno.jig.jp/2853  
* https://karaage.hatenadiary.jp/entry/2020/03/23/073000  
* https://github.com/taisukef/bootBASIC_64bit/blob/master/basic.asm  

## (TODO) TINY8086, asm, with nasm and boches    
* https://github.com/Honneamise/TINY8086  

## klbasic, BASIC11  
* https://seanet.com/~karllunt/klbasic_main.html  
* https://hackaday.com/2011/08/28/basic-programming-on-an-arduino/  
* https://hackaday.com/2012/05/01/arduino-basic-interpreter-using-lcd-keyboard-and-sd/  
* https://hackaday.com/2012/05/03/basic-for-some-beefy-avrchips/  
* https://github.com/tonypdmtr/BASIC11  

## ehbasic, easy68k, m68k  
* http://www.easy68k.com/easy68kexamples.htm  
* http://www.easy68k.com/examples/ehbasic.zip  

## ???  
* http://savannah.nongnu.org/projects/z80asm  
* https://sourceforge.net/p/asm8080/source/ci/default/tree/  
* https://sourceforge.net/projects/z88dk/files/latest/download  
* https://github.com/adamdunkels/ubasic  
* https://www.cnblogs.com/cway/p/12794979.html  

## bootBasic, bootOS   
* https://github.com/nanochess/bootBASIC  
* https://blog.csdn.net/weixin_42169971/article/details/116949435  
* https://github.com/nanochess/bootOS  

## 用C语言写BASIC解释器
* https://github.com/zzp-me/_posts/blob/a02badba2aa5a4c3afb7c6829bf36c01e4311662/2009-10-18-basic-interpreter-in-c-1.md  
* https://blog.csdn.net/zy1049677338/article/details/80668918  

## bas  
* bas, basic interpreter  
* http://www.moria.de/~michael/bas/  
* https://github.com/paulwratt/bas-2.5-plus  
* https://github.com/PX4/NuttX-apps/tree/px4_firmware_nuttx-10.3.0%2B/interpreters/bas  
* https://github.com/apache/nuttx-apps  
```
其实nuttx-apps也有一些跟buildroot中所收录的不同的脚本引擎库，例如wasm-micro-runtime和wasm3。
还有minibasic好像是一个4000行的单文件basic解释器，但我觉得还能缩到1000行以内。
还有bas好像是另一个ANSI BASIC解释器，好像在哪里看见过，但记不起来，出处是moria.de
```
* https://www.thefreecountry.com/compilers/basic.shtml  

# S-BASIC (1Z-013B), SHARP MZ-700  
* (TODO) z80 see  
http://savannah.nongnu.org/projects/z80asm   
https://sourceforge.net/projects/z88dk/files/latest/download   
* test
```
https://sourceforge.net/projects/mz800emu/
mz800emu-win32-stable-1.0.8-rev_237.rar
run MZ-800 - 32 bit.bat, press c to load .mzf  
or press Alt+K to show keyboard  

1Z-013B.zip
kbasicv5.zip
kostlivec.zip
https://original.sharpmz.org/mz-700/dldos.htm
```
* note
```
又找到一个新的BASIC语言解释器，叫1Z-013B，可以用MZ-700模拟器运行，
例如Sharp MZ-800 Emulator（sourceforge的mz800emu），效果如下。
键盘和现在的键盘不同，可以用Alt+K唤出。ROM可以从sharpmz的下载栏目获得，
格式是mzf。MZ-700是8位机器，基于Z80，我最开始是从咸鱼知道这个（最近）  
```
* not good
```
mzwin_0099.zip
mzwin_0099_v1_not_good.7z
roms.zip
http://mz-800.xf.cz:8080/download.htm

cannot run?
http://sourceforge.net/projects/mz800em/
https://www.math.ucdavis.edu/~mkoeppe/mz800/

not good
https://takamin.github.io/mz700-js/emu.html
```

# MSX BASIC  

# Natural Tiny Basic (NT-Basic), from BAS-INT.ZIP, see ntbasic-v0.1.1.tar.gz/ref    
* https://cubeatsystems.com/ntbasic/index.html  
* search ntbasic-v0.3.0.tar.gz  

# QBASIC  

## Avalonia Visual Basic 6  
* C# impletation of VB6 IDE, also can be used in chrome  
* https://github.com/BAndysc/AvaloniaVisualBasic6  

## Open Basic  
* ob190.zip  

## 40KB BASIC
* https://minibots.wordpress.com/2024/06/05/emulador-de-nec-pc-8001-con-lilygo-ttgo-vga32/  
* https://github.com/basara767676/PC8001FabGL  

## small basic
* https://github.com/sb/releases  

## z80 basic  
* https://www.bbcbasic.co.uk/bbcbasic/z80basic.html  

## (Closed source) apple1 basic rom    
* https://github.com/alangarf/apple-one/blob/master/roms/basic.hex  

## apple1/apple2 basic  
* https://www.scullinsteel.com/apple1/#BASIC
* https://github.com/whscullin/apple2js#readme
* https://github.com/whscullin/apple1js
* https://www.scullinsteel.com/apple1/#BASIC
```
运行whscullin/apple1js的BASIC解释器。方法：
（1）通过非井号后缀链接打开www.scullinsteel.com/apple1/
（2）load按钮然后下拉选择BASIC
（3）等待中间红色进度条充满（可以按CLS按键清屏）
（3）加载完成后显示>字符，就可以输入BASIC语句了

运行whscullin/apple2js的BASIC解释器。方法：
(1)最开始打开www.scullinsteel.com/apple2/
（2）在显示APPLE ][的时候无法输入内容，而且加载按钮中找不到BASIC，
但其实可以直接按RESET按键，重启后看到]提示符，并且DISK 1的灯熄灭
（2）在]提示符后面输入BASIC脚本回车即可执行
```
* Java apple2  
git: apple2emulator.rar  
eclipse: apple2.rar  
```
我看过gh上应该没有我之前可以运行的Java版Apple2模拟器（我以前好像说过这个问题），
原因不明，不过这东西可能只是方便研究6502汇编语言，
就是说基于这些模拟器甚至可以自己编译磁带ROM然后运行——
当然要先找到合适的6502汇编编译器，但我不清楚具体怎么操作
```

## mist64/msbasic, Microsoft BASIC for 6502    
* https://github.com/mist64/msbasic

## a1basic, Apple I BASIC  
* https://github.com/brouhaha/a1basic  
