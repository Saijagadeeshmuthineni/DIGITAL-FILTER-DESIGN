# DIGITAL-FILTER-DESIGN

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: M.SAI JAGADEESH

**INTEN ID**: CT08GHS

**DOMAIN**: VLSI

**BATCH DURATION**: DECEMBER 25TH,2024 TO JANUARY 25TH,2025.

**MENTOR NAME**: NEELA SANTHOSH KUMAR

# Finite impulse response (FIR) filters are commonly used in digital signal processing (DSP) applications for noise reduction, signal enhancement, and data compression. In this post, we will show how to design a basic FIR filter in Verilog and SystemVerilog, as well as a pipelined FIR filter.A combinational FIR filter is a filter that processes all the input samples in a single clock cycle. The output of a combinational FIR filter is the convolution of the input signal and the impulse response of the filter. The impulse response is defined by a set of coefficients, and the number of coefficients determines the order of the filter.A pipelined FIR filter is a filter that processes the input samples over multiple clock cycles. The output of a pipelined FIR filter is the convolution of the input signal and the impulse response of the filter, just like a combinational FIR filter. However, a pipelined FIR filter requires more clock cycles to produce the output.The pipelined FIR filter is implemented by dividing the impulse response into multiple stages and processing each stage in a separate clock cycle. The output of each stage is stored in a register, and the register values are combined to produce the final output.In addition to pipelining the filter stages, we can also pipeline the summation of the filter outputs. This can reduce the critical path and increase the clock frequency of the filter. 
