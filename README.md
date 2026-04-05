# Full Adder — Verilog HDL

A 1-bit Full Adder implemented in Verilog HDL and verified using Icarus Verilog and GTKWave.
Built as part of my VLSI/RTL Design learning journey.

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 |  0  |  0  |  0   |
| 0 | 0 |  1  |  1  |  0   |
| 0 | 1 |  0  |  1  |  0   |
| 0 | 1 |  1  |  0  |  1   |
| 1 | 0 |  0  |  1  |  0   |
| 1 | 0 |  1  |  0  |  1   |
| 1 | 1 |  0  |  0  |  1   |
| 1 | 1 |  1  |  1  |  1   |

## Files

| File | Description |
|------|-------------|
| `full_adder.v` | RTL design module |
| `full_adder_tb.v` | Testbench for simulation |
| `full_adder.vcd` | Waveform dump file |
| `output_image.png` | GTKWave waveform screenshot |

## Tools Used
- Icarus Verilog
- GTKWave
- VS Code

## Simulation
```bash
iverilog -o full_adder full_adder.v full_adder_tb.v
vvp full_adder
gtkwave full_adder.vcd
```

## Waveform Output
![GTKWave Output](output_image.png)

## Author
**Akash M**
- GitHub: [@Advenarrow](https://github.com/Advenarrow)
- LinkedIn: [Akash M](https://linkedin.com/in/akash-m-ece)
- B.E. ECE — Government College of Engineering Tirunelveli
