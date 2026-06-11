
<div align="center">

# 408 Low-Level Learning Project

<p align="center">
  <img src="https://img.shields.io/badge/Assembly-ARM64-0091BD?style=for-the-badge&logo=arm&logoColor=white" alt="ARM64">
  <img src="https://img.shields.io/badge/Verilog-HDL-2C2255?style=for-the-badge&logoColor=white" alt="Verilog">
  <img src="https://img.shields.io/badge/C-Language-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/CUDA-Parallel-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white" alt="macOS">
  <img src="https://img.shields.io/badge/Platform-ARM64-5C2D91?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square" alt="Status">
</p>

</div>

> 计算机底层学习项目：汇编系统编程、芯片设计、算法数据结构

---

## 项目结构

```
408/
├── CUDA/        # CUDA 并行计算
├── Chip/        # Verilog 芯片设计
├── ISA/         # ARM64 汇编系统编程（进行中）
├── src/         # C 语言算法与数据结构
├── ctos/        # 其他
└── bin/         # 编译后的二进制
```

---

## 1. 汇编系统编程 (ISA/)

在 macOS 上用 ARM64 汇编实现系统级编程，包括内存管理、系统调用、自定义指令解析等。

**已完成：**
- ✅ 堆结构定义与初始化
- ✅ 内存分配（带分割）
- ✅ 内存释放（带相邻合并）
- ✅ Read/Write 系统调用封装
- ✅ 字符/字符串 I/O
- ✅ 模块化设计
- 🔧 自定义指令解析（进行中）

详细计划：[ISA/spec/schedule.md](ISA/spec/schedule.md)

---

## 2. 芯片设计 (Chip/)

用 Verilog 实现简单硬件模块（加法器、UART 等），学习数字电路。

---

## 3. 算法与数据结构 (src/)

经典算法的 C 语言实现。

**已完成：**
- ✅ 插入排序、归并排序
- ✅ 最大子数组
- ✅ 矩阵运算

---

## 4. CUDA 并行计算 (CUDA/)

学习 CUDA 并行编程。

---

## 快速开始

```bash
# 汇编系统编程
cd ISA && ./run.sh

# 算法数据结构
./run.sh
```

---

## 相关文档

- [ARM64 指令集参考](ISA/spec/ISA.md)
- [开发进度计划](ISA/spec/schedule.md)
- [芯片设计文档](Chip/design.md)
