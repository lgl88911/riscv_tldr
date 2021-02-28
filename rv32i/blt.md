# blt

> 小于时分支.

- 若寄存器 x[rs1]的值小于寄存器x[rs2]的值（均视为二进制补码），把 pc的值设为当前值加上符号位扩展的偏移 offset。if (rs1 <s rs2) pc += sext(offset):

`blt rs1, rs2, offset`

- 若寄存器x[rs1]的值小于寄存器 x[rs2]的值（均视为无符号数），把 pc的值设为当前值加上符号位扩展的偏移offset。if (rs1 <u rs2) pc += sext(offset):

`bltu rs1, rs2, offset`

- 实例:

`blt t0, t1, lable`
`bltu t0, t1, lable`
