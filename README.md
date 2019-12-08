# fpga-hiscore

This is a SystemVerilog solution to support high scores found in arcade games.

<p align="center">
<img src="https://i.imgur.com/DklV94U.png" width="350px" alt="MiSTer Enhanced Experience Logo">
</p>

**fpga-hiscore** is part of the **MiSTer Enhanced Experience project** aimed at improving the MiSTer experience. For more information, please check out the [Enex wiki](https://github.com/eniva/MisSTer_Guides/wiki/Enhanced-Experience-Project).

**Features**
=============
- High score support
- Save/Load scores

**Implementation**
=============

```systemverilog
HISCORE #() hiscore (
	.clk(clk_sys),
	.reset(reset),
	.enable(hiscore_en),
	.addrinput(),
	.datainput(),
	.db(),
);
```

[WIP]
