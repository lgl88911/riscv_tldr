# lw

> 存字.

- 将 x[rs2]的低位4字节存入内地址x[rs1]+sign-extend(offset)。M[x[rs1]+sext(offset)=x[rs2][31:0]:

`sw rs2, offset(rs1)`

- 实例:

`sw t0, 4(a0)`

