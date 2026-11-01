# Project-Thorax
My first attempt at a custom PCB used to enable the detection of microplastics in different bodies of water tested across many different kinds of water.

This is a unique project state, so I will explain it.
Below is my ship comment that I feel explains the status well:

Hello everyone!
This is my magnum opus --- unfinished.
I hope to finish it soon and ship it to a different YSWS for funding, but for now it is just a concept in software.

I will still explain it, however.

This is meant to be a microplastic detection PCB that uses light spectroscopy to determine whether microplastics are present in water based on machine learning.

I wanted to make the PCB myself to learn the basics of electrical engineering and to also have some design freedom when it came to using specific components. The design was meant to use the very powerful ATSAMD series chip to coordinate many different concurrent processes, such as data transfer, flash memory storage, SD card storage, live ML model usage, Bluetooth data transfer, and data collection using the integrated sensor.

My data-collection plan is to set up a controlled lab environment with a single light source on the board, then take microplastic samples and place them in distilled water. After this, I will conduct hundreds of trials and collect data to see how the light response is received by the sensor. Each material's light response or reflected wavelength will allow the ML model to understand what constitutes a plastic/specifically red plastic, and what is not. The goal is to keep the project and its dependent variables as simple as possible so as not to overcomplicate data analysis and manipulation.

Post data collection, I plan to use the data to train a basic machine learning model on the patterns of how light is reflected on specific materials. This will allow for the distinction between specific material types and complete the project's overall goal of detecting microplastics in water. I intend to refine this later on with more funding and resources available to make this a reality and a golden standard to determine microplastic content in water.

For now, this is goodbye, everyone. It was fun seeing all of your amazing projects, and now you will see mine :)

See you guys soon!

Now that you have read through that, I must explain why a demo wasn't possible, what I'm doing in place of that, and how to get this thing running.

A demo was not possible because I've been bombarded with homework. If I had even had 75 percent of the homework I have right now, this project would likely be complete, amongst many other things. For reference, I'm taking 4 APs, two dual enrollments, organizing a haven(haven.hackclub.com/philly - GO CHECK IT OUT AHHH), youth group lead, library Teen Advisory Board president, and much more I'm probably forgetting. It's self-inflicted, so I have nobody to blame but myself, but that's an explanation, not an excuse.

What I'm doing is making the project files public, because that's literally all I have. I wish I could say I had more, but I don't. There is literally nothing else for me to give to all of you. I wish I could at least give the PCB, but then at that point I could ship, so it is what it is.

If you wanted to get this running, you can place TVS diodes on all the likely-to-be-exposed components and finish the PCB yourself in the PCB editor. A lot of the actual connections have all been done properly based on schematics; it just needs electrostatic discharge protection, so that's why I'm using TVS diodes. Technically, this is good to go right now, but you will absolutely static shock the components and fry them.

Until I figure out TVS diodes, I will be unable to properly ship this project. So I hope to figure that out soon and let you guys know how that goes!
I have attached a build notes document for your potential amusement; it's not all that exciting, but it does have some notes that I made for myself while making the PCB.
https://docs.google.com/document/d/10ZuE0ZeMz8bDbDXp7TKcbCHwWacSMxAw3u6ysEummEY/edit?usp=sharing

This is the end for now, but I will be back to finish this; I promise.
