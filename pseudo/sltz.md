# sltz

> 伪指令,小于0置1.

- 如果rs小于0, rd被设置为1:

`sltz rd, rs`

- 实例,a0大于等于0时s0为0, a0小于0时s0为1:

`sltz s0, a0`
