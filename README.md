# FPGA-4-Bit-Full-Adder

This VHDL code implements a **4-bit Ripple Carry Adder** by cascading four 1-bit full adders. It takes two 4-bit binary numbers, `A` and `B`, and a carry-in signal `CIN` as inputs. The adder outputs a 4-bit sum `S` and a carry-out `COUT`.

- **Components**: The `BIT1` component, which represents a 1-bit full adder, is instantiated four times to add each pair of bits from `A` and `B` along with the carry from the previous bit.
- **Carry Propagation**: Each instance passes its carry-out to the carry-in of the next higher bit, allowing the adders to operate in sequence.
- **Final Output**: The final carry-out from the last adder is output as `COUT`.

This ripple carry adder serves as a fundamental building block in digital arithmetic circuits, allowing for binary addition of larger bit-width numbers by cascading additional stages.

https://www.youtube.com/watch?v=Fk3i7EJm9A4
