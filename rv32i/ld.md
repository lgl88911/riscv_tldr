# ld

> 双字加载.

- 从地址x[rs1] + sign-extend(offset)读取八个字节，写入 x[rd]。x[rd] = M[x[rs1] + sext(offset)][63:0]:

`ld rd, offset(rs1)`

