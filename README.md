# wmt_basic_study
My Basic Language study

## TODO  
* (done) port back to C, tinybasic_cpp    
* https://github.com/Timu5/BasicSharp  
* https://github.com/microsoft/GW-BASIC  
* https://github.com/arucil/gvbasic-simulator4cpp  
* https://github.com/Klaus2m5/6502_EhBASIC_V2.22
* (TODO) tramm i8080 html emulator, Emu8080, Intel 8080 CPU Emulator  
emu8080_java_v3.rar  

## (IMP) tinybasic csharp and cpp port  
* https://github.com/weimingtom/tinybasic_csharp  
* search baidupan, tinybasic_v3_csharp_failed.rar  
* search baidupan, tinybasic_v13_final_success.rar  
* 不过仔细想想，研究basic诸如bas-int之类的实现，其实有一点点用，因为它很有可能是可重入的  
（调用栈短而且有一个大的执行循环），类似于onscripter。相比而言，lua不太适合做成可重入抢占式，  
虽然lua是可以挂起来，不过很容易循环出不去，无法主动将其挂起
* https://github.com/weimingtom/tinybasic_cpp  

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
我顺便找到一本书《101 BASIC Computer Games》，这本书比较有名，  
然后有人把它移植到CSharp和Java，在gh上：basic-computer-games。  
不过应该没有中文翻译本，配图的，我觉得很有趣，我怀疑以前图书馆会有很多这类旧书，  
毕竟我在图书馆找到过更古老的编程语言的代码书，全是示例代码。  
也可以参考这篇《复活80年代的游戏代码，它们出自第一本售出百万册的计算机书籍》  

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
