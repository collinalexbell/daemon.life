## Mission Statement
Build robots & AI that will make every human as wealthy as a modern day billionaire while leaving people free to be as fulfilled and connected with nature as Buddha himself.

## Product Statement
By March 1st, 2018 I will build a production ready gardener robot named Holon & publish a book of the same name detailing the metaphysical principles and reasoning for building such a robot.


## Current daemon.life sites
- [Elliott.daemon.life](http://elliott.daemon.life)
- [Molyneux.daemon.life](http://molyneux.daemon.life)
- [Peterson.daemon.life](http://peterson.daemon.life)

## What is daemon.life?

Futurists like Ray Kurzwiel and Elon Musk predict that in the future, AI and humans will interface so seamlessly with digital computational devices that computer algorithms will feel as if they an inate part of the human mind.

Daemon.life's goal is to develop the algorithms that humans will integrate with and to embody those algorithms within a robotic avitar.

This concept of a daemon was taken from the book series His Dark Materials by Phillip Pullman

## Products

- [Structure Sensor motor mount](https://github.com/SlightlyCyborg/StructureSensorBot)
- Check out the [Etsy](https://www.etsy.com/shop/CyberneticTech) shop for most recent robots.

## History

#### The kickstarter

The concept of daemon.life started when I began building an AI personality for my BB8 robot. Eventually, the AI personality became divorced from the BB8 robot itself and the project took on a life of its own.

I started hacking on daemon.life in Aug 2016 and by Dec 2016, I had launched a kickstarter for the project.

[![kickstarter project](pics/daemon_life_kickstarter.png "Kickstarter")](http://www.youtube.com/watch?v=4QAli8j347E)


The kickstarter ultimately failed, but that did not matter much to me. I had resolved to build a robotics and AI company back in 2013, so now in 2016 I wasn't going to let a kickstarter failure get me down.

#### The reflection period 

I tried to collect my thoughts on why the kickstarter failed. At first I thought it was because I was using a lot of APIs and was not doing speech synthesis and speech recognition using my own neural nets. I had learned [neural nets in college](https://github.com/SlightlyCyborg/dart-neuralnet) and used them in small [gardening robot simulations](https://github.com/SlightlyCyborg/gardening_robot), but those used simple fully connected archetectures and standard backpropgation. I sat down and went though Stanfords Conv Net course and [did most of their assignments](https://github.com/SlightlyCyborg/cs231n-assignment2) to gain a more in depth understanding of machine learning. 


#### Small product launch

In the end, I ultimately decided that the reason my kickstarter failed was not that I didn't have enough home made deeplearning, but was rather because I did not embody the AI into a physical product. If I was going to develop open source AI, I needed to put it into a physical computing device so that I have a package to sell it in. 

I developed a very simple robot with a single axis of rotation that can make a laptop with a webcam follow a person when they move out of frame (left or right)


[![swivel](pics/swivel.png "Swivel")](https://www.youtube.com/watch?v=Oq267ltnVC8)

I put that project up on [collinscybernetic.tech](http://collinscybernetic.tech) and it actually made a few dollars, just by selling open source hardware files.



#### The Dragon Robot

At this point, I pretty much knew what my business model would be: build a simple robot to install my AI software into and then sell the robot to tech enthusiasts who are interested in having a personal AI.

I began development on my next robot.

At first it was going to be a simple evolution of my swivel bot

![2 Axis Bot](pics/2_axis_bot.png "2 Axis Bot")

However, I ended up taking my design skills as far as I could take them and built a robotic dragon with a cellphone for the CPU and face.


![Dragon Drawing](pics/dragon_drawing.png "Dragon Drawing")
![Dragon Real](pics/dragon_real.jpg "Dragon Real")


#### The spider bot

The dragon robot was simply too expensive. I needed something cheaper

I began work on a spider robot, but it was too complex and became a dead end.

<blockquote class="twitter-video" data-lang="en"><p lang="en" dir="ltr">Added a structure sensor to the spider. <a href="https://t.co/TJKRoZoDmp">pic.twitter.com/TJKRoZoDmp</a></p>&mdash; Collin Bell ⓥ/⚛/Ƀ (@SlightlyCyborg) <a href="https://twitter.com/SlightlyCyborg/status/875280630225002496">June 15, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

#### The IndieGoGo Launch.

On July 14, 2017 I had my first significant success. I built motor mount that can move around the popular Structure Sensor on a 2d axis.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ptE-CMaljYE" frameborder="0" allowfullscreen></iframe>

The launch netted me $228 in revenue, $96 of which is in donations for open sourcing the project. 

2 people bought the product.

Again, it was simply too expensive to build the whole product.

The structure sensor costs > $300. This means that I could only market the device to people who already owned the structure sensor.

#### The TY Beanie Baby Robot.

<blockquote class="twitter-video" data-lang="en"><p lang="en" dir="ltr">Too damn cute <a href="https://t.co/w47LxJc6CQ">pic.twitter.com/w47LxJc6CQ</a></p>&mdash; Collin Bell ⓥ/⚛/Ƀ (@SlightlyCyborg) <a href="https://twitter.com/SlightlyCyborg/status/886793968872288260">July 17, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

This robot got >3000 upvotes on [reddit](https://www.reddit.com/r/shittyrobots/comments/6pokmo/i_turned_a_1997_ty_beanie_baby_into_a_shitty_robot/)


There are several things going for this robot as a medium for distributing daemon.life to users.

1. TY Beanie Babies are already a viral meme.
2. They are cheap to get. They are much cheaper than 3d printing a robot body.
3. They come in several varieties. This is in line with the books that inspired this project. In "His Dark Matierals" peoples daemons are embodied in many different forms dependant on the personality of the person.


I have not launched this product yet, but plan on doing so via a YouTube video and ,in the spirit of the 90's, an EBAY listing.



## Future

The short term goals of daemon.life are:

1. Get simple, open source robots into the homes of users.
2. Make sure the robots are both useful and noninvasive. The Furby is an example of what not to do here. Simple uses would be the use of the daemon as an alarm clock and as an alert system for important messages.

The long term goals of daemon.life are:

1. Allow the user to collect meaningfull data about their lives through robotic sensors in the daemon such as through cameras and voice.

2. Allow the user to query that data using visualization tools and speech interaction.

3. Boostrap the evolution of more interesting and capable open source consumer robots. 

The end goal of dameon.life is:

1. Evolve a daemon that can automate the basic physical needs of a person.
2. Make sure each person globally has a daemon that is looking after their physical well being. This would effectively implement a Universal Basic Income of food for all humans on earth.

## Priorities

It seems inevitable that humans will become more and more tightly coupled with their algorithms. 

It seems vital to me that the algorithms that are being with the user are in fact controlled by the user and not by a corporation or government. 

For this reason it is important that the users:

1. Own and control the data that their daemons collect.
2. Own and control the source code and neural networks running on the daemon.
