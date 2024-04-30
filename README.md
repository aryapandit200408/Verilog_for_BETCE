# Verilog_for_BETCE
This is a repository that will help you get started with Verilog. This manual has been designed to be done alongside Prof. Mrinal Kanti Naskar Sir's Digital 1 and 2 Lab. 
This would be very helpful for those who want to move forward in the digital electronics domain for research and jobs. 



### Prerequisites
1. You will need to learn the fundamentals of digital circuits. Digital Design by Morris Mano (Verilog and System Verilog Language included) Version should be used a reference.

![81GDEgMEtiL _SY466_](https://github.com/aryapandit200408/Verilog_for_BETCE/assets/115896451/02e282d8-6ce6-4cc2-9aab-821ac41cfd95)

2. If you wish to brush up your concepts through YouTube videos, you can use [playlist 1]() or [playlist 2]()


### Getting Started 
#### 1. Verilog using Vivado
This is perhaps the easiest way to get started since the UI is very easy and you can directly code FPGAs after synthesis and implementation. 
Head over to the Vivado Download page [here](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools.html).

#### 2. [Verilog using EDA Playground](https://www.edaplayground.com/)

#### 3. Verilog using Quartus

#### 4. [HDLbits Online Verilog Simulator](https://hdlbits.01xz.net/wiki/Iverilog)

#### 5. Icarus Verilog


### Learning Verilog 
#### 1. Book - Samir Palnitkar
![81k7JGO7o6L _SY466_](https://github.com/aryapandit200408/Verilog_for_BETCE/assets/115896451/a8c5ef9c-3781-4b6a-963f-200f721fbab8)

#### 2. Youtube Playlist - Hardware Modeling using Verilog [Link](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBELELTSPgzYkQg3HgclQh-5)

#### 3. Website - Chip Verify [Link](https://www.chipverify.com/tutorials/verilog)

### Recommended Roadmap
1. **Prerequisites:** Have your digital circuits-1 concepts ready
2. **Basic Knowledge:** Start with Indranil Sengupta's lecture series [Link](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBELELTSPgzYkQg3HgclQh-5)
You must finish this series up to video number 22, ie. writing test benches. Don't forget to make notes as these would come in handy during interviews. By now the theory part of how a simple Verilog code works and the testbench part would be clear.
3. **Getting suited:** Go to [ProblemSets-HDLBits](https://hdlbits.01xz.net/wiki/Problem_sets) and attempt all the questions.
Try applying you knowledge from the lectures and you own understanding. Please refrain from just getting the answer using chatgpt or the internet, without even trying.
4. **Doubts:** At any point if you feel any doubt on a certain topic, revisit those parts from Samir Palnitkar's Book or ChipVerify's website, or the NPTEL Lecture
5. **Vivado:** After covering HDLBits, you are supposed to move on to vivado.
6. **Assignments:** Try replicating MKN Sir's assignments in Vivado using all the knowledge you have gained till now.
   Let's take an example to illustrate the process:-
   1. Let's say you were given a multiplexer to design in digital lab.
   2. Now you need to design the same in Verilog.
   3. Write codes for:-
      a) Gate Level Implementation*
      b) Dataflow Level Implementation*
      c) Behavioral Implementation
   4. Write the testbench code and perform a simulation to achieve functional coverage.
   5. Elaborate the Design
   6. Run Synthesis for the design for each of the 3 types of codes. If some errors or critical warnings for each of them, debug your code.
   7. Run Implementation for the design for each of the 3 types of codes. If some error or critical warnings for each of the 3 types of implementation, debug your code.
   8. Generate Bitstream for the code. This step will likely cause the most errors however having the knowledge and patience to debug them will be crucial.
   9. After successful bitstream generation, you may now enter the final and most rewarding step: **Coding an FPGA**
      You would have to directly upload your bitstream onto an FPGA. If there are no logical errors, your implementation should work fine.
   10. If you have been able to succesfully implement all the above steps, **then congrats! you have successfully learned to use Verilog! and have just completed your first implementation! Proud of You!**

**In some cases like basic sequential circuits like flip flops, it is impossible to run implementation or generate bitstream for Gate Level or Dataflow Level design. For these behavioral design should only be used. Why?*
