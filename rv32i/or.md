# or

> 取或.

- 把寄存器 x[rs1]和寄存器x[rs2]按位取或，结果写入x[rd], x[rd]=x[rs1] | x[rs2]:

`or rd, rs1, rs2`

- 把寄存器 x[rs1]和有符号扩展的立即数immediate(只有低12bit有效)按位取或，结果写 入 x[rd]。x[rd]=x[rs1] | sext(immediate):

`ori rd, rs1, immediate`

- 实例:

`or a0, t1, t2`
`ori a0, t1, 0b11011`

