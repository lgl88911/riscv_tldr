# jalr

> 跳转并寄存器链接.

- 把pc设置为 x[rs1] + sign-extend(offset)，把计算出的地址最低有效位设为 0，并将原 pc+4的值写入 f[rd]， rd默认为 x1。t =pc+4; pc=(x[rs1]+sext(offset))&~1; x[rd]=t:

`jalr rd, offset(rs1)`

- 实例:

`jalr ra, offset(t0)`

