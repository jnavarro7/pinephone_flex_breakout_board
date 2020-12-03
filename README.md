# pinephone_flex_breakout_board
## Flex PCB breakout board for the PinePhone from Pine64
The PinePhone is an smart phone that supports the major Linux for mobile distributions. [Pine64 - PinePhone](https://www.pine64.org/pinephone/)

The PinePhone exposes power, an interrupt pin and an I2C port on the back of it. 
This Flex board was designed to be able to expose these pins outside of the PinePhone with even the back cover on. 

As fas as I know there is no CAD files available so I had to measure directly on the PinePhone to create this prototype, and then use the method of printing the PCB in 1:1 scale for measures. 

![Paper PCB 1 to 1](/pictures/paper_1to1.JPG)
![Paper PCB outside](/pictures/paper_outside.JPG)

## Pogo Pins
The way the PinePhone exposes power, interrupt and I2C port is via a set of 6 pogo pins that stick out on the back of the PinePhone. 

![Pogo Pins](/pictures/pogopins.JPG)

## Pogo Pins Pinout
The schematic from Pine64 is not very clear and does not states which I2C pin is which so this is still to be confirmed.  Once I know which is DATA and which is CLK I will update the design. 
![Pogo Pins](/pictures/layout.jpg)

## Flex board prototype
The protoype is meant to be mounted with screws using the ones already available in the PinePhone but longer screws will be needed to make a better attachment. 

![Flex Boards](/pictures/flex_boards.JPG)
![Positioning on the back of the PinePhone](/pictures/flex_positioning.JPG)
![Flex Board sticking out](/pictures/flex_outside.JPG)
![Measurements](/pictures/measurements.JPG)

## Next steps
This is only 1 part of the prototype, the other part of the system is sensors boards that will attach to this breakout board and communicate using the I2C protocol. 
![Prototype](/pictures/prototype.JPG)

## Design

The design was created using <a href="https://diptrace.com" title="DipTrace">DipTrace</a>

## Try it for yourself
You can get the flex board from OSH Park using this direct link to order the project. 

<a href="https://oshpark.com/shared_projects/iJymtIab" title="Order boards with OSHPark">Order boards with OSHPark</a>

Remember to order it as a Flex Board!. 

## License

Released under the Creative Commons Attribution 3.0 License
https://creativecommons.org/licenses/by/3.0/