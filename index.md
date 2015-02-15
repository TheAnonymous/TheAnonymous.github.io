---
title: Uploader a simple way to share files across the network
layout: post
---
# Uploader

###  Welcome. This is a small and super simple program to share files across the network over HTTP. It is tested on Windows, Linux and Mac but should be compilable to every system where gcc/clang exists. The only thing you have to do is to download it and execute it.


* [Windows(x64)](https://drive.google.com/file/d/0B_GPBNtpF5YgalZUMlF3bGIyelE/view?usp=sharing)
  On Windows a small pcre.dll is needed because I use Perl regex in my code. I may try to compile it static in the future.
* [Windows(x86)]() Comming not so soon since I don't have a 32 bit Windows on my fingers but may in the future.
* [Linux(x64)](https://drive.google.com/file/d/0B_GPBNtpF5YgYWhSY0FPdUVaelU/view?usp=sharing)
* [Linux(x86)]() Not commming soon because who use 32bit Linux anyway :P
* [Linux ARM/RaspberryPi]() Comming soon.
* [OSX](https://drive.google.com/open?id=0B_GPBNtpF5Ygb0ZwczZMN1FCQ00&authuser=0)


[Source on Github](https://github.com/TheAnonymous/Uploader/tree/master)

#### There are two options you can use. First is to set a port where where it should serve (i.e. 80 which is the standard HTTP port). Second option is to serve subdirectorys. Here are some examples:

Linux/OSX:

* ./uploader insecure 80
* ./uploader 80 insecure
* ./uploader 80
* ./uploader insecure

Windows:

Extract the zip file copy the dll and the exe where you want it to serve. Then open "cmd" and write

* uploader.exe insecure 80
* uploader.exe 80 insecure
* uploader.exe 80
* uploader.exe insecure

####As you see pretty basic and it doesn't matter which order you use

####Screenshot:

![Screenshot](http://theanonymous.github.io/uploader.png)

If you see any bugs please open an issue at my github page.

LIZENSE: BSD

Thats it have fun.


#### PS: If you have a FritzBox (very popular router in Germany) here is small tool for easy opening a port via upnp, so you can use the Uploader tool to share across the internet.
[UPNP - Tool (Linux x64)](https://drive.google.com/file/d/0B_GPBNtpF5YgNm10ZXp5TnppRFE/view?usp=sharing)
