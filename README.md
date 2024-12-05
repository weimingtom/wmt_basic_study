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

## 大昔につくったnscripter版narcissuのPSP移植版貼っとく
* https://archive.org/details/narcissu-for-psp_20230904_0718  
* https://x.com/owasikohu/status/1825212321863811264  
* narcissu for psp β.zip  

## PSP-Archive/ONScripter-for-PSP  
* https://github.com/PSP-Archive/ONScripter-for-PSP  

## [分享]用ONScripter在PocketPC上玩PC的美少女AVG  
* https://www.mobile01.com/topicdetail.php?f=129&t=1113684  

## To Heart2動いた~。  
* https://nyanonon.hatenablog.com/entry/20051012/p1  
* https://web.archive.org/web/20050404193721/http://pyon.org/furukawa/watasimo/waffleppc.html  
* https://web.archive.org/web/20050308143414/http://waffle.bunkasha.co.jp/zau/index.html  
* あかね  
* https://web.archive.org/web/20050308143414/http://waffle.bunkasha.co.jp/zau/akane-src-010909.zip  
* http://waffle.bunkasha.co.jp/zau/index.html  
* https://web.archive.org/web/20070416235126/http://otd10.jbbs.livedoor.jp/1000011759/bbs_plain  
```
TODO：
onscripter-libretro加载narcissu for psp β.zip会崩溃

bt搜索，magnet搜索
https://en.btdig.com/search?order=0&q=さよならを教えて+

https://ultrapre.github.io/blog.ztjal.info/index.html

[其他] 我想用C++做一个制作AVG游戏的 制作软件 开发一套引擎 [复制链接]
https://www.rpgchina.net/forum.php?mod=viewthread&tid=32705

http://harupspgame.blog64.fc2.com/blog-entry-230.html

TODO，baidupan, NSCRIPTER_OG.7z

https://thenewleafjournal.com/narcissu-insani-version-vn-review/
https://web.archive.org/web/20230222204643/http://stage-nana.sakura.ne.jp/narcissu.htm
http://altogether.insani.org/2005/resources/index/phase00.html
narcissu

onsplayer
http://onsplayer.cn
https://github.com/CrazyPeter/PlayVisualNovelsOniOS

https://github.com/vn-tools/arc_unpacker
```
```
https://github.com/waybeforenow/toheart-tools
https://github.com/skydark/nstools
```
```
转，【个人重制】《月姬plus+disc》-unity引擎重制版 发布
https://tieba.baidu.com/p/8551539049
基于Fungus
search baidupan, 月姬plus-unity2018工程文件.rar
我发现tieba上有人用unity移植《月姬plus》到psv上
（参考：《月姬plus+disc》-unity引擎重制版），似乎是基于Fungus框架（插件），
不过我的Unity版本太旧打开不了这个移植工程。
我有长远计划自己用Unity或CSharp实现类似onscripter的功能，
不过暂时还只是计划尝试阶段。准备假期正式迁移到gh上继续研究下去
```

## light.vn
* https://lightvn.net/download/  
* https://github.com/SoulEngineProject/Light.vn  
* https://github.com/xiakkto/Light.vn-Chinese-Wiki/wiki  
* https://soulengineproject.itch.io/lightvn  
* Light.vn.release.16.4.2-en_240806_1255.zip  
* Light.vn.release.16.5.1_240816_1912.zip  

## Steam  
```
https://steamdb.info/tech/Engine/NScripter/
https://steamdb.info/tech/Engine/KiriKiri/
https://steamdb.info/tech/Engine/YU-RIS/
https://github.com/SteamDatabase/FileDetectionRuleSets/tree/main/descriptions
https://steamdb.info/tech/Engine/RenPy/
https://steamdb.info/tech/Engine/CatSystem2/
SteamDB有个没什么用的功能是可以根据游戏查游戏引擎，或者根据游戏引擎反查相关的galgame，
例如我找到这些引擎：水仙1+2的NScripter，亚托莉Atri的KiriKiri（其实是krkrz），
龙姬混日子的YU-RIS，片轮少女的RenPy，ISLAND的CatSystem2，
不过有些游戏的引擎没识别出来（没收录引擎），例如星之梦planetarian
具体遍历
https://github.com/SteamDatabase/FileDetectionRuleSets/tree/main/descriptions
```
```
https://github.com/eviltwo/ChotNovel/tree/main
KAG风格脚本
https://github.com/eviltwo/ChotNovel/blob/main/ChotNovel/Assets/StreamingAssets/scenario/test.txt
可运行的unity galgame
https://github.com/RyougiChan/PoiGalgame/releases/tag/v0.1.0

mine别名aka：面包工坊mine模拟器app
system4 sdk
https://github.com/silas1037/AliceSoft
search silas1037_AliceSoft-master.zip
壳之少女，G弦，TLWiki
https://www.sohu.com/a/278568936_120020331
(TODO) 记录NScripter那本书和光盘
https://github.com/silas1037/GalHex/tree/master
https://github.com/jszhtian/Krkr-engine
crass
https://github.com/weimingtom/X-moe/tree/master/Unpacker/crass
rpaExtract  作者：芥末沙拉热狗包 https://www.bilibili.com/read/cv21268044/ 出处：bilibili
如果上述软件无法解压，可使用UnRen工具进行解包， 作者：芥末沙拉热狗包 https://www.bilibili.com/read/cv21268044/ 出处：bilibili
UniExtract 作者：芥末沙拉热狗包 https://www.bilibili.com/read/cv21268044/ 出处：bilibili
AssetStudio软件（汉化版） 作者：芥末沙拉热狗包 https://www.bilibili.com/read/cv21268044/ 出处：bilibili
https://www.bilibili.com/read/cv21268044/
https://github.com/Kaskadee/rpaextract/releases
https://github.com/F95Sam/UnRen

来源crass, see crass-0.4.10.1.rar
https://github.com/shangjiaxuan/Crass-source/tree/master/crass-0.4.14.1/documentation/cn
https://morkt.github.io/GARbro/supported.html
-
描述：        System-NNN（Naynit Kcalbwen Studio）(http://www2s.biglobe.ne.jp/~tinyan/nyanlib/index.htm)
-
描述：        ISM script engine（http://hp.vector.co.jp/authors/VA000482/）
源代码下载（ISM-1.0.0.src.rar）：
http://www.wiiupload.net/fl/5e2d10f59c
https://hp.vector.co.jp/authors/VA000482/software/ismsa099.lzh
https://hp.vector.co.jp/authors/VA000482/
(x) https://github.com/b1csimar/java_ism
search baidupan, ismd099c.lzh, ismd099c.lzh, not source file!!!!
-
名称：        HSP
描述：        onion software开发的系统Hot Soup Processor（http://www.onionsoft.net/hsp/）
hsp3
https://github.com/onitama/OpenHSP
https://hsp.tv
-
名称：        FS
【注意事项】
源代码下载（FlyingShinePDFile-2.0.0.src.rar）：
http://www.wiiupload.net/fl/3d03a5adea
-
名称：        ExHIBIT
描述：        RETOUCH开发的sketch/ExHIBIT系统（http://www.retouch.info/）
-
名称：        ADV+++
描述：        Professional Adventure-Game System by YOX-Project（http://www.yox-project.com/）
```
```
chonscripter-20101024.zip, like onscripter-CN

小鸡模拟器的ONS：cn/natdon/onscripterv2，感觉好像多了一些类，可能做了改动或者基于别的分支代码
```
```
(TODO)
在xubuntu20上编译运行xclannad的效果（我以前试过在Windows上跑，这次改成用linux跑），
目前只能跑日本语版。其实我是想弄中文的，没成功——因为我没找到可用的文件，
估计怕被人提文本所以应该比较难找到，待考（不过能跑原版其实就足够了）。
至于这玩意要怎么编译，只能说要改很多地方，因为代码写得不咋的

xclannad的中文我也搞出来了，我的天，其实就是GBK来着，
之前显示不出来是因为转换gbk2unicode的代码有问题，可以通过debug_flag=true
打开调试输出重定向到文件，然后就能猜测到具体字符集了（原版是sjis，FV中文版是gbk），
然后改转换函数即可（我参考的版本是转两次，改成转一次就正确了），
有时间试试整个换成FV版看能不能正常运行（目前我测试的数据并非FV版）
work_xclannad_v2_chinese_good.tar.gz
```
```
我试过用rpgmaker 2000也可以做出类似rpgmaker xp的galgame效果（ppt），方法和效果如下：
（1）准备好立绘背景图和背景音乐，准备ps，可能需要goldwave
（2）设置开始没有角色，用地图右下角的粉红砖块铺满，
地图树右键地图属性选择开头图（3）立绘事件图片复制Picture，
标题图复制到Title和Panorama（用于默认背景图），声音复制到Music目录
（4）bgm支持mp3（5）立绘最好保存为等屏大小的透明png索引8位，
并且用PhotoShop把颜色表中透明色替换到第一个（按旁边吸管点击颜色表）
（6）切换图片可以用HideScreen和ShowScreen代替
（7）在地图砖块创建一个autorun事件，填写事件，
通常以Text命令分隔切换对话和屏幕（ShowText），因为ShowText能暂停屏幕
Project002_v2.rar

clannad_fv chinese patch
https://code.google.com/archive/p/clannad-fullvoice-simplechinsese-patch/downloads
https://github.com/pzcchina/clannad-fullvoice-simplechinsese-patch/tree/master
code.google.com/p/clannad-fullvoice-simplechinsese-patch
我试过用加了GBK转换的xclannad运行CLANNAD FV全语音GBK版也是可以的，效果如下，
patch来源这个工程：clannad-fullvoice-simplechinsese-patch（我用的是默示版的clannad fv，
但原版应该是这个patch，默示版相当于patch之后的结果），还是有很多fall back错误，
不过似乎勉强可以使用（可能加载保存有问题）

或者更准确的说法，面包工坊mine源代码里面的xclannad应该是不能直接运行GBK版的
clannad fv（或者是替换了GBK SEEN.txt的默示版），需要改一下代码中字符转换函数，
直接执行gbk2unicode即可（去掉前一个双字节字符转换操作）

[20040428][Key]CLANNAD_moshi.zip
测试源码和ttf字体文件（看_min目录里面的字体）；
work_xclannad_20241014_moshi_v2.tar.gz
==
在xubuntu20上编译运行xclannad的效果（我以前试过在Windows上跑，这次改成用linux跑），
目前只能跑日本语版。其实我是想弄中文的，没成功——因为我没找到可用的文件，
估计怕被人提文本所以应该比较难找到，待考（不过能跑原版其实就足够了）。
至于这玩意要怎么编译，只能说要改很多地方，因为代码写得不咋的
xclannad的中文我也搞出来了，我的天，其实就是GBK来着，
之前显示不出来是因为转换gbk2unicode的代码有问题，
可以通过debug_flag=true打开调试输出重定向到文件，然后就能猜测到具体字符集了
（原版是sjis，FV中文版是gbk），然后改转换函数即可
（我参考的版本是转两次，改成转一次就正确了），
有时间试试整个换成FV版看能不能正常运行（目前我测试的数据并非FV版）
work_xclannad_v2_chinese_good.tar.gz
==
xubuntu200464_onsyuri
==
https://code.google.com/archive/p/clannad-fullvoice-simplechinsese-patch/downloads
CLANNAD_FV_2.0.rar
这个CLANNAD_FV_2.0.rar，应该就是上次说的GBK版clannad fv gbk patch的出处，都十几年前了，
如果能提供相关工具就好了，不过不可能——因为这种patch本质上和做游戏差不多，
都是不想人看到里面的内容，或者看了也很难改。另外我有点怀疑steam版可能也是和FV版类似，待考
==
需要额外放置一个默认字体ttf和ttc文件，未记录（TODO）
==
```
```

xsystem35_1.7.3-pre5.orig.tar.gz，
https://mirrors.cqupt.edu.cn/deepin/pool/main/x/xsystem35/
如果用1.7.2必须装gtk-config,即libgtk1.2-dev或libgtk1.0-dev，必须支持gtk-config命令（例如redhat9，挂载IDE硬盘）
https://blog.csdn.net/u010189459/article/details/38401513
错误：heching for gtk-config... no
checking for GTK - version = 1.2.0... no
*** The gtk-config script installed by GTK could not be found
*** If GTK was installed in PREFIX, make sure PREFIX/bin is in
*** your path, or set the GTK_CONFIG enviroment variable to the
*** full path to gtk-config.
configure: error: Cannot find GTK: Is gtk-config in path?
原因：
解决：sudo apt-get install libgtk1.2-dev
==
在ubuntu14上编译运行的xsystem35-1.7.3，从这个版本开始支持gtk2或者叫gtk+（此处是gtk+-2.0 2.24.23），
不再需要gtk-config命令。字体问题仍然待考，编译可能需要做一些修改和特殊配置
（IMP）work_xsystem35_v1.tar.gz
kichikuou_GAMEDATA.zip
==
在redhat9上编译运行的xsystem35-1.7.2，由于这个版本需要gtk1.0（此处是gtk-1.2.10）和gtk-config，
所以不能在ubuntu10和之后的版本上编译，所以只能这样。字体显示问题未解决（redhat9只支持IDE硬盘不支持SATA硬盘）
work_xsystem35_redhat_v1.tar.gz
==
（TODO）尝试windows下编译？
==
（IMP）
ubuntu14下勉强能把xsystem35 1.7.3pre5的字体弄出来（可能根据字体不同有些字仍然显示不出），
方法是在命令行后面加上这样的参数：./xsystem35 -devfont ttf -ttfont_gothic msgothic.ttc，
至于这个ttc或者ttf字体需要自己去找一个，这个开源项目应该不提供，
类似的情况xclannad的字体也是要自己找（我用了类似的字体）
work_xsystem35_v2.tar.gz
==
我测试过可以用相同的命令行方式指定gothic字体，运行redhat9上编译的xsystem35 1.7.2，
而且字体显示更佳，所以我可能最终还是选这个版本来研究
（./xsystem35 -devfont ttf -ttfont_gothic msgothic__real.ttc)
==
鬼畜王兰斯中文版.rar
其实这A社游戏好像有人做了中文版的（大概也算神作吧，不懂），只不过有一些地方没中文，
而且一上来就全打通了。我没试过能不能用xsystem35启动，也不想试，
可能有时间用ONScripter-CN的代码比较一些。
我怎么感觉上这个游戏是带语音的（不确定），应该是可以外挂语音文件的，
但这个中文版本应该不能语音，只有音效
==
兰斯bgm问题
Xsystem35.pdf
```
```
Sys42SDK_20041224.lzh
system40ver132.lzh
http://kei.stbbs.net/rubyeye/sys40/sdk_dl.html
http://sidealice.blogbus.com/logs/144618.html
http://ms.mblogger.cn/af
http://sidealice.blogbus.com/logs/346778.html
http://sidealice.com/
http://8ne.sakura.ne.jp:20008/chika/unitbase/xsys35/
```
```
TODO：
转区工具
winxp 日语版

gdi混合器.rar
GDIPlusDBB.exe, mfc gdiplus.dll

rldev.rar
Translation_Aggregator.7z
apploc.7z
AGTH_setup.rar
th2x_chspatch_ver103.7z

Xp3tools-20060708.zip see TLWiki.rar
gpl_cd.img.rar, Aquaplus_sources.iso.rar.exe see TLWiki.rar
```
```
Visual C++冒险游戏程序设计.rar
Visual C++_RPG游戏程序设计.rar
我把《Visual C++ RPG游戏程序设计》和《Visual C++冒险游戏程序设计》这两本书的源代码又找回来，
打算把RPG那个也计划这几年内移植到Java上。至于《冒险》那个我以前已经移植到Java上了。
其实这俩游戏都不咋的，属于那种你只要知道怎么玩就算玩通了的感觉，不过好处是开源，
不开源的游戏再好玩也没多少参考价值
Script Engine Programming (スクリプトエンジン プログラミング) 
https://github.com/weimingtom/myosotis2/tree/master
脚本引擎编程， ScriptSource.zip
http://www.sbcr.jp/products/4797347623.html
3d游戏编程，3dRpgProgramingSample.zip
```
```

latest CUI for Crass.rar
Crass-source.7z
http://www.kaorinusantara.web.id/forum/f9/how-rip-cg-data-visual-novel-galge-5506.html/
http://blog.roodo.com/toheart/archives/5543593.html


yaneSDK
ygs2001v111.lzh

一些提取器
onscripter-tools_win.zip
crass-0.4.10.1.7z
ExtractData120_src.7z
汉化脚本
CLANNAD.7z
kanon.7z
Planetarian.7z
この青空に約束を.rar

RealLiveMax
RealLiveMax_SDK_20110107_004.zip
里面有angel magister的示例，见GAMEDATA
RealLiveMax_SDK_20111129_006.zip
```
```
ONScripter-CN, real
https://github.com/natdon/ONScripter-CN/tree/951935b05ae66fb5e0c09ceb437324687f0a23f7/jni/app_onscripter-32bpp/onscripter-20130317
面包工坊ONScripter-CN的一部分代码应该是来源于早期的john-he中文化版本，
见onslocale.h的头部。当然我手头上存有的john-he源码版本都是2009年以前的，
而ONScripter-CN的版本是2013年，应该是重新又整合进去（已经改得面目全非）——
所以可能只有两种中文化GBK版，一个是john-he，一个是jh，
也可能这俩其实本质上都是同一个源头同一个人搞出来的
```
```
研究waffle:
avg32
kurokoge
avg32_commands
xkanon.airdemo-pre.patch.gz
bless_avg32_1.4.tar.gz

kirikiri相关
https://github.com/number201724/psbfile
https://github.com/Project-AZUSA/IronTJS
https://github.com/Project-AZUSA/KirikiriSharp
https://github.com/UlyssesWu/Furikiri
https://github.com/rinkako/YuriAVGEngine

nexas相关，青空下的约定，女仆咖啡帕露菲
https://github.com/pkuislm/NexasPackEdit
https://tieba.baidu.com/p/1048551798
https://github.com/pkuislm/NexasPackEdit/tree/main
toheart2, ps2
https://nyanonon.hatenablog.com/entry/20051012/p1
https://tieba.baidu.com/p/6983596738
https://zhidao.baidu.com/question/73361126.html
http://izuno.blog22.fc2.com/blog-entry-31.html
https://bbs.saraba1st.com/2b/thread-177550-1-1.html
http://savaiv.blog81.fc2.com/blog-entry-292.html
ppc
https://www.mobile01.com/topicdetail.php?f=129&t=1113684
avg32
kagayaku.tabigeinin.com/zakki01.html
Shiori-chan Project, ONScripter Multi-Platforms Binary,
ONScripter for MacOSX 10.2 + Tools(nsaconv, sarconv, nsadec, sardec),
xclannad for LinuxZaurus,waffle for arm
https://web.archive.org/web/20071231075020/http://kimatten.hp.infoseek.co.jp/#ONScripter
https://web.archive.org/web/20090220183547/http://kimatten.hp.infoseek.co.jp/

Toheart PS2光盘有个SLPS_254.12文件，里面有MW MIPS C Compiler字样
Metrowerks Playstation 2 Compiler
https://github.com/matt-kempster/m2c
https://github.com/Xeeynamo/sotn-decomp
https://romspure.cc/roms/sony-playstation-2/to-heart-2/

waffle???
https://github.com/vn-tools/arc_unpacker/releases
https://forums.fuwanovel.moe/topic/7080-guide-avg32-for-ios-waffle-app/
https://web.archive.org/web/20130811153135/http://www.iphooone.com/pukiwiki/index.php?AIR¾
http://www.retropc.net/kenjo/zau/
https://www7a.biglobe.ne.jp/~hajipda/pg3_waff.htm
在PSP2000上运行waffle的效果（我这里用avgcnv07.zip和avc020803.zip的avgconv.exe转换kanon初回版，
并且把WLK200.AVD改名为WLK2XX.AVD，并且复制onscripter psp的default.ttf。
waffle psp版是waffle-040116_psp（霧雨の降る日に わっふる for PSP）。
总体来说没语音，而且开头主菜单的鼠标移动很飘，很难移动到某个菜单
waffle-040116_psp__20241018_v1_may_run_good.7z
==
我很怀疑所谓的waffle（わっふる）其实很可能并不是真的AVG32，只不过号称是AVG32罢了
（它读取的WLK2星星.AVD数据文件的开头写着ZAVG32)，也许因为它似乎支持AVG32的PDT（图片格式？），
所以它说它自己是类AVG32，我感觉是这样
==

https://zhidao.baidu.com/question/1766065596450028100.html
青空下的约定（18X）（NeXAS引擎，ONS引擎）
G弦上的魔王（ONS，LAVIS引擎）
loli的时间（AMP引擎）
lovemaid（AMP引擎）
memories~将记忆的全部~（AMP引擎）
SANARARA~ 一生一次~（AMP引擎）
白色相簿2序章（AMP引擎）
XXloli（AMP引擎）
车轮之国 向日葵的少女（ONS引擎）
车轮之国悠久的少年少女（PGM引擎）
冲动的魔女们 ~被囚禁的zero~（日本语）（rfz引擎）
鬼哭街（LAVIS引擎）
和之匣（AMP引擎）
滑溜溜的汁液（PGM引擎）
花吻在上（AMP引擎）（忘了多少作了）
花与少女的祝福（AMP引擎）
花与少女的祝福FD(日本语）（AMP引擎）
军人少女的（哗~~~）生活（日本语）（AMP引擎）
妹妹大作战（AMP引擎）
梦见之药（ONS引擎，AMP引擎）
梦妖尤娜的侍奉课程（AMP引擎）
明日的世界（RFZ引擎）
你是主人我是仆（日本语）（ONS引擎）
女仆餐厅帕沙耶之歌露菲（ONS引擎，NeXAS引擎）
沙耶之歌（AMP引擎，ONS引擎）
实妹相伴的大泉君（AMP引擎）
盛夏之梦（AMP引擎）
死神之吻乃离别之味（日本语）（RZF引擎）
3days（ONS引擎）
遥仰凤华（日本语）（ONS引擎）
追问
这些引擎是什么意思？
追答
NeXAS是移植的最高境界。
通常的移植都是用PSP的自制AVG引擎移植的，例如AMP
ons 这个是用官方引擎移植的

RLVM
在ubuntu14上编译运行rlvm 0.14的效果（steam非hd版的英语和日本语两个版本），
我只能说编译这个项目要看脸，rlvm最新版就没办法在ubuntu14上编译，
包括PortMaster版的rlvm的参考仓库也无法在ubuntu14上编译成功。
我暂时只考虑旧版本（反正都能用）。我没想通字体是怎么回事，
英文和日文都有不同程度的问题，但英文会严重一些；还有我想不明白为什么没指定字体文件也能显示日文，
只能说作者也太厉害了（也可能是通过其他手段来加载日文字体）
==
我大概猜到为什么rlvm可以正常显示到日文字体，它应该是穷举法，
在src/utilities/find_font_file.cc中有两个数组western_platform_fonts和
ja_platform_fonts就是用来推测gothic字体路径位置的。其实xsystem35也有类似的做法，
不过xsystem35的默认日文字体路径在ubuntu上缺失
==
默认似乎加载msgothic.ttc，待考（搜索代码）
==
(IMP) rlvm remove boost progress:
work_rlvm_v7.tar.gz
打算长期改rlvm的代码，把里面的boost代码全部清除掉（还有一些可以清除掉的库）——
不过这些boost代码太多了，我暂时只改了十分之一都不到，慢慢改，反正我也不急于改好，
我可能有时间才做（干别的），准备放到gitee上慢慢改
==
rlvm的字体问题其实有两个，一个是不知道为何PortMaster里面（可能非开源）的rlvm字体是缺像素的，
另一个是在PC版上，英文的间距似乎是不正确的，对于字宽不对齐（字宽变长）的字体会把字母重叠挤在一起
==
在ubuntu14上编译运行rlvm 0.14的效果（steam非hd版的英语和日本语两个版本），我只能说编译这个项目要看脸，
rlvm最新版就没办法在ubuntu14上编译，包括PortMaster版的rlvm的参考仓库也无法在ubuntu14上编译成功。
我暂时只考虑旧版本（反正都能用）。我没想通字体是怎么回事，英文和日文都有不同程度的问题，但英文会严重一些；
还有我想不明白为什么没指定字体文件也能显示日文，只能说作者也太厉害了（也可能是通过其他手段来加载日文字体）
==

使用脚本开发冒险游戏 原始版本.rar
https://github.com/weimingtom/marika_java
アドベンチャーゲームプログラミング
TODO:找这本书的代码
VISUAL C++冒险游戏程序设计.pdf
[Visual C++角色扮演游戏程序设计].pdf
Live2D模型制作讲座 教程集 绘画技巧 日漫教程 临摹美术CG素材
live2Dbook.zip

（IMP，TODO）nscripter_onscripter_kirikiri_demo
projects_20241018.7z
幽冥录1.rar

（IMP，TODO）SFA引擎
SFA_v7_utf8合并.7z
sfa_strings.xls

vino, unity
游戏Demo.zip

OpenRGSS-RPGMaker和rpgmaker
rgss.rar
java版移植，参考：rpg2kemu.7z
```

## retroarch ons  
* https://github.com/christianhaitian/retroarch-cores/blob/master/aarch64/onscripter_libretro.so.zip  
* https://github.com/christianhaitian/rk3326_core_builds/blob/rk3326/scripts/onscripter.sh  

## (IMP) rlvm portmaster  
* https://github.com/christianhaitian/PortMaster/blob/main/Rlvm.zip  
* https://github.com/christianhaitian/PortMaster/blob/main/Moonlight.zip  
* https://github.com/christianhaitian/PortMaster/blob/main/markdown/rlvm.md  
* https://github.com/kloptops/rlvm  
* search baidupan, kloptops_rlvm-master.zip, christianhaitian_PortMaster-main_min_rlvm_moonlight.7z  

## mkxp
* https://github.com/Ancurio/mkxp
* https://giters.com/krishenriksen/AnberPorts/issues/51
* https://github.com/night-burst/mkxp-z
* https://github.com/krishenriksen/AnberPorts
* https://giters.com/krishenriksen/AnberPorts/issues/51
* https://github.com/libretro/easyrpg-libretro
* https://github.com/EasyRPG/Player

## vndb  
```
https://myskrpatch.tistory.com/82
https://vndb.org/r?f=01fwArtemis_0Engine-&o=d&p=1&s=released
火星，我现在才发现原来vndb也是可以过滤引擎类型的（类似于steamdb），
只不过默认不会显示出来，例如可以过滤所有Artemis Engine引擎的galgame
（虽然其实也没啥用）
搜索加上条件是全年龄或者加上介质是CD即可
https://vndb.org/r?q=&sb=Search%21&o=a&s=title&f=02fwArtemis_0Engine-a00
https://vndb.org/r?q=&sb=Search%21&o=a&s=title&f=03fwArtemis_0Engine-a00bgcd
或者只搜索汉化过的
https://vndb.org/r?q=&sb=Search%21&o=a&s=title&f=02fwNScripter-2wzh_dHans-
我有一个办法，可以通过vndb筛选游戏引擎，加上全年龄（拨动下方的滑条到最左），
再加上介质是CD，就可以找到较好的游戏；或者换一个思路，筛选游戏引擎，
加上语言是中文——不过这两种筛选还是会漏掉一些比较好的galgame游戏，
主要vndb上收录的游戏太多了，应该很难找到适合自己的，完全是随缘
```

## easyrpg build
```
easyrpg build
https://github.com/EasyRPG/Player/blob/master/docs/BUILDING.md
https://github.com/EasyRPG/buildscripts/tree/master/linux-static
https://wiki.easyrpg.org/development/compiling/player/cmake
https://easyrpg.org/downloads/player/0.8/
https://github.com/EasyRPG/liblcf
依赖：
https://wiki.easyrpg.org/development/compiling/porting
由于easyrpg的linux版可能会运行失败（动态库问题），所以要自己编译，
在xubuntu20下用cmake编译运行easyrpg过程如下
（1）准备：expat2（我用的是expat-2.4.9）和liblcf-0.8和Player-0.8的源码包，
并且创建的rpgmaker 2k的简单工程（2）用cmake依次编译expat2和liblcf和Player，
使用相同的-DCMAKE_INSTALL_PREFIX=指向同一个输出目录
（原理是cmake会把这个输出目录也用于输入的依靠库目录），
并且都执行make install，最后获得easyrpg-player
（3）然后切换到rpgmaker 2k的简单工程目录下，然后通过LD_LIBRARY_PATH指向so动态库目录
同时执行easyrpg-player，例如这样：
LD_LIBRARY_PATH=/home/wmt/work_easyrpg/out/lib /home/wmt/work_easyrpg/out/bin/easyrpg-player
（4）运行效果和windows版几乎一摸一样

（IMP，TODO）work_easyrpg_v1_success.tar.gz
```
