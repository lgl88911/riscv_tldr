# beq

> 相等时分支.

- 若寄存器x[rs1]和寄存器x[rs2]的值相等，把pc的值设为当前值加上符号位扩展的偏移offset。if (rs1 == rs2) pc += sext(offset):

`beq rs1, rs2, offset`

- 实例:

`beq t0,t1,lable`
