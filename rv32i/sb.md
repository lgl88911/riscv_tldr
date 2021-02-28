# sb

> 存字节.

- 将 x[rs2]的低位字节存入内地址x[rs1]+sign-extend(offset)。M[x[rs1]+sext(offset)=x[rs2][7:0]:

`sb rs2, offset(rs1)`

- 实例:

`sb t0, 3(a0)`

