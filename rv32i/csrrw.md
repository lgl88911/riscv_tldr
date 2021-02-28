# csrrw[i]

> 读后写控制状态寄存器 .

- t = CSRs[csr]; CSRs[csr] = x[rs1]; x[rd] = t:

`csrrw rd, csr, rs1`

- x[rd] = CSRs[csr]; CSRs[csr] = zimm(只写五位的零扩展立即数）:

`csrrwi rd, csr, zimm[4:0]`

- 实例:

`csrrs t0, mie, t1`
`csrrs t0, mie, 0b11010`
