Pipeline Processor Simulator

This is a MIPS Processor Simulator without operand forwading.
The Simulator takes three files as input-

a)DCache.txt

b)ICache.txt

c)RF.txt

Steps:

1)Enter the instructions for the processor in the ICache.txt file, filling a byte in every line.

2)Enter the appropriate intial values in the DCache.txt and RF.txt files.

3)Run the processor.cpp file, which will generate two files-

  a)Output.txt : Contains stats for processor
  b)ODCache.txt    : Contains final DCache config