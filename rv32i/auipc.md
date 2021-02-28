# auipc

> PC加立即数.

- 把符号位扩展的20 位（左移 12 位）立即数加到 pc上，结果写入 x[rd]。x[rd] = pc + sext(immediate[31:12] << 12):

`auipc rd, immediate`


- 实例:

`auipc t0,0`

