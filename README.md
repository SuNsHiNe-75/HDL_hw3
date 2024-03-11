#### Introduction
This is the third assignment for the "Hardware Description Language" course at NSYSU.  
It mainly covers the following tasks:  
- Trace the given Verilog RTL codes of the 16-bit pipelined THUMB processor, and use the given test bench tb_thumb.v to verify the RTL code.
- In the original Verilog, all the four pipelined stages (IF stage, ID stage, EX stage, WB stage) are in a single module. Modify the code so that each pipelined stage is in a separate module, so that the critical path delay of each pipelined stage can be easily measured from the synthesis results of the Synopsys Design Compiler.
- Generate three different synthesis results using different design constraints: area-optimized result, delay-optimized result, and in-between using different constraints in the Synopsys DC. Compare the differences of critical path delays, area, and power for the three different synthesis results.
- Measure the critical path delay of each pipelined stage in the synthesis results.
- Use Synospys PrimeTime to measure the delay and power by providing a sequence of inputs. Compare the delay and power with those obtained from Synospsy Design Compiler.
