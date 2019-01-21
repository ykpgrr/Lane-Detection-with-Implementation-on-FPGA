# LANE-DETECTION-ALGORITHMS-ON-FPGA
REALIZATION OF LANE DETECTION ALGORITHMS ON FPGA USING SDSOC AND VIVADO. C++, xfOpenCV, OpenCV, Verilog. <br />

This project realized in C++ using with OpenCV and xfOpenCV Libraries. <br />
It is a sub-task of "REALIZATION OF LANE DETECTION ALGORITHMS ON FPGA USING SDSOC AND VIVADO" graduate project at Istanbul Technical University, June 2018. <br />

Project members: <br />
Yakup GÖRÜR (gorury@itu.edu.tr) - Software and SDSoC  Platform <br />
Mehmet Akif AKKAYA (akifakkaya1@gmail.com) - VIVADO Platform <br />
Sıddıka Berna ÖRS YALÇIN (Advisor) <br />

### LANE-DETECTION-ALGORITHMS-ON-FPGA (This Repository) -Full Project -
1-) Lane Detection (https://github.com/ykpgrr/Lane-Detection.git)<br />
2-) Lane Detection SDSoC FPGA (https://github.com/ykpgrr/LANE-DETECTION-ALGORITHMS-ON-FPGA.git) <br />
3-) Lane-Detection VIVADO FPGA (https://github.com/ykpgrr/Lane-Detection-VIVADO-FPGA.git) <br />

## TODO
- Update Readme <br />
-- x Add Summary of REALIZATION OF LANE DETECTION ALGORITHMS ON FPGA USING SDSOC AND VIVADO <br />
-- Add SDSoC software/hardware diagram on Readme <br />
-- Add Results <br />




# REALIZATION OF LANE DETECTION ALGORITHMS ON FPGA USING SDSOC AND VIVADO
## SUMMARY

The usage rate of image processing algorithms has gained a great impetus with the "OpenCV" library, which is implemented as open source. The lane detection algorithms, which are an advanced driver assistance system, are also one of the algorithms that using image processing techniques. Unfortunately, the image processing algorithms are slow on processors because of the processing intensity of image processing techniques. High-priced hardwares such as "Graphics Processing Unit" (GPU) are used to accelerate this slow operation. But the usage of GPU in projects increases the project costs, so the end user is offered as a product at high price. This situation reduces the usability of image processing techniques and applications in daily life. <br />

In this project, the Zedboard FPGA development card of the ZYNQ-7000 series of Xilinx Company is used as “System on Chip” (SoC) to solve this problem. A lane detection algorithm has been developed as an image processing project, and it has been implemented in the FPGA after this developed algorithm was broken down as software and hardware. <br />

According to the time analysis of the lane detection algorithm, the preprocessing part was implemented in hardware. SDSoC and Vivado platforms were used to make implementation of the developed lane detection algorithm on FPGA. Low level code (Verilog) is used in Vivado platform while high level code (C++) is used in SDSoC platform. In SDSoC platform, the "xfOpenCV" library was also used. The “xfOpenCV” library is a set of 50+ kernels, optimized for Xilinx FPGAs and SoCs, based on the OpenCV computer vision library. The kernels in the xfOpenCV library are optimized and supported in the Xilinx SDSoC Tool Suit.
