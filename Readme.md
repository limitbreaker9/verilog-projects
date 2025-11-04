### 1. [Synchronous FIFO](./synchronous_fifo)

A parameterized synchronous FIFO implemented in Verilog, supporting configurable `DEPTH` and `DATA_WIDTH`.

#### Features
- Read / Write pointer architecture with MSB wrap-around technique  
- Proper `full` and `empty` flag generation  
- Synthesizable RTL (tested with **Yosys**)  
- Compatible with open-source simulation tools (Icarus Verilog + GTKWave)

#### Project Files
- `synchronous_fifo.v` — RTL design  
- `fifo_netlist.svg` — Gate-level netlist visualization (Yosys + netlistsvg)  
- `README.md` — Project description & usage  

#### Status
- **RTL:** ✅  
- **Synthesis:** ✅  
- **Testbench:** ✳️ In progress (basic push/pop test coming soon)  

