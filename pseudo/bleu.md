# ble

> 伪指令,无符号小于等于跳转.

- 以无符号比较，寄存器rs值小于等于rt时跳转到offset:

`bleu rs, rt, offset`

- 实例:

`bleu s0, s1, lable2`
