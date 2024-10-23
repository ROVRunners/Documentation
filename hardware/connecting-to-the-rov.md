---
description: Instructions on how to boot up and connect to the ROV from the surface PC.
---

# Connecting to the ROV



1. Wire it up.
   1. Plug the ROV's power line into the power box and turn it on in the following way:
      1. Flip the black switch
      2. Wait for it to spin up
      3. Flip the silver switch
   2. Plug in the power strip in the Control Box (Yellow box) and make sure it's on
   3. Plug the DVR, monitors, and PC into the power strip.
   4. Plug the HDMI wires into their respective ports.
      1. Green into the PC.
      2. Purple into the DVR.
   5. Plug the Ethernet wires into their ports.
      1. Green into the PC.
      2. Orange into the black and yellow box attached to the DVR.
   6. Press the power button on the PC and let it boot up.
2. Connect the PC to the ROV.
   1. On the PC, open a command terminal.
   2. Run the following commands:
      1. ssh rovrunners@192.168.2.2
         1. If it fails, repeat until it works, possibly closing and reopening the terminal.
      2. ./start.sh
   3. Open VSCode on the PC.
   4. Navigate to the 'main.py' file in the automatically opened repository.
   5. Press the run arrow at the top of the screen.

