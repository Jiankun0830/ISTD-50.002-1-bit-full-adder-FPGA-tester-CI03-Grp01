The aim of the project is to test a one bit full adder using mojo FPGA. Mojo has a 3-bit output representing A, B, Cin.The outputs of mojo are used as inputs for one bit full adder, and the outputs of the one bit full adder s, Cout are useed as input for mojo so that we can test the functionality of the adder.The general strategy is to use a finite state machine to toggle between different test states, with each state being passed only when the required outputs are met.