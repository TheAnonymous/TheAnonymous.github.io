---
title: Uploader a simple way to share files across the network
layout: post
---
# Uploader

###  Welcome. This is a small and super simple programm to share files across the network over HTTP. It is tested on Windows, Linux and Mac but should be compilable to every system where gcc/clang exists. The only thing you have to do is to download it and execute it.


* [Windows(x64)](https://drive.google.com/file/d/0B_GPBNtpF5YgalZUMlF3bGIyelE/view?usp=sharing)
  On windows a small pcre.dll is needed because I use Perl regex in my code. I may try to compile it static in the future.
* [Windows(x86)]() Comming soon.
* [Linux(x64)](https://drive.google.com/file/d/0B_GPBNtpF5YgYWhSY0FPdUVaelU/view?usp=sharing)
* [Linux(x86)]() Not commming soon because who use 32bit Linux anyway :P
* [Linux ARM]() Comming soon.
* OSX - Comming Soon.


[Source on Github](https://github.com/TheAnonymous/Uploader/tree/master)

#### There are two options you can use. First is to set a port where where it should serve (i.e. 80 which is the standard HTTP port). Second option is to serve subdirectorys. Here are some examples:

* ./uploader insecure 80
* ./uploader 80 insecure
* ./uploader 80
* ./uploader insecure

####As you see pretty basic and it doesn't matter which order you use

If you see any bugs please open an issue at my github page.

LIZENSE: BSD

Thats it have fun.
