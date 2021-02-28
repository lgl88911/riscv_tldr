# csrsi

> 伪指令,CSR立即数置位.

- CSR寄存器按照立即数置位，csr = csr | imm:

`csrsi csr, imm`

- 实例:

`csrs mie, 0b10`
