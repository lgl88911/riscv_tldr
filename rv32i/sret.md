# sret

> 管理员模式例外返回.

- 从管理员模式的例外处程序中返回。将 pc设置为CSRs[sepc], 将特权级设置成 CSRs[sstatus].SPP, CSRs[sstatus].SIE置成 CSRs[sstatus].SPIE, 并且将CSRs[sstatus].SPIE为 1; 如果支持用户模式则将 CSR [sstatus].SPP设置为 设置为 0:

`sret`

