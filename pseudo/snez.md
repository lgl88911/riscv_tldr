# snez

> 伪指令,非0置1.

- 如果rs不等于0, rd被设置为1:

`snez rd, rs`

- 实例,a0为0时s0为0, a0为1时s0为1:

`snez s0, a0`
