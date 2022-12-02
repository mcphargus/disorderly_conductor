# Disorderly Conductor

> "if you have to pay for it, it sucks, but _never steal_" - Rowdy

This is the computer I build for my bikes. There will be many, and no two are the same. I may start doing commissioned DCs if people are interested.

## ideas

Awesome list (but not really, but really!) of ideas for the Disorderly Conductor. `#todo: make awesome list for this`

### in general

- old rpi (has to be the crappiest / smallest / cheapest rpi, or some similar system on chip equivalent)
- leverage tF out of i2c
    - add uarts and adcs and all the stuff that the pi is missing
    - add esp8266's. Yes, I know they have wifi, but if you use i2c as a communication channel, you free up the wifi for wifi things :-) 
    - add esp01s, arduinos, gps's via i2c 2 uart, dacs for audio (if the rpi i2c supports)
- leverage tF out of usb
- UARTs and sensors for days
- so many wires, and not wires we'd expect. get real janky with it
    - ethernet? of course!
    - rj11 (old phone wire? Hell Yeah!)
    - phono cable (like 1/4")
    - RCA cable
    - speaker wire
    - lamp cord
    - basically put i2c or uart on every type of commonly available wire, just to show that it can be done
    - waterproof it with common stuff that wouldn't be first choice
        - petroleum jelly
- pulls sensors, buttons, ICs, solderable components, everything from harvested electronics
- screens and displays
    - use all of them, combine with other tools, phone front and center
- your phone is the most capable thing that you own from a technilogical and survival perspective
    - even if it doesn't have internet
    - phone + pi = power + pifm with a wire (+ gps, etc)
    - communication with NO INTERNET
    - This is really a whole episode. A love letter to the modern handset.

### power manglement
- power everything with an off-bike battery, charge with bike battery. This leaves the system running when bike stuff is down, and some devices (here's looking at you esp32) can be put into low power mode to monitor the bike's battery and other environmental conditions around the bike.

## 'Disorderly Conductor'? Really guy?

For reals? That name is awesome! How did you come up with it?

> Google searching. Earlier tonight I was working on an idea for episodes, and an idea to use different legal verbs in my episode names popped into my head. I like doing things where I walk through the alphabet, one letter at a time, and think about words that start with it. Pretty sure this is because Teenage Mutant Ninja Turtles is one of my all time favorite movies, and when Donatello and Casey Jones are working on the truck, they call eachother names working through the Alphabet. I did this with my sister for a very long time, and we even pick it up again occasionally. One insult per day via text message.

> Tonight as I was walking through the alphabet, thinking of litigious verbs, I thought to myself, "selph? This is something we could totally automate!" Then I started wandering through word association tools online and tripped over [visuwords](https://visuwords.com/rowdy). 

> "disorderly" was a word that popped up, so I just Googled it. Then, Disorderly Conduct statutes were staring back at me from my shiny Chrome. Conduct? conduct... Conductor! Computers have conductors in them! A conductor leads an orchestra! 

> Kishon is AN ORCHESTRA OF DISORDER. Wild pistons flying according to the laws of physics, guided by metal, thrust into motion by powerful gasoline explosions!!!!!!!! \*sniff\* _it really is beautiful._

Yes. Yes. I did just conduct (ha!) an interview with myself via markdown. Yes, I'm crazy. Is there a point you're trying to make?