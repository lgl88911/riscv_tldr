# csrci

> 伪指令,CSR立即数位清0.

- CSR寄存器按照立即数位清0，csr = csr & imm:

`csrci csr, imm`

- 实例:

`csrci mie, 0b11110111`
