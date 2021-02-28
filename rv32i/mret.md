# mret

> 机器模式异常返回.

- 从机器模式异常处理程序返回。将 pc设置为CSRs[mepc], 将特权级设置成 CSRs[mstatus].MPP, CSRs[mstatus].MIE置成 CSRs[mstatus].MPIE, 并且将CSRs[mstatus].MPIE为 1; 如果支持用户模式则将 CSR [mstatus].MPP设置为 设置为 0:

`mret`

