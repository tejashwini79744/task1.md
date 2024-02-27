A 4-week Research Internship on RISC-V using VSDSquadron Mini RISC-V Dev Board BOARD SPECS:

CH32V003F4U6 chip with 32-bit RISC-V core based on RV32EC instruction set

SRAM 2kb onchip volatile sram 16kb external program memory Processor 24 MHz Sink Current per I/O Pin 8 mA Source Current per I/O Pin 8 mA Input voltage (nominal) 5 V I/O voltage 3.3 V Programmer/debugger Onboard RISC-V programmer/debugger, USB to TTL serial port support SPI 1x, PC5(SCK), PC1(NSS), PC6(MOSI), PC7(MISO) I2C 1x, PC1(SDA), PC2(SCL) USART 1x, PD6(RX), PD5(TX) External interrupts 8 external interrupt edge detectors, but it only maps one external interrupt to 18 I/O ports PWM pins 14X Analog I/O pins 10-bit ADC, PD0-PD7, PA1, PA2, PC4 Digital I/O pins 15 Built-in LED Pin 1X onboard user led (PD6) USB 2.0 Type-C TASK 1:

1.To install RISC-V GNU Tool chain

sudo apt install git-all# To install git 
sudo apt-get install autoconf automake autotools-dev curl python3 libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev
git clone https://github.com/riscv/riscv-gnu-toolchain

![image](https://github.com/tejashwini79744/task1.md/assets/161418020/489dd9d8-557a-455c-b2b6-237567ff36b4)

2.To install Yosys

git clone https://github.com/YosysHQ/yosys.git 
cd yosys 
sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev sudo apt-get install tcl-dev sudo apt-get install libreadline-dev! make config-gcc! make sudo make install 

![image](https://github.com/tejashwini79744/task1.md/assets/161418020/6de9dfa5-0ae2-4d99-a1e4-0f77cb47e019)
3.To install iverilog and gtkwave

sudo apt-get install iverilog
sudo apt update sudo apt-get install gtkwave

![image](https://github.com/tejashwini79744/task1.md/assets/161418020/24170e2d-d6e3-4299-b278-ad6e239cf6d4)


![image](https://github.com/tejashwini79744/task1.md/assets/161418020/f3b784d6-0cb0-40d9-9b6f-08ab48d39098)

