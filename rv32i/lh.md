# lh[u]

> 半字加载.

- 从地址x[rs1] + sign-extend(offset)读取两个字节，经符号位扩展后写入 x[rd]。x[rd] = sext(M[x[rs1] + sext(offset)][15:0]):

`lh rd, offset(rs1)`

- 从地址x[rs1] + sign-extend(offset)读取两个字节，经零扩展后写入 x[rd]。x[rd] = M[x[rs1] + sext(offset)][15:0]:

`lhu rd, offset(rs1)`

- 实例:

`lh t0, 2(a0)`
`lhu t0, 2(a0)`

