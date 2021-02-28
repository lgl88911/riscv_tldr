# add[i]

> 加法.

- 把寄存器 x[rs2]加到寄存器x[rs1]上，结果写入 x[rd]。 忽略算术溢出。 x[rd] = x[rs1] + x[rs2]:

`add rd, rs1, rs2`

- 把符号位扩展的立即数加到寄存器 x[rs1]上，结果写入 x[rd]。 忽略算术溢出。 x[rd] = x[rs1] + sext(immediate):

`addi rd, rs1, immediate`

- 实例:

`add t0,t1,t2`
`add t0,t1,100`
