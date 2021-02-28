# rdcycle[h]

> 伪指令,读取cycle寄存器(周期计数器).

- 读取rdcycle寄存器值到rd:

`rdcycle rd`

- 读取rdcycle后右移32位后写入到rd:

`rdcycleh rd`

- 实例:

`rdcycle t0`
`rdcycleh t1`
