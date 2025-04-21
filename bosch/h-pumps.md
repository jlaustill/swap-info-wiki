---
title: Bosch H-Pump Info
description: Just a page to document general H Pump info
published: true
date: 2025-04-21T16:36:13.057Z
tags: 
editor: markdown
dateCreated: 2025-04-17T22:18:45.427Z
---

# H-Pumps
## Intro
Pumps are listed in order of ease of use on a Cummins 12 valve or 24 valve. I’m sure there are other pumps out there that will work, these are just the options that I have explored. If you have questions post them in the comments so the info is out there for others. Further information is below the pump list.

## Parts
2-427-010-024 Wiring harness with pigtail

## 0-402-796-043
RP43, 12mm elements, 14mm cam lift, 580cc
Came on Scania 9.0L bus engine
Thousands of miles on this pump with either camshaft, have a good base file
Made 721whp with stock camshaft, very slow rate of injection
Made 943whp with a reground camshaft, this setup rips and drives great
Easiest pump to bolt on, already has the correct pilot diameter
Upper bolt holes just need helicoils removed
Lower bolt holes need redrilled

## 0-402-796-042 & 0-402-796-045
RP43, 12mm elements, 14mm cam lift, 640cc
Should be 1000+whp capable
Only other pump available in North America, still not very common
Came on Volvo D7C
Most aggressive RP43 camshaft I've found yet
Has correct pilot diameter
All bolt holes need to be redrilled
Has a big mount on the pump casting from the factory application, might need to cut it off
Haven't ran on a truck yet

### The 045 Pump has the following ID tag
015 Assembly code or internal control code
BOSCH Manufacturer
0842800119 H Bosch production control / internal number
0 402 796 045 Bosch Pump part number
PES6H120/320RS30 Pump series, plunger size, cam profile, rotation, and governor type
3978796 Customer = Volvo part number

PES Inline Mechanical injection pump
6 number of cylinders
H left-hand rotation
120 Plunger element size (12.0mm)
/320 Camshaft specification degree or stroke
RS governor type RSV-E or RSV-EDC
30 specific governor varian


## 0-402-796-041 & 0-402-796-044
RP43, 11mm elements, 14mm cam lift
Should be 500whp capable with the smaller elements, don't hold me to this
Came on Volvo D7C
Should be the same as the 042/045 pumps aside from smaller elements
Haven't benched or ran on a truck yet

## 0-402-796-207 & 0-402-796-213
RP39, 12mm elements, 18mm cam lift, 660cc
Should be 1000+whp capable
Most accessible pumps in North America
Came on Cummins QST-30
Only difference is 207 has a mechanical lift pump, 213 comes with it blocked off.
Need to weld or plug front oil feed port and drill a new one on the side
Haven't run long enough to dyno, responds similar to 210 pump
Might have issues with getting a low idle due to the plunger helix
Most aggressive H-pump camshaft I've come across
Pilot needs to be machined down to 107mm and bolt heads turned down
Oil drainholes in pilot need to be drilled
Must use RTV to seal pump to case since there's no room to machine an o-ring groove
Upper bolt holes need to be opened up
Lower bolt holes need redrilled

## 0-402-796-206 & 0-402-796-212
Mirror image of 207/213 pumps listed above
Most accessible pumps in North America
Came on Cummins QST-30
Rotation is correct so it should still work
Feed ports will be near the cylinder head, may or may not clear
Lift pump on 206 pump will be against the block so it needs to be blocked off

## 0-402-795-210
RP39, 12mm elements, 18mm cam lift, 680cc
Made 1007whp at 18mm rack travel
Came on MAN TGA engines
Starting to get some miles on this pump, little harder to tune but it’s coming along
Pilot needs to be machined down to 107mm
Might be enough room for a pilot o-ring groove, otherwise seal with RTV
Need to weld or plug front oil feed port and drill a new one on the side
Camshaft is wrong rotation for a Cummins, I swapped in a 207 camshaft
Doesn't need an inlet feed block
Pump housing is already drilled for dual feed
Lift pump will be against the block so it needs to be blocked off

## Notes
- Flow ratings were done on a bench with a 0.7mm orifice in the test nozzle, most pumps rated in the aftermarket are measured with a 0.8mm orifice. Take these numbers with a grain of salt, they would test higher with a larger orifice.
- 12mm is the largest element that was offered on any of these pumps, I went from a 13mm P7100 to a 12mm RP43 and the truck runs harder all around. Element size isn’t everything when you factor in rate of injection and dynamic timing.
- All H-pumps should clear a 12 valve head with no issues, on a 24 valve head the pump casting will likely need to be ground, RP39s are bigger so they take more grinding.
- RP43s have a 35mm shaft taper and RP39s have a 40mm shaft taper. Any good machine shop should be able to recut a P7100 gear for you. Yes, the taper is supposed to be precision ground but I've ran 3 gears machined 3 different ways and none of them slipped.
- I’ve spun the 207, 210, and 043 pumps all north of 4500rpm with no issues
- All H-pumps have 14mm of timing solenoid travel, I've been using a Ford EGR position sensor with a machined block to provide ECU feedback.
- Baldurs DSL1 controller is your best bet for an ECU, I can provide a starting point map for some pumps but different engines and injectors will respond differently.
- Due to the difference in the pump case they all need a different rear pump support than a P7100.
- Most H-pumps have a lift pump that runs off the pump cam, you can run this if you want, I've never tried it and always blocked it off to use an electric pump.
- If you need a timing sensor adapter, rear pump support, lift pump block off, or an inlet feed block I have some for sale.
- Inlet pressure is specified as 45psi, I've run anywhere from 30-70psi with no issues. 70psi is where I leave mine now.
- All pumps have at least a 30* timing swing, some are in the mid 40s. This is largely dependent on the camshaft.
- Don't be afraid of core pumps or used pumps on eBay, every used pump I've purchased so far has only needed a reseal. Purchased a handful of international pumps through eBay, everyone has showed up so far and they won’t let the buyer get screwed either way.
- This all might seem like a lot but I’ve seen what guys are paying for reman pumps with Chinese parts in them, you could come out cheaper with more capability for less if you’re a DIY kinda person.
- I can be reached via [Facebook](https://www.facebook.com/barberautomotivesolutions/about)

### Torque Chart
![pe_toque_chart.png](/pe_toque_chart.png)

### Wiring
#### Main Plug Harness
1. Fuel solenoid Sensor Signal - Green
2. Fuel Solenoid 1 - Brown
3. Timing Solenoid 1 - Blue
4. Timing Solenoid 2 - White
5. Fuel Solenoid Sensor Ground - Black
6. Fuel Solenoid Sensor Positive - Red
7. Fuel Solenoid 2 - Brown/White
