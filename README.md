# 5-stage-PipelineCPU
這次 Project 使用 VerilogHDL 撰寫，以 Midterm Project 所設計之 ALU
Design 為基礎， 參考課本 Chapter 4 與課程講義之 Pipelined Datapath，設計一
個 Pipelined MIPS-Lite CPU。透過本次的分組作業讓我們能夠熟悉 VerilogHDL
的語法並能夠靈活運用。
二、方法
(1)設計重點說明:
利用老師的 Single Cycle CPU 加入 4 個 Pipeline Register 來實現本次
Final Project 的 PipelineCPU 並且實現下列 16 道 MIPS 指令
a) Integer Arithmetic: add, sub, and, or, srl, slt, ori
b) Integer Memory Access: lw, sw
c) Integer Branch: beq, j, jr
d) Integer Multiply/Divide: divu
e) Other Instructions: mfhi, mflo, nop

<img width="788" height="1119" alt="image" src="https://github.com/user-attachments/assets/dec0525b-5664-4869-b74d-7d15efe1bcc3" />
