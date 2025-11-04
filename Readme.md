### 1. [Synchronous FIFO](./FIFO/synchronous fifo)

A parameterized synchronous FIFO implemented in Verilog, supporting configurable `DEPTH` and `DATA_WIDTH`.

#### Features
- Read / Write pointer architecture with MSB wrap-around technique  
- Proper `full` and `empty` flag generation  
- Synthesizable RTL (tested with **Yosys**)  
- Compatible with open-source simulation tools (Icarus Verilog + GTKWave)
 

#### Status
- **RTL:** ✅  
- **Synthesis:** ✅  
- **Testbench:** ✳️ In progress (basic push/pop test coming soon)  

