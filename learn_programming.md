---
title: Learning Programming
layout: default
---
## Resources to learn programming.

Here are some resources to learn programing I will add stuff when I find more.
So I would suggest to learn Ruby as a first language since you get much done without to much effort. Also stuff like "Pointers" and "Memory Managment" doesnt have to bother you.
With time its useful to learn such stuff and I would definitly suggest to learn also other languages, but Ruby has a low learning curve which is nice for a good start.
So here are the resources to make you a battle plan. This is not a "how to" but a few hints to where to look at. Read the stuff yourself as the internet is full of good Youtube-Video-Tutorials, How to's and tutorials.

#### Linux
Linux is for beginners the most difficult Operating System possible but its also the most programming focused OS. Also it will help to know Linux when you administrate a server.
IMHO the best distributions are [Fedora](https://getfedora.org/) and [Antergos](http://antergos.com/) Fedora is easyer at the start but Antegros/Arch is easyer if you want to dig deeper as it provides much software via AURs. So if you want to develope C++, C, Ruby, Python go with Fedora, but if you want to some more unusual like Nim, Elixir, Rust, Go, go with Antegros as its just a AUR away. But be warned don't use to much time to learn Linux it can be a time consuming hobby to learn more and more stuff like set up a Proxy server, Mail server, backup solution and so forth. Do such stuff when you need it but first of all focus on your goal - "learn to code".

#### Editors
* Atom.io is one of the best starter editors with build in repository. If you want to code for example ruby go to the package management and search for ruby and see if there is a usefull package for you. Same goes for Sublime.
* Sublime Text a bit more stable that Atom and you have to add the repository yourself.
* Gedit is my editor for very small things like config files.
* Vim/Vi/Emacs you will hear many programmers who swear that this are the best editors and they are indeed good BUT they need time to learn and the learning curve is not that small. So you may wana try to learn them when you have time. But I would not recommend them to beginners. Also the config files of both are IMHO very hard for beginners. Personally I learned emacs but really it gave me not that much more power and other Editors are more comfortable.
* IDEs like Netbeans/Eclipse/Visual Studio whatever: They are nice when you code in some language like Java but I don't like them much as they are often very slow. If you program Ruby you may find Rubymine comfortable as it has autocompletion but its nothing I personally like.

#### Learn to Code
So here they are:


[Exercism.io](http://exercism.io/) is excellent to start when you have done your first steps. Basicly you code and other will give you hints how you can make it better. Do one exercise every week and in one year you will be good coder. Really you can read one Book about programming after another but without practice its worthless. You didn't learn riding a bike with reading about - right?


[Rosettacode.org](http://rosettacode.org/wiki/Rosetta_Code) is a good source if you dig into a new language and want to see how to solve a specific problem like reading a file, convert an integer to a string etc.


[Sinatra](http://www.sinatrarb.com/) this is a special tip from me. I've never seen an easyer solution to digg into web programming than Sinatra (and there are Sinatra clones for many languages like flask for python). So you may wonder why should you digg into web programming. Well because it's fun and motivating to see results. With web programming with Sinatra you can see nearly instant results and you can digg as deep as you like. Start with a "Hello World" and then may build your own starting page for your browser then a Server to download files then add a upload function, then may a (simple) RSS-Reader and so forth.


[Rubygems](https://rubygems.org/) THE resource for ruby. Well when you learn a language its ok to start with something like a loop, if clause, and whatever but that was IMHO not much fun because what can you do with such things? The fun part comes with Libs and APIs! You want to parse RSS well go to rubygems search "RSS" take a gem search for examples, copy paste, change it, look into the documentation to see whats possible. With time your knowledge will grow and you will have a bag full of stuff you have done.

#### Github/Git
Git is good and bad in one. Git is a version control system with much power IMHO to much power for a starter. So for a beginner this commands should be enough:
* git init
* git clone
* git commit -a -m "Something"
* git push
* git pull
* git add -A
Of course you can do a lot more with BUT learn as you need it! These commands will bring you to your goal at the start and thats enough. If you spended a evening to learn this Git commands thats enough everything above you will forget to the point where you need it. And that experince is not that good :/ Ah and make a github account its useful you will see...


#### Motivation
 * Bugs and mistakes: They are normal nobody will try something to program and it will work from the beginning thats happens very very rarely even if you are a pro. The normal way is to try, see where something went wrong, go further see where the next thing went wrong, fix it and so forth. If it works like intended enjoy and may add features. Thats the normal way of programming. With time you will get a feeling of how to start things, and where are the hard parts of a task. Also normal stuff like a loop which at start are may hard will just work when you get better but then you will have other breaking points...


* Travel: Really if you are coder and earn money with it you have much freedome as long as you get the stuff done. I dont know any other job where you can travel around the world and work at the same time (37Signals has programmes which does that). And even if you don't want to travel many companys offers that you can come when you want or work from home. Also there are website where you can find remote work just google for it.

* Money: Well everyone needs money to live but coding often not only offers you enough to live but enough to live comfortable. Even if you don't work at Google or Facebook you will normally(!) never have a money problem again (At least if you are good with money...).

* Save everything: Seriously save every piece of code you have with a descriptional name. You will ofter solve a problem and a year later have the same or only a slightly different problem to solve. Than its good when you find the old soloution and only have to make small changes.

#### Copy & Paste
Copy and paste from websites like stack overflow or the official documentation are ok even pros does that. BUT try as hard as you can to understand it. May not all at once but with time. But NEVER! write a program where you have copy/paste code in it which you don't understand and say its finished (well if its just for fun its not that critical but as soon as you write code for others this an absolute NO GO!).

#### Documenation

Seriously read the documentation of anything you use. I don't mean to read it like a book but read it like a handbook. You know? See where is what so that if you have a problem with a lib you know where to search.

### Later...

#### Programming paradigms
Learn
* Learn Object Orientation
* Functional Programming

Use both one time may in a play project. At first you will think like "Where do I need this stuff?" but with time you will see that this are pretty useful sometimes. There are many more but these are today the most used.


#### Multithreading
Many programmers have a huge respect for multicore programming. This doesn't come from nothing BUT today there are tools which makes threading much easyer than C++1988 !
Learn:
* Why functional programming make it much easyer
* Difference between paralleslism and concurrency
* Deadlocks
* Mutex & Semaphores
* OpenMP
* OpenMPI
* Difference between fork and a threads
And at this point you will grasp the rest pretty sure.
