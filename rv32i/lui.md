# lui

> 高位立即数加载.

- 将符号位扩展的20位立即数immediate左移12位，并将低12位置零，写入 x[rd]中。x[rd] = sext(immediate[31:12] << 12):

`lui rd, immediate`

