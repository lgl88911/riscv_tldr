# sgtz

> 伪指令,大于0置1.

- 如果rs大于0, rd被设置为1:

`sgtz rd, rs`

- 实例,a0小于等于0时s0为0, a0大于0时s0为1:

`sltz s0, a0`
