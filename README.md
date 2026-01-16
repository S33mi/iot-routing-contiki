iot-routing-contiki contains 3 sub folders
1) doc (all requirend documents files about Routing in Internet of Things (IoT))
2) exp & results (Already performed results and experiments. How to setup code and run experiments)
3) src (all required files that were modified according the proposed solution given in Thesis doc file)


How to Setup
------------------------

Installation
-- Download
1) download conkiti cooja from officail website
                OR
2) open terminal and run the following
3) wget https://github.com/contiki-os/contiki/archive/3.0.zip
-- Install
1)  unzip 3.0.zip
   
2)  rename
   
       mv contiki-3.0 contiki
3)  Install all the required packages for compiling and running ContikiOS.
   
  sudo apt-get install 
	build-essential 
	binutils-msp430 
	gcc-msp430 
	msp430-libc 
	msp430mcu 
	mspdebug 
	gcc-arm-none-eabi 
	gdb-arm-none-eabi 
	openjdk-8-jdk 
	openjdk-8-jre 
	ant 
	libncurses5-dev
  
4) sudo apt-get update
   
5) sudo apt-get upgrade

6) cp /src/net contiki/core/net

-- build

1) cd contiki/tools/cooja
   ant run

-- experiments

1)  create a new simulation based on simulation setup mentioned in thesis doc.
2)  create new motes for the iot network as mentioned in experimental frameworkone by one.
3) run simulation.
4) save runtime results in a file/folder.



Last modification to the code files Year 2018


Any Question?
https://x.com/Seemi_Rauf
