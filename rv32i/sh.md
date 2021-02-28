# lh

> 存半字.

- 将 x[rs2]的低位2字节存入内地址x[rs1]+sign-extend(offset)。M[x[rs1]+sext(offset)=x[rs2][15:0]:

`sh rs2, offset(rs1)`

- 实例:

`sh t0, 3(a0)`

