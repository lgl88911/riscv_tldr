# slt[i][u]

> 小于则置位.

- 比较 x[rs1]和 x[rs2]中的数，如果 x[rs1]更小，向 x[rd]写入 1，否则写入 0。x[rd]=(x[rs1]<s x[rs2]):

`slt rd, rs1, rs2`

- 比较 x[rs1]和有符号扩展的 immediate(只有12位)，如果 x[rs1]更小，向 x[rd]写入 1，否则写入 0，x[rd]=(x[rs1]<s sext(immediate))：

`slti rd, rs1, immediate`


- 比较 x[rs1]和有符号扩展的 immediate(只有12位)，以无符号比较。如果 x[rs1]更小，向 x[rd]写入 1，否则写入 0，x[rd]=(x[rs1]<u sext(immediate))：

`sltiu rd, rs1, immediate`


- 比较 x[rs1]和 x[rs2]中的数，以无符号比较.如果 x[rs1]更小，向 x[rd]写入 1，否则写入 0。x[rd]=(x[rs1]<u x[rs2]):

`sltu rd, rs1, rs2`

- 实例:

`slt a0, t0, t1`
`slti a0, t0, 35`
`sltiu a0, t0, 55`
`sltu a0, t0, t1`

