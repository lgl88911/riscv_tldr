# riscv_tldr
tldr file for riscv assembly instructions
这是一份基于tldr的riscv汇编指令文件库，将其安装在tldr后，可以通过tldr进行riscv汇编指令的查询。
目前支持RV32I和汇编伪指令。

## 安装
> cd ~
git clone https://github.com/lgl88911/riscv_tldr.git
sudo apt-get install tldr
cp riscv_tldr/rv32i/* ~/.tldr/tldr/pages/common/
cp riscv_tldr/pseudo/* ~/.tldr/tldr/pages/common/

## 使用
和tldr一样简单
> tldr la

如果没有查找到指令，请尝试缩短查找词，只找有意义的关键词例如
>tldr addi
找不到就用
>tldr add


## 贡献和Issue
欢迎修改错误和提交Issue
 
