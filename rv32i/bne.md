# bne

> 不相等时分支.

- 若寄存器 x[rs1]和寄存器 x[rs2]的值不相等，把 pc的值设为当前值加上符号位扩展偏移offset。if (rs1 ≠ rs2) pc += sext(offset)：

`bne rs1, rs2, offset`

- 实例:

`bne t0, t1, lable`
