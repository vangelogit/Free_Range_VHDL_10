# Free Range VHDL 10

This update was motivated by the feedback from the students which appreciated the "no-frills" style of the book
and wanted to see it updated and continuously improved.

Great care was taken to preserve the informal style of the original authors, while adding crucial information
that was needed to make the book more appropriate to the laboratory classes which adopted the book. Minor
updates regarding newer VHDL versions were also added where appropriate.

Vitor Angelo

(What follows it was the last information made available by the original authors)

## FREE RANGE VHDL (last commit: Fri Jan 4 14:07:09 2019 +0100)

Bryan Mealy, Fabrizio Tappero

The purpose of this book is to provide students and young engineers with a guide to help them develop the skills
necessary to be able to use VHDL for introductory and intermediate level digital design. These skills will also
give you the ability and the confidence to continue on with VHDL-based digital design. In this way, you will also
take steps toward developing the skills required to implement more advanced digital design systems.
Although there are many books and on-line tutorials dealing with VHDL, these sources are often troublesome for
several reasons. Firstly, much of the information regarding VHDL is either needlessly confusing or poorly written.
Material with these characteristics seems to be written from the standpoint of someone who is either painfully
intelligent or has forgotten that their audience may be seeing the material for the first time. Secondly, the common
approach for most VHDL manuals is to introduce too many topics and a lot of extraneous information too early.
Most of this material would best appear later in the presentation. Material presented in this manner has a tendency
to be confusing, is easily forgotten if misunderstood or simply is never applied. The approach taken by this book
is to provide only what you need to know to quickly get up and running in VHDL. As with all learning, once you have
obtained and applied some useful information, it is much easier to build on what you know as opposed to continually
adding information that is not directly applicable to the subjects at hand.

The intent of this book is to present topics to someone familiar with digital logic design and with some skills in
algorithmic programming languages such as Java or C. The information presented here is focused on giving a solid
knowledge of the approach and function of VHDL. With a logical and intelligent introduction to basic VHDL concepts,
you should be able to quickly and efficiently create useful VHDL code. In this way, you will see VHDL as a valuable
design, simulation and test tool rather than another batch of throw-away technical knowledge encountered in some
forgotten class or lab.

Lastly, VHDL is an extremely powerful tool. The more you understand as you study and work with VHDL, the more it
will enhance your learning experience independently of your particular area of interest. It is well worth noting
that VHDL and other similar hardware design languages are used to create most of the digital integrated circuits
found in the various electronic gizmos that overwhelm our modern lives. The concept of using software to design
hardware that is controlled by software will surely provide you with endless hours of contemplation. VHDL is a very
exciting language and mastering it will allow you to implement systems capable of handling and processing in parallel
ns-level logic events in a comfortable software environment.

This book was written with the intention of being freely available to everybody. The formatted electronic version of
this book is available from the Internet. Any part of this book can be copied, distributed and modified in accordance
with the conditions of its license.

If you want to download the PDF or to know more about this book have a look at the [freerangefactory website](http://freerangefactory.org).

If you want to buy the Free Range VHDL Paperback you can do that from [amazon.com](https://www.amazon.com/no-frills-writing-powerful-digital-implementations/dp/B015MT2IBM/ref=sr_1_1).

#### FREE RANGE VHDL - how to contribute ####

Latex source files of the open-source VHDL book FREE RANGE VHDL. FREE RANGE VHDL is written in Latex!

The source code is available from: 
 https://github.com/fabriziotappero/Free-Range-VHDL-book

To help out with the book you can point out problems or suggestions 
by sending me an e-mail at:
   http://freerangefactory.org/#contact

Alternatively, you can get the Latex source, edit it and sending me a
patch. If you like that please keep reading.

git (www.git-scm.com) is the version control system used to menage the 
content of this book. I personally use the Git Shell command line.

1) Get the latest latex version of the book from github:
    git clone https://github.com/fabriziotappero/Free-Range-VHDL-book.git
    cd Free-Range-VHDL-book-master

2) you can see the history of the latest version of the book with:
    gitk

4) Modify and save any file you want.

5) If you have Latex installed in your machine, use the command "compile" 
   and the command "clean" to compile and clean your final PDF. 
   check the status of your work with the command:
    git status

5) create a patch with the command:
    git diff > my_patch.patch

6) copy and paste the content of the patch file and an explanation of what
   you have done in:
    http://freerangefactory.org/#contact

AN ALTERNATIVE AND MODERN WAY IS TO GENERATE A GITHUB PULL REQUEST.
https://yangsu.github.io/pull-request-tutorial/

I would love to hear your suggestions and get your help!


