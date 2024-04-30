# Verilog_for_BETCE_Digital_Lab
This is a repository that will help you get started with Verilog. This manual has been designed to be done alongside Prof. Mrinal Kanti Naskar Sir's Digital 1 and 2 Lab. 
This would be very helpful for those who want to move forward in the digital electronics domain for research and jobs. 



### Prerequisites
1. You will need to learn the fundamentals of Digital Circuits (specifically Digital Logic Circuits-I and FSM from Digital Logic Circuits-II).
   One great book is Digital Design by Morris Mano (Verilog and System Verilog Language included version).

[![81GDEgMEtiL _SY466_](https://github.com/aryapandit200408/Verilog_for_BETCE/assets/115896451/02e282d8-6ce6-4cc2-9aab-821ac41cfd95)](https://www.amazon.in/Digital-Design-Introduction-Verilog-System/dp/9353062012/ref=sr_1_1?crid=2ET66C32YEEV7&dib=eyJ2IjoiMSJ9.Ssx9NPh9B4lsajRBxVJ2YpmkLXjKaTrZwYpCV2IXlA7ao0PSVX0OBkGpJY6Ril1FFPdcNuwUEwc9K6r2cmYAuZwsBNy32e_Kzb-8-CjIxaDpueeBoGjqcip4egq3ObsIRHbMNKnWT6E2sph7qjFMpeBSyGWASW-MgcsXrqNLYtx3NJvvQX0wTasVOhA3RPTHgqurPwPQMemrL0pnEHk1MAMr_vUdLzjIk54ewPb6c3E.shMz-kBDSDGZAbUYk_kVM5LF2I3CJjK225YIRq6gLGw&dib_tag=se&keywords=digital+design+by+morris+mano&qid=1714506300&sprefix=%2Caps%2C281&sr=8-1)

2. If you wish to brush up your concepts through YouTube videos, you can use [playlist 1](https://www.youtube.com/watch?v=DBTna2ydmC0&list=PLwjK_iyK4LLBC_so3odA64E2MLgIRKafl) or [playlist 2](https://www.youtube.com/watch?v=M0mx8S05v60&list=PLBlnK6fEyqRjMH3mWf6kwqiTbT798eAOm&ab_channel=NesoAcademy)


### Getting Started 
#### 1. Verilog using Vivado
This is perhaps the easiest way to get started since the UI is very easy and you can directly code FPGAs after synthesis and implementation. 
Head over to the Vivado Download page [here](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools.html).
#### 2. [Verilog using EDA Playground](https://www.edaplayground.com/)
#### 3. Verilog using Quartus
#### 4. [HDLbits Online Verilog Simulator](https://hdlbits.01xz.net/wiki/Iverilog)
#### 5. Icarus Verilog
**Vivado is the easiest to use and lets you code Xilinx FPGAs (BASYS-3 FPGAs available at digital lab can be code using this), however, if you have technology constraints you could always use online alternatives like EDA Playground*

### Learning Verilog 
#### 1. Book - Samir Palnitkar
[Old edition pdf](https://robo-tronix.weebly.com/uploads/2/3/2/1/23219916/veriloghdlsamirpalnitkar.pdf)

[![81k7JGO7o6L _SY466_](https://github.com/aryapandit200408/Verilog_for_BETCE/assets/115896451/a8c5ef9c-3781-4b6a-963f-200f721fbab8)](https://www.amazon.in/Verilog-Hdl-Samir-Palnitkar/dp/8177589180/ref=sr_1_2?crid=3A2KJAUID548K&dib=eyJ2IjoiMSJ9.MAIPZEcAtCW6bUJ5YKXJ-PlbAq-MTRHC4q-7nA_wDML2VEMBcNPMySbH930Hh3fUQgMYWCfwSULkbt3-jfLWIG5b6Vydi_RL40j3VDFt045nsEBkKj4sBwy6tFMLebgKx4MVt8ppmUYCl_G0VUfc_EQ_byr0QOp6y19ubukTB-SLcdP-7dRrVdxF1Cb3TEA7eqg9FyjO0QeUVU8bx9JLNgELh4tOFwYHtnnn72PkGpc.cugXMmJQ-ToFLfhxqALa2VfzYkYZR2EKC29SBHdX7D4&dib_tag=se&keywords=verilog+hdl+samir+palnitkar&qid=1714505981&sprefix=verilo%2Caps%2C275&sr=8-2)

#### 2. Youtube Playlist - Hardware Modeling using Verilog [Link](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBELELTSPgzYkQg3HgclQh-5)

#### 3. Website - Chip Verify [Link](https://www.chipverify.com/tutorials/verilog)

### Recommended Roadmap
1. **Prerequisites:** Have your digital circuits-1 concepts ready
2. **Basic Knowledge:** Start with Indranil Sengupta's lecture series [Link](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBELELTSPgzYkQg3HgclQh-5)
You must finish this series up to video number 22, ie. writing test benches. Don't forget to make notes as these would come in handy during interviews. By now the theory part of how a simple Verilog code works and the testbench part would be clear.
3. **Getting suited:** Go to [ProblemSets-HDLBits](https://hdlbits.01xz.net/wiki/Problem_sets) and attempt all the questions.
Try applying you knowledge from the lectures and you own understanding. Please refrain from just getting the answer using chatgpt or the internet, without even trying.
4. **Doubts:** At any point if you feel any doubt on a certain topic, revisit those parts from Samir Palnitkar's Book, ChipVerify's website, or the NPTEL Lecture
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

**In some cases like basic sequential circuits like flip flops, it is impossible to run implementation or generate bitstream for Gate Level or Dataflow Level design. For these behavioral design should only be used: Why?*
