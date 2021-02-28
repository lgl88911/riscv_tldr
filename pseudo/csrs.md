# csrs

> 伪指令,CSR寄存器置位.

- CSR寄存器按照rs置位，csr = csr | rs:

`csrs csr, rs`

- 实例:

`csrs mie, t0`
