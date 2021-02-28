# csrc

> 伪指令,CSR寄存器位清0.

- CSR寄存器按照rs位清0，csr = csr & rs:

`csrc csr, rs`

- 实例:

`csrc mie, t0`
