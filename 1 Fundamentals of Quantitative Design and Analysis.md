# 1 Fundamentals of Quantitative Design and Analysis
## 1.1 Introduction
1. Incredible progress in Computer technology makes it much cheaper to own a personal computer.  

2. Two things make RISC(Reduced Instruction Set Computer) architecture possible:  
- The virtual elimination of assembly language programming reduced the need for object-code compatibility.
- The standardized, vendor-independent operating systems such as Unix and its clone Linux, lowered the cost of bringing out a new architecture.

3. RISC-Reduced Instruction Set Computer: Simpler Instruction Set, makes processors simpler and less costy. Also more efficient in heat management and power consumption. 

4. RISC focuses on two critical performance techniques:  
- instruction level parallelism(pipeline and multiple instruction issue)
- The use of cache

5. The effect of dramatic growth rate of computer performance:  
- Improved the performance of computer users.
- It leads to the new class of computer.
- Improvement of semiconductor technology led the dominance of microprocessor-based computer instead of Mainframe computers and minicomputer.
- It benefits the software development.

6. The renassiance of hardware is over, Intel cancelled its high-performance uniprocessors projects and said that high-performance would be via multiple processors per chip.

7. Different parallelism:
- ILP: Executes multiple instructions from a single program at the same time, using techniques like pipelining and superscalar execution. It focuses on parallelism within a single thread.
- DLP: Performs the same operation on multiple data points. Imaging cutting a line of apples, for CPU, it will cut them one by one, for GPU, it will cut all the apples simultaneously.
- TLP: Executes different threads at the same time on different cores.
- RLP: Handle multiple independent request at the same time.


