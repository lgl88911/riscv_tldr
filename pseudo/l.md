# l{b|h|w|d}

> 伪指令,读取全局量.

- 将字节量symbol读取到寄存器rd中:

`lb rd, symbol`

- 将半字量symbol读取到寄存器rd中:

`lh rd, symbol`

- 将字量symbol读取到寄存器rd中:

`lw rd, symbol`

- 将双字量symbol读取到寄存器rd中:

`ld rd, symbol`


- 实例:

`lb s0, vbyte`
`lh s0, vhalf`
`lw s0, vword`
`ld s0, vdword`
