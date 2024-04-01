+++
title = 'Recurse Center: Week 1'
date = 2024-03-31T22:00:00Z
+++

## Wello, horld!

Earlier this month I decided to leave my job and spend a few weeks at the [Recurse Center](https://recurse.com), working on my programming skills and taking time to think about what I'd like to do next. 

Participants aren't _required_ to write a blog about their time here, but it is a great way to document what you've been doing in this busy period, for your future self if nobody else.

I'll cover more about what the Recurse Center is and why I chose to apply to it in a future post - for now this is just a lowdown on what I've been doing in Week 1 of my batch.

## 🐍 Python
Something I'd like to cover during my time here is Python.  I've only ever really been a Javascript developer and picking up another language will increase my versatility.  Like with human languages, knowing 2+ languages - whatever they are - gives you a better understanding of language as a whole.

When there are so many programming languages in the world, it can feel a bit hard to choose what you should pick or why.  I chose Python purely based on its popularity - it was voted the 3rd most commonly used programming language in Stack Overflow's [2023 Developer Survey](https://survey.stackoverflow.co/2023/#section-most-popular-technologies-programming-scripting-and-markup-languages).

It crops up a lot not just in things like web development, which is what I've done since becoming a programmer in 2019, but also fields like data science and this little known thing which absolutely noone is talking about called machine learning.

<img src="/beckham-meme.jpeg" alt="My favourite meme of the year" width="400" />

So with that goal in mind, here are some of the projects I've chosen:

### A VERY simple Flask server

A few months ago I put together a very basic Flask server that calls the [Octopus Energy APIs](https://developer.octopus.energy/docs/api/), and my first task was to revive that and add a couple of things.  

Octopus Energy is my gas/electricity supplier in the UK and they allow customers to provision API keys and download their smart meter data.  I had some vague idea that I would download this data and display it in a graph against other measures like the temperature at my location over the same time period, and/or the cost of gas/electricity at the same time, to see how the lines relate to each other.  Perhaps this would reveal groundbreaking insights like 'when it's cold, I turn the heating on'.

<img src="/by-george.gif" alt="Who would have thought" width="400" />

Science will have to wait to see if that hypothesis is true because for now I've left this project as just literally printing some unformatted JSON objects on a page.  I'll probably come back to it later to add some kind of visualisation library in, but for now I felt like I'd got what I wanted out of the project - i.e. literally just writing my first Python project (wtf is a 'venv'?), running a server, loading .env variables,  making API calls, displaying output. 

For now I'd like to move further outside of my comfort zone of webpage land, which led me to my next projects.

### Kaggle
As I mentioned above, one common application of Python is in machine learning.  In 2024 it seems a bit remiss to have a career break and not touch on this a little bit.

Realistically I don't see myself as being perfectly suited to the full mathsy linear algebra side of machine learning, but I thought working with some prebuilt tools could be interesting.  That led me to [Kaggle](kaggle.com) - a platform for data science learning and competions.

Kaggle have an entry-level [challenge](https://www.kaggle.com/competitions/titanic) where you build a simple model to predict the likelihood of certain passengers surviving the Titanic disaster, based on some given data such as age, gender, ticket class.  First off... I have to say this feels a bit tasteless - using personal tragedies in what is essentially a game.  Putting those scruples aside though it is an excellent learning exercise, supported by the [Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning) and [Intermediate Machine Learning](https://www.kaggle.com/learn/intermediate-machine-learning) short courses.

### ChatGPT CLI
The most significant thing I worked on was a CLI took written in Python which enables you to ask ChatGPT questions directly from your terminal.  A motivator for this has been just how useful I've found it as a development tool.  Being able to find the answer to questions like 'How do I make an asynchronous non-blocking request?' or 'Why do I get this error about my EntryPoint?' directly inside the IDE, rather than having to switch over to the browser (and potentially succumb to some distraction like my favourite - going down a rabbithole on the Guardian), is massively helpful.

![Quaero in action](/quaero-demo.gif)

If you'd like to try it out, it's called Quaero and is downloadable at https://pypi.org/project/quaero/ 😊.

## Other
I've been trying to practise better developer habits as I've gone about this - finding better ways to organise my ideas, document my findings, and move quickly around my environment.

This has included:
* Making extensive use of [Notion](notion.so) to plan and record my work
* Finally forcing myself to use Vim (or rather Vim bindings in VSCode)
    - shout out to [Vim Adventures](https://vim-adventures.com/) for actually making this fun
    - and [this handy keyboard cover](https://www.editorskeys.com/en-us/products/vi-vim-keyboard-covers-for-macbook-imac) for when your memory fails you
* Making myself do things as much as possible from the CLI, in particular basic things like opening/deleting/moving files and directories

## Outro
It's been a hectic week - in terms of coding, being introduced to new ideas, and also just general life admin as I jumped into a lot of change in a very short space of time - but I'm glad I've got to this place and am looking forward to what the following weeks bring!