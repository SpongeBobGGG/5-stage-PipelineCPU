# 5-stage-PipelineCPU

## 一、 專案概述
本專案使用 **VerilogHDL** 撰寫，以期中專案（Midterm Project）所設計之 **ALU Design** 為基礎，參考教材第四章與課程講義之 **Pipelined Datapath**，設計一個 **Pipelined MIPS-Lite CPU**。透過本次分組作業，旨在熟悉 VerilogHDL 語法並強化硬體描述語言之靈活運用能力。

## 二、 方法

### (1) 設計重點說明
於 Single Cycle CPU 架構中加入 **4 個 Pipeline Registers** 以實現 PipelineCPU，並支援下列 16 道 MIPS 指令：

#### a) Integer Arithmetic (整數算術邏輯)
* `add`, `sub`, `and`, `or`, `srl`, `slt`, `ori`

#### b) Integer Memory Access (記憶體存取)
* `lw`, `sw`

#### c) Integer Branch (分支與跳躍)
* `beq`, `j`, `jr`

#### d) Integer Multiply/Divide (乘除運算)
* `divu`

#### e) Other Instructions (其他指令)
* `mfhi`, `mflo`, `nop`

<img width="788" height="1119" alt="image" src="https://github.com/user-attachments/assets/dec0525b-5664-4869-b74d-7d15efe1bcc3" />
