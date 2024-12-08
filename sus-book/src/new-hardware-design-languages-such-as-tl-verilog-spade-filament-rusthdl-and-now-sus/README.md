# New HDLs *Design* Languages such as [TL-Verilog](https://arxiv.org/abs/1811.01780), [Spade](https://spade-lang.org/), [Filament](https://filamenthdl.com/), [RustHDL](https://rust-hdl.org/) and now [SUS](.)
The above opinions on the other styles of hardware design are shared by my colleagues building these new hardware *design* languages. The main differences between them are philosophical: What common hardware constructs and concepts should be abstracted and how? 

One big decision all of these (including SUS) make is going all-in on Synchronous Hardware. A clock becomes a fundamental language construct instead of being a regular wire. A thing most of them also share is a Rust-inspired syntax, and being written in Rust. 