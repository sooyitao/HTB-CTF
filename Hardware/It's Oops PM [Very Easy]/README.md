# It's Oops PM (<font color=green>Very Easy</font>)


## Description

With the location of the underground bunker secured, the crew embarks on the next phase of their plan: assessing the feasibility of creating an underground tunnel to bypass the super mutant camp. They secure samples of water, soil, and air near the area. Scouring the wasteland for salvageable equipment, they stumble upon a dilapidated research facility where they find a cache of environmental sensors. Examining these sensors, the crew discovers they communicate with a satellite and contain a crypto-processor that encrypts their transmissions. After hand-drawing the diagrams and emulating the silicon chip's logic with VHDL, they uncover what appears to be a backdoor in the embedded logic that only triggers when a specific input is given to the system. Determined to exploit this, they turn to their tech specialist. Can you connect to the satellite and activate it?

## Tools Used

- Basic text viewer (Notepad++)

## Skills Learned

- Basic source code analysis

## Steps Taken
1. Analyzing the source codes
2. Found backdoor code from backdoor.vhdl
![alt text](image.png)
3. Connect to IP and input the backdoor code to get flag
![alt text](image-1.png)