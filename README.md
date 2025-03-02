# Verilog_for_BETCE_Digital_Lab
This is a repository that will help you get started with Verilog. This manual has been designed to be done alongside Prof. Mrinal Kanti Naskar Sir's Digital 1 and 2 Lab. 
This would be very helpful for those who want to move forward in the digital electronics domain for research and jobs. 



## Prerequisites: Knowledge of Digital Circuits
1. You will need to learn the fundamentals of Digital Circuits (specifically Digital Logic Circuits-I and FSM from Digital Logic Circuits-II).
   One great book is Digital Design by Morris Mano (Verilog and System Verilog Language included version).

</div>
<p align="center">
  <a href="https://www.amazon.in/Digital-Design-Introduction-Verilog-System/dp/9353062012/ref=sr_1_1?crid=2ET66C32YEEV7&dib=eyJ2IjoiMSJ9.Ssx9NPh9B4lsajRBxVJ2YpmkLXjKaTrZwYpCV2IXlA7ao0PSVX0OBkGpJY6Ril1FFPdcNuwUEwc9K6r2cmYAuZwsBNy32e_Kzb-8-CjIxaDpueeBoGjqcip4egq3ObsIRHbMNKnWT6E2sph7qjFMpeBSyGWASW-MgcsXrqNLYtx3NJvvQX0wTasVOhA3RPTHgqurPwPQMemrL0pnEHk1MAMr_vUdLzjIk54ewPb6c3E.shMz-kBDSDGZAbUYk_kVM5LF2I3CJjK225YIRq6gLGw&dib_tag=se&keywords=digital+design+by+morris+mano&qid=1714506300&sprefix=%2Caps%2C281&sr=8-1"> <img src="https://github.com/aryapandit200408/Verilog_for_BETCE/assets/115896451/02e282d8-6ce6-4cc2-9aab-821ac41cfd95"> </a>
</p>

2. If you wish to brush up your concepts through YouTube videos, you can use [playlist 1](https://www.youtube.com/watch?v=DBTna2ydmC0&list=PLwjK_iyK4LLBC_so3odA64E2MLgIRKafl) or [playlist 2](https://www.youtube.com/watch?v=M0mx8S05v60&list=PLBlnK6fEyqRjMH3mWf6kwqiTbT798eAOm&ab_channel=NesoAcademy)



## Getting Started 
1. Verilog using Vivado
[Vivado Download page](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools.html).
2. [Verilog using EDA Playground](https://www.edaplayground.com/)
3. Verilog using Quartus
4. [HDLbits Online Verilog Simulator](https://hdlbits.01xz.net/wiki/Iverilog)
5. Icarus Verilog

**Vivado is the easiest to use and lets you code Xilinx FPGAs (BASYS-3 FPGAs available at digital lab can be coded using this), however, if you have technology constraints you could always use online alternatives like EDA Playground.*



## Learning Verilog 
1. Book - Samir Palnitkar
[Old edition pdf](https://robo-tronix.weebly.com/uploads/2/3/2/1/23219916/veriloghdlsamirpalnitkar.pdf)

</div>
<p align="center">
  <a href="https://www.amazon.in/Verilog-Hdl-Samir-Palnitkar/dp/8177589180/ref=sr_1_2?crid=3A2KJAUID548K&dib=eyJ2IjoiMSJ9.MAIPZEcAtCW6bUJ5YKXJ-PlbAq-MTRHC4q-7nA_wDML2VEMBcNPMySbH930Hh3fUQgMYWCfwSULkbt3-jfLWIG5b6Vydi_RL40j3VDFt045nsEBkKj4sBwy6tFMLebgKx4MVt8ppmUYCl_G0VUfc_EQ_byr0QOp6y19ubukTB-SLcdP-7dRrVdxF1Cb3TEA7eqg9FyjO0QeUVU8bx9JLNgELh4tOFwYHtnnn72PkGpc.cugXMmJQ-ToFLfhxqALa2VfzYkYZR2EKC29SBHdX7D4&dib_tag=se&keywords=verilog+hdl+samir+palnitkar&qid=1714505981&sprefix=verilo%2Caps%2C275&sr=8-2"> <img src="https://github.com/aryapandit200408/Verilog_for_BETCE/assets/115896451/a8c5ef9c-3781-4b6a-963f-200f721fbab8"> </a>
</p>

2. Youtube Playlist - Hardware Modeling using Verilog by Indranil Sengupta [Link](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBELELTSPgzYkQg3HgclQh-5)
   a) While in Digital-1: Watch this series until video number 22, ie. writing test benches. Don't forget to make notes as these would be useful during interviews. The theory part of how a simple Verilog code works and the testbench part would be clear.
   b) While in Digital-2: Watch the rest of the lectures. 

Other Resources:-
3. Website - Chip Verify [Link](https://www.chipverify.com/tutorials/verilog)

Try following only one of these resources whichever suits your style.



## Recommended Roadmap
#### Digital Circuits I
1. **Prerequisites:** Have your Digital Circuits-1 concepts ready
2. **Getting suited:** Go to [ProblemSets-HDLBits](https://hdlbits.01xz.net/wiki/Problem_sets) and attempt all the questions.
Try applying you knowledge from the lectures and you own understanding. Please refrain from just getting the answer using chatgpt or the internet, without even trying.
3. **Doubts:** If you have any doubts about a certain topic, revisit those parts from Samir Palnitkar's Book, ChipVerify's website, or the NPTEL Lecture. You may even Google it, for example, the Verilog code for D-Flip Flop, and compare the code with your own to see where you went wrong. Don't copy-paste the code to HDLbits; try to run it and pass all the test conditions on your own.
4. **Vivado:** After covering HDLBits, you are supposed to move on to vivado.
5. **Assignments:** You can try replicating MKN Sir's assignments in Vivado using all the knowledge you have gained till now.
   Let's take an example to illustrate the process:-
   1. Let's say you were given a multiplexer to implement using ICs during last week's lab session.
   2. Now you need to design the same in Verilog.
   3. Write codes for:-
      a) Gate Level Implementation
      b) Dataflow Level Implementation
      c) Behavioral Implementation
   4. Write the testbench code and perform a simulation to achieve functional coverage.
   5. Elaborate the Design
   6. Run Synthesis for the design for each of the 3 types of codes. If there will be some errors or critical warnings for each of them, debug your code.
   7. Run Implementation for the design for each of the 3 types of codes. If some error or critical warnings for each of the 3 types of implementation, debug your code.
   8. Generate Bitstream for the code. This step will likely cause the most errors however having the knowledge and patience to debug them will be crucial.
   9. After successful bitstream generation, you may now enter the final and most rewarding step: **Coding an FPGA**
      You would have to upload your bitstream onto an FPGA directly. If there are no logical errors, your implementation should work fine.
   10. If you have been able to implement all the above steps successfully, **then congrats! you have successfully learned to use Verilog! and have just completed your first implementation! Proud of You!**
With this step, you have covered almost all basic digital components. Now it is time to move into designing intermediate-level systems in Verilog.


#### Digital Circuits II

6. **Learning:** After digital-1, and after learning FSMs. Do the rest of the NPTEL Lectures [Link](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBELELTSPgzYkQg3HgclQh-5)
7. **System Design:** In the Digital Logic Circuits II lab, with each lab session try designing the given system with both the control unit (FSM) and logic unit (DataUnit).
8. **Assignments:** Try replicating MKN Sir's assignments in Vivado using all the knowledge you have gained till now.
   Let's take an example to illustrate the process:-
   1. Let's say you were given a Bus Based System to be designed in the digital lab.
   2. Now you need to design the same in Verilog.
   3. Before jumping into writing code, have the multisim implementation and the basic circuit diagram at hand. In Verilog, your task is to replicate the individual components and ensure all of them are connected appropriately.
   4. Write codes for Gate Level Implementation. Doing gate-level implementation will ensure the lower number of errors during synthesis and make your life much easier. Although doing behavioral coding may reduce the size of the code, but it is imperative as electronics students to have a grasp of the lower levels of abstractions (ie closer to the circuit). Also since you already have the gate-level coded modules from previous codes ready, so it is essentially a game of wiring up the different modules and components.
   5. Write the testbench code and perform a simulation to achieve functional coverage.
   6. Elaborate the Design
   7. Run Synthesis for the design. If some errors or critical warnings for each of them, debug your code.
   8. Run Implementation for the design. If some error or critical warnings for each of the 3 types of implementation, debug your code.
   9. Generate Bitstream for the code. This step will likely cause the most errors however having the knowledge and patience to debug them will be crucial. Look out for the combinational loop error!**
   10. After successful bitstream generation, you may now enter the final and most rewarding step: **Coding an FPGA**
      You would have to upload your bitstream onto an FPGA directly. If there are no logical errors, your implementation should work fine.
   11. If you have been able to implement all the above steps successfully, **then congrats! you have successfully learned to design a system and implement it on Verilog! Proud of You!**
With this step, you have understood how to design intermediate-level systems and that is commendable.

Could you answer these questions? <br>
**In some cases like basic sequential circuits like flip flops, it is impossible to run implementation or generate bitstream for Gate Level or Dataflow Level design. For these behavioral design should only be used: Why?*

***I had this error quite a few times, can you avoid it? How?*

## How to Program in Vivado? How can I code the FPGA?
For this follow this [video](https://www.youtube.com/watch?v=K3miHPhri50)

## Further Reading


### Research Prospects
If you aspire to pursue research in the digital design domain, this is a great time to explore research projects. Here are some potential paths you can consider<ul> 
   <li> Exploring FPGAs 
   <ul> 
      <li> Digital Signal Processing Applications on FPGA </li>
      <li> Accelerating Fast Fourier Transforms on FPGAs </li>
      <li> Image Processing on FPGAs </li>
      <li> ML acceleration on FPGAs </li>
   </ul>
   </li>
   <li>Exploring Computer Architecture and High-Performance Computing Domains (though it won't require direct use of Verilog)
   <ul>
      <li> Exploring GPUs </li>
      <li> Exploring In-Memory Computing </li>
      <li> Exploring Network on Chip Architectures </li>
      <li> Exploring Hardware Security </li>
   </ul>
   </li>
This list is by no means exhaustive. You can join forums like r/FPGA or search for papers on Google Scholar to learn more!
</ul>

## Conclusions

Learning Verilog would open a lot of opportunities for you. Those who will be trying for summer research internships during 2nd year and are interested in research statements involving knowledge of digital may also list any/each of these implementations as singular short projects under the "personal projects" section of your CV. This will certainly increase your chances of selection if you don't have any other relevant projects to show.



<br>
<br>


<p align="center"> 
   Made with ❤️ by Arya Pandit ETCE'26 </p>
<p align="center">
   Feel free to reach out for any doubts or if you want to contribute to this repository! Happy Learning!
</p>
