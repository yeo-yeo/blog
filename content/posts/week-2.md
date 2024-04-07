+++
title = 'Recurse Center: Week 2'
date = 2024-04-07T20:00:00Z
+++

## LDN -> NYC 

The Recurse Center is based in New York and pre-Covid all attendance was in person at its office space, the 'Hub', in Brooklyn.  Since the pandemic physical attendance has been optional, but given that a lot of the value of RC is the connections you make and the ideas you share, I wanted to attend in person.  Circumstances meant I was still at home in London for week 1, but the big thing for me in week 2 was I arrived in New York.

And... there was an earthquake?!

![blinking](/liberty-blinking.gif)

Being here in person had a big impact on how my week was spent - less focus on specific project(s) - more incidental conversations with people about their own origin stories and what they're working on.  Many people organise one-off or recurring workshops about things they'd like to work on and find a group to join them, so I dipped in to a number of these to get some inspiration for what I'd like to do here.  Part of the joy of this is that you don't just end up working on your known unknowns, but you also discover unknown unknowns that can turn into the most interesting and rewarding parts of your time. 

## Bits and pieces

Accordingly, this week has been more about trying out different bits and pieces.  Here's a selection:

### Cryptopals

[Cryptopals](https://cryptopals.com/) is a popular set of cryptographic exercises walking you through from simple tasks like converting hexidemical strings to base64, to advanced algorithmic challenges. My cohort ('batch' in RC terminology) has a weekly meeting to go through these together.

This seemed like a great opportunity to explore something at the edge of my knowledge and to practise using Python (one of my main goals being to learn Python).  And as a bonus, when you poke around in the challenges you reveal weird hidden messages like:

![Cryptopals message](/cryptopals.png)

![Backs away slowly](/homer.gif)

### Missing Semester of CS

Another group I've joined is one following MIT's [Missing Semester of CS](https://missing.csail.mit.edu/) course.  It covers tools and tricks that help you practically be a better and faster developer - classics like grep, sed, awk, as well as profiling, build systems, and job control.

Starting this has been reviving memories of things I learnt from previously dipping into [The Linux Command Line](https://linuxcommand.org/tlcl.php).  It reminded me that on my old laptop I had set up a virtual machine running a version of Ubuntu, as while macOS is Unix compliant and so many of the same commands and tools are available, many others only apply to Linux.

I went through the same process on this laptop to set up an Ubuntu VM so I could test those Linux-specific things out again - but more importantly, while I was browsing the [UTM gallery](https://mac.getutm.app/gallery/) I decided I really needed to set up Windows XP too for the optimum Solitaire playing experience.  Hello old friend. 

![Solitaire showdown](/solitaire.gif)

### Nand 2 Tetris

One thing that came up in casual chats this week is a course called [Nand 2 Tetris](https://www.nand2tetris.org/), in which you go through 12 projects, starting with building 15 different logic gates from solely a NAND gate, and working through all the intermediate steps to building an operating system that you can play a simple game on.

This immediately piqued my interest.  As someone who does not have a CS degree and has only been a developer for a few years, I constantly have this anxiety that there is so much I don't know about lower-level programming, and while you might not need to know it 95% of the time, that other 5% of the time can be where magical things happen.

I went and looked up a presentation given by fellow coursemate [Nic Crane](https://thisisnic.github.io/about/) on her experience of the course, and was sold!  Nic had some very relatable slides in her presentation, such as:

![Nic presentation](/nic-presentation.png)

And my particular favourite:
![Nic presentation](/nic-presentation-2.png)

I was sold!  As the week wrapped up I threw myself into it pretty hard, and worked my way through logic gates and built an Arithmetic Logic Unit (ALU), using the course's provided Hardware Simulator.  Here it is running some automated tests against my ALU code:

![Look at it go!](/hardware-simulator.gif)


### Hearing about fun things other people have been doing

By popular demand another coursemate Maud Gautier re-did her [live-coding presentation](https://github.com/MaudGautier/key-value-store-one-hour) which she'd given a few weeks ago, where she built a simple database before our very eyes.  Maud has chosen to deep dive into database management systems and how they work under the hood in her time here - you can read more about her research on her [blog](https://maudgautier.github.io/).

Various people have also been doing cool projects with a [1985 HP Pen Plotter](https://www.hpmuseum.net/display_item.php?hw=80), like Amy McCarthy's [webcam -> plotter project](https://github.com/amymc/photo-plot).

## Things that didn't make the cut

You quickly realise that one of the biggest challenges of being here is saying no to some of the fun things going on, in order to make some progress on anything at all.  One interesting recurring meeting I popped into is a group that's reading the [Structure and Interpretation of Computer Programs](https://en.wikipedia.org/wiki/Structure_and_Interpretation_of_Computer_Programs) (aka the 'wizard book').  This one felt like it was going slightly too in-depth for what I need right now, and I felt that the commitment I'd have to make to doing the reading meant I'd have to deprioritise other things that I wanted to do 💔 hopefully we'll meet again down the line, wizard book.

Similarly there is a hardcore group undertaking the [ARENA course](https://www.arena.education/), which digs into AI safety and mechanistic interpretability.  The extent of the material of this one makes it a big commitment especially if you're only doing 6 weeks at the RC, so after initially pricking up my ears I realised it probably wasn't the best fit for me right now.

## What's next?

For week 3 I'm looking forward to focusing more on a specific project again after all the dabbling and getting to know people this week.  I'm hoping to keep powering through Nand 2 Tetris and make it to Part 2 (software) where I'm looking forward to slowing down and going into more detail, since subjects like VMs, compilers and operating systems are lower-level but closer to my usual work.
