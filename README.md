# VSD_RISC-V INTERNSHIP

To learn more about the VSDSquadron Mini RISC-V internship projects, you have come to the right place. You will receive all the tools need to gain hands-on expertise with Mini RISC-V throughout the four weeks of this internship.





VSDSQUADRON Mini Board





![307096354-0a8e7a8c-3680-4139-9668-1d09c3c6b431](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/015c3776-3a29-4ea4-8dfd-415664f30c1d)






THE first internship call was held on 16th of feb 2024


# TASK 1

As of 16th feb

1.install RISC-V GNU Toolchain

2.install Yosys

3.install iverilog

4.install gtkwave



# CLONING RISC-V GNU TOOLCHAIN


![Screenshot 2024-03-04 202354](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/c6463f43-eed6-49ac-a912-d71a858de74e)



![Screenshot 2024-03-04 203451](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/2a243be3-1ed7-4ac6-8ee3-6aa6f8b3e740)


# TOOLS

![Screenshot 2024-03-05 165505](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/c15a47b0-c39a-4633-aef1-89ca29ad048f)




![Screenshot 2024-03-05 165809](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/66afba37-75ed-42f1-a411-edbb814d7b03)


# TASK 2

As of 20th feb

BLOCK DIAGRAM

![BD_TL](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/3117ee82-6e77-4727-a641-c38c47c8cb20)

SIGNAL DESCRIPTION

![Screenshot 2024-03-05 201406](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/6333076f-29aa-4354-8870-8c574532b9a7)

FLOW DIAGRAM

![WhatsApp Image 2024-01-11 at 4 20 00 PM](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/50b43a57-34c4-48ca-9255-95f561e3f6a0)


# TASK 3
As of 26th deb

Cloning github files (SKY 130) credit @ https://github.com/kunalg123


![sky130](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/4e3f7852-8208-4e1c-86f2-777867faedeb)

Basic RTL and TEST BENCH Files

![Screenshot 2024-03-08 164819](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/b9c0d4d7-f8c0-483f-9754-51e695edc8fd)


Executing the MUX file

![Screenshot 2024-03-08 172339](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/f4690ed1-f1df-49ef-982a-90c88f109d64)
GTKWave form for a basic mux
![Screenshot 2024-03-08 171809](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/f8d7be4d-b72e-4cb7-8b7f-3ed7c248fa41)


TRAFFIC LIGHT CONTROLLER Verilog Code (INITIAL VERSION)
![Screenshot 2024-03-10 231657](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/12c3aa73-dbb2-499e-9198-6dcb259d4b8a)

TRAFFIC LIGHT CONTROLLER Testbench file
![Screenshot 2024-03-10 231726](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/4756770f-af79-4ebb-b769-b7350bbc4b5e)

GTKWave form for the TRAFFIC LIGHT CONTROLLER
![Screenshot 2024-03-10 231018](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/b172dbeb-e1e1-418b-9620-1091a0e67f97)

# TASK 4
checking design file using GTK wave

![Screenshot 2024-03-13 203412](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/09854953-b76b-4158-b142-8abf092b651b)

Invoke the yosys tool using yosys command

![Screenshot 2024-03-10 112753](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/26b788c2-883e-4468-899b-da58bed1dc70)

Synthesis traffic light controller file

![Screenshot 2024-03-11 224949](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/3b6ce273-3a7d-4063-9738-2fb160d8cb89)

abc exe pass

![Screenshot 2024-03-11 225142](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/a6c1c0e1-2ff2-4cca-bb78-fbce80d5d4fd)

# TASK 5
Task 5 is to synthesis and generate the netlist of the Traffic light controller file


Original RTL codes
![Screenshot 2024-03-13 201721](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/28c1e310-7269-445f-854e-d3e07eaae7f4)

![Screenshot 2024-03-13 201741](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/0afec5d0-9783-4844-b564-caca07c13780)

![Screenshot 2024-03-13 201752](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/74536adb-bb69-4fdc-b961-5288de167920)


Synthesis traffic light controller file

![Screenshot 2024-03-11 224949](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/3b6ce273-3a7d-4063-9738-2fb160d8cb89)

Netlist file of TLC
![Screenshot 2024-03-11 225631](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/eadd6b18-1f9c-415b-a7a0-3bf583dc0d91)

simplified Netlist file of TLC
![Screenshot 2024-03-11 225815](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/f8fa37e3-e367-48b1-bcb0-c267dea533d1)
Realised logic..from dot viewer 
![Screenshot 2024-03-11 225323](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/33a774f8-315d-4d48-abf7-2eeb546410d3)

wave-form

![Screenshot 2024-03-13 204423](https://github.com/balaji-c7/VSD_RISC-V/assets/126571399/fda769c2-fbfb-43b8-97c7-e8a3f8658cb4)
#ACKNOWLEDGMENT


=>MR.Kunal ghosh,Director&Co-founder of VSD Corpration pvt ltd..,

#REFERENCES 

=>GUIDE-Kunal Ghosh, Diretor, VSD Corp. Pvt. Ltd., Contact @=>kunalpghosh@gmail.com

=>TLC Files-Lokesh Maji, M.Tech - VLSI, Batch: 2022-24, IIITB, Contact @=> majilokesh10@gmail.com
