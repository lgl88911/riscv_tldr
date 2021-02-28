# lb[u]

> 字节加载.

- 从地址x[rs1] + sign-extend(offset)读取一个字节，经符号位扩展后写入 x[rd]。x[rd] = sext(M[x[rs1] + sext(offset)][7:0]):

`lb rd, offset(rs1)`

- 从地址x[rs1] + sign-extend(offset)读取一个字节，经零扩展后写入 x[rd]。x[rd] = M[x[rs1] + sext(offset)][7:0]:

`lbu rd, offset(rs1)`

- 实例:

`lb t0, 3(a0)`
`lbu t0, 3(a0)`

