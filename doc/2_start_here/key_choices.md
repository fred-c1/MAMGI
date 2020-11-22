Keys choices motivating this architecture

1. Two distinct blocks: “Processor” and “Logic”  
This allows using almost any microcontroller in the Processor block and almost any FPGA in the Logic block.
<br/><br/>

2. Delta sigma ADC technology for analog measurements (on the high voltage side)  
- This ADC technology is well suited for modern electrical insulation  
- The digital filter (last stage of the Delta sigma ADC function) can easily be implemented in the logic block
<br/><br/>

3. The presence of a “Logic block” (as opposed to just a “Processor”) has the following advantages:
- Since the control of the motor-generator is done in the Logic block, very high speeds/RPM can be achieved
- The logic block can also be used to implement useful peripherals (e.g. RDC function = Resolver to Digital Converter)

