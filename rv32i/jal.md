# jal

> 跳转并链接.

- 把下一条指令的地址(pc+4)放入寄存器ra，然后把 pc设置为当前值加上符号位扩展的的 offset。rd默认为 x1(ra)。x[rd] = pc+4; pc += sext(offset):

`jal rd, offset`

- 实例:

`jal ra,func`

