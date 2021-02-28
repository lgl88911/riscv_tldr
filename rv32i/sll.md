# sll

> 逻辑左移.

- rs2低5位为左移位数，高位忽略。左移后空出位数补0。x[rd]=x[rs1] << x[rs2]:

`sll rd, rs1, rs2`

- 立即数shamt低5位为左移位数，第6位必须为0，左移后空出位数补0。x[rd]=x[rs1] << shamt

`slli rd, rs1, shamt`

- 实例:

`sll t0, t0, t1`
`slli t0, t0, 3`

