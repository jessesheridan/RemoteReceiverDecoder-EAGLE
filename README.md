# RemoteReceiverDecoder-EAGLE
1" square electronics board that contains an Atmel ATxmega192A3 used for connecting to four JR/Spektrum Remote Receivers.
This board takes in the data given by these four receivers, selects the best data and outputs to one serial port at a baud rate of your choosing.
This board has been built and briefly tested.  I had started working on the code for the microcontroller but had not finished.

Being small was the driving factor behind designing the board.  The Atmel AVR XMEGA microcontroller was selected for its 7 UARTs.  I needed 5 in order to connect 4 receivers and one output connection.

The schematic and board layot were created using CadSoft EAGLE.
