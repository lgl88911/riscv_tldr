# csrrs[i]

> 读后置位控制状态寄存器 .

- t = CSRs[csr]; CSRs[csr] = t | x[rs1]; x[rd] = t:

`csrrs rd, csr, rs1`

- t = CSRs[csr]; CSRs[csr] = t | zimm; x[rd] = t(csr寄存器的第5位及更高不变）:

`csrrsi rd, csr, zimm[4:0]`

- 实例:

`csrrs t0, mie, t1`
`csrrs t0, mie, 0b11010`
