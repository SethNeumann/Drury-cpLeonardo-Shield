The original cpNode used a Leonardo-based protoyping board called a BB-Leo.  Chuck Catania like Leonardo because the
2nd serial port made for easier serial debugging as the cpNode needed D0/D1 (TX/RX) to implement the CMRINet.  In 2021
Modern Device discontinued the BB-Leo, so we moved the basic cpNode to the ProMini resulting in the cpNode-PM, we also made 
an adapter board with a Pro-Mini that fit into a standard cpNode, called a BB-ProMini.

Dennis Drury like the Leonardo and wanted to keep the code compatible, so he designed this shield form factor board that 
plugs onto a standard (Uno form factor) Leonardo.  It supports the I2C chain so you can use standard IOXs (or any other
shield you like if you want to write customer code).  

This is a great complement to cpNode, cpNode-PM, Andrew Deak's MegaNode and of course the classic JLC SMINI and SUSIC.
