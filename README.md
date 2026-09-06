# Project: SpongeBob Boat

A budget build (under $250) using recycled and scrap parts, designed to resemble SpongeBob's boat while carrying one driver and one passenger a distance of 2 miles over varying inclines and declines.

![SpongeBob Boat](pictures/missing.PNG)

# Design Requirements
- Total budget under $250
- Visual theme matching SpongeBob's boat
- Capacity for one driver and one passenger
- Must travel 2 miles over varying terrain grade (inclines and declines)

# Approach

![SpongeBob Boat](pictures/DrawingsSoilandlace.jpg)

The initial priority was structural: build a frame capable of safely supporting two riders and driving reliably, before addressing aesthetics. We began with a rectangular 40x40 aluminum extrusion frame reinforced with a center beam for added rigidity.

![SpongeBob Boat](pictures/BaciscFrame.jpeg)

This design gave us a frame rigid enough to support two passengers (~400 lbs combined load). The frame was assembled using plasma-cut 90° brackets, slotted T-nuts, and M6 hardware throughout.

<p align="center">
  <img src="pictures/PlamaCut.gif" alt="SpongeBob Boat demo">
</p>

Motor brackets were plasma-cut from 1/8" mild steel to mount a recycled wheelchair motor — a 24V, 250W high-torque unit repurposed for propulsion.

<p align="center">
  <img src="pictures/MotorWithBrak.jpg" alt="SpongeBob Boat">
</p>

At this stage, the chassis was fully assembled and structurally rigid.

<p align="center">
  <img src="pictures/BaseFrame.JPG" alt="SpongeBob Boat">
</p>

One issue that emerged was **canting** — where the wheel angles outward under load, bending the mounting bracket over time.

<p align="center">
  <img src="pictures/CanterProb.jpg" alt="SpongeBob Boat">
</p>

The fix was a simple structural brace: adding a support bar between the two motor mounts. This tied the mounts together and significantly reduced canting under load.

<p align="center">
  <img src="pictures/CanterSol.jpg" alt="SpongeBob Boat">
</p>


## Moving on to PowerTrane and Electronics 

- Originally, we used the control unit from the wheelchair, but this proved to be very unreliable, with constant errors and overheating

<p align="center">
  <img src="pictures/OldconFetKaboom.jpeg" alt="SpongeBob Boat">
</p>
