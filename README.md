# bdx-map-animation
An animated map element to present latency between BDx data centres and selected global cities

Embed the element at
https://raw.githubusercontent.com/kholab/bdx-map-animation/main/map-animation-embed.html 

index.js contains a dummy webflow page, with example usage contained.

Data center to city-name translations (we use city-names in the element): 
HKG1 == wong-chuk-hang
HKG2 == kwai-chung
SIN1 == paya-lebar
NKG1 == nanjing 
CAN1 == guangzhou

For adding new lines: 
Search for comments enclosed by "New Line Helper"
- set the dc and city in helper code
- 2 green dots for centre points of bezier curves 
- aqua square for adjusting left dot
- violet square for adjusting right dot
- new positions of line will be logged