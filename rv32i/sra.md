# sra

> 算数右移.

- rs2低5位为右移位数，高位忽略。右移后空出位数用x[rs1]的最高位填充。x[rd]=(x[rs1]>>s x[rs2]):

`sra rd, rs1, rs2`

- 立即数shamt低5位为→移位数，第6位必须为0，右移后空出位数用x[rs1]的最高位填充。x[rd]=x[rs1] >>s shamt

`srai rd, rs1, shamt`

- 实例:

`sll t0, t0, t1`
`slli t0, t0, 3`

