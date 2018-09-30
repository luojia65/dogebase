冰岩实习作业

# Day 0

## 遇到的问题

1. Rust语言中，实现父子相关的树结构往往需要涉及到unsafe代码，需要谨慎编写，并对相关的unsafe API有深入的认识。若编写不力，内存安全性将会退化到C语言级别；
2. 解决所有权问题需要使用智能指针等数据结构，而且需要嵌套，可能要考虑使用裸指针，有一定难度；
3. 多线程相关代码可能需要涉及到内部可变性。

## 规划

1. 在内存中实现B+树及相关单元测试代码（1.5d）

