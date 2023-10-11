# simulink-device-drivers
Developing Simulink&reg; Device Driver Blocks: Step-By-Step Guide and Examples

[![View simulink-device-drivers on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/39354-simulink-device-drivers)

This package contains a guide that explains, in a step-by-step fashion, how to develop device driver blocks (blocks that perform target-specific functions when executed on a target platform).
Example drivers for:

-) Arduino digital output,

-) Arduino digital input,

-) Arduino analog output,

-) Arduino encoder read,

are included.

While the examples are built using the Arduino&reg; as the hardware platform (specifically relying on the Simulink Support Package for Arduino), the method applies to any other supported target.

In this guide, the first method to develop device drivers is based on the S-Function Builder block. Following chapters also describe different methods based respectively on the Legacy Code tool, the MATLAB function block, and the System Object block. Advantages and disadvantages of each method are discussed in the guide.

Finally, note that for MATLAB 2013b you will need to apply a fix for the S-Function builder to develop blocks with no input. To do so, go to the following page: http://www.mathworks.com/support/bugreports/1006532 , scroll down to the bottom, and follow the instructions therein.
