# lw[u]

> 字加载.

- 从地址x[rs1] + sign-extend(offset)读取四个字节，写入 x[rd](RV64I 经符号位扩展)。x[rd] = sext(M[x[rs1] + sext(offset)][31:0]):

`lw rd, offset(rs1)`

- 从地址x[rs1] + sign-extend(offset)读取四个字节，写入 x[rd](RV64I 经零扩展后)。x[rd] = M[x[rs1] + sext(offset)][31:0]:

`lwu rd, offset(rs1)`

- 实例:

`lw t0, 4(a0)`
`lwu t0, 4(a0)`

