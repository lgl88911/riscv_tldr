# rdcycle[h]

> 与.

- 将寄存器 x[rs1]和寄存器x[rs2]位与的结果写入 x[rd]。 x[rd] = x[rs1] & x[rs2]:

`and rd, rs1, rs2`

- 把符号位扩展的立即数和寄存器x[rs1]上的值进行位与，结果写入 x[rd]。x[rd] = x[rs1] & sext(immediate):

`andi rd, rs1, immediate`

- 实例:

`and t0,t1,t2`
`and t0,t1,0b100`
