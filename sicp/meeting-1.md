---
layout: sicp-page
title: SICP Study Group -- Meeting 1
---
## <i>(estimated time to complete this: 15min)</i>

# Reading
Section 1.1 @ [http://mitpress.mit.edu/sicp/full-text/book/book-Z-H-10.html](http://mitpress.mit.edu/sicp/full-text/book/book-Z-H-10.html)

# Getting Scheme on your laptop
As you read thru it is really helpful (critical!) to be able to run the examples they give.

Follow these steps to get a Scheme environment set-up where you can run code as you read through the book. We'll be using a Scheme implementation called Racket (http://download.racket-lang.org/) 

I'm going to assume you're on a Mac. If you're on Linux/Windows sorry! You can probably translate these steps pretty easily. Racket is available on Mac/Linux/Windows.

### 1) Open Terminal (Cmd-Space, type "Terminal", hit Enter)

This is a command-line interface to your computer. Many of the things you can do by using the mouse and clicking on stuff, you can also do in the Terminal by typing commands.

### 2) Execute the following command (copy-and-paste it into your Terminal window, and hit "enter"):

curl -o ~/Desktop/racket-6.1.1-i386-macosx.dmg http://mirror.racket-lang.org/installers/6.1.1/racket-6.1.1-i386-macosx.dmg

This downloads the Racket program into a file on your desktop.

### 3) Double click racket-6.1.1-i386-macosx.dmg on your Desktop

Copy the Racket folder to your Applications folder (follow the arrow)

### 4) Launch DrRacket (the development environment provided by Racket)

Cmd-Space, type "DrRacket", hit Enter

# Getting Started with DrRacket

Cool, now you have an implementation of the Scheme language called Racket installed on your computer.

Racket include an IDE (Integrated Development Environment) called DrRacket. And IDE is a place where you can write, navigate, run, test, and debug your code. Everyone has a different set up; some people use full-featured IDEs, some use bare-bones text editors, and others land somewhere in-between.

One of the *really cool* things about the DrRacket IDE is that it's written in Racket! This turns out to be a really powerful technique, because it means you can use your tools (the IDE) to further develop those very same tools.

Let's run some Scheme in DrRacket.

<img src="https://draftin.com:443/images/28309?token=ZD2E7KlT8IUmAqTQgtlbnKIgPAiA3KHoAR__G3JQfAazLaLzGbTn3kgK-jXUvckZ5qWheD4Ab1b-MhgLhPsHYi4" width="600" />

In the top pane is a very simple program which computes the value of the expression (120 + 120). The bottom pane is something called a REPL, which stands for "read-evaluate-print loop." Expressions typed into the bottom pane will be executed when you hit [enter].

Try executing some examples from SICP; e.g enter (+ 21 35 12 7) and hit [enter].

Now you're ready to get started. Do the reading, run the examples, and we'll see you on Tuesday!