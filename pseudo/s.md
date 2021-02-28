# s{b|h|w|d}

> 伪指令,写全局量.

- 将寄存器rd的内容写入到字节量symbol中, rt为交换寄存器:

`sb rd, symbol, rt`

- 将寄存器rd的内容写入到半字量symbol中, rt为交换寄存器:

`sh rd, symbol, rt`

- 将寄存器rd的内容写入到字量symbol中, rt为交换寄存器:

`sw rd, symbol, rt`

- 将寄存器rd的内容写入到双字量symbol中, rt为交换寄存器:

`sd rd, symbol, rt`


- 实例:

`sb a0, vbyte, t0`
`sh a0, vhalf, t0`
`sw a0, vword, t0`
`sd a0, vdword, t0`
