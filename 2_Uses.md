## What can we do with it?

* Execute an arbitrarily deep neural network
* Execute the network on the SnapdragonTM CPU, the AdrenoTM GPU or the HexagonTM DSP.
* Debug the network execution on x86 Ubuntu Linux
* Convert Caffe, Caffe2, ONNXTM and TensorFlowTM models to a SNPE Deep Learning Container (DLC) file
* Quantize DLC files to 8 bit fixed point for running on the Hexagon DSP
* Debug and analyze the performance of the network with SNPE tools
* Integrate a network into applications and other code via C++ or Java

## Meaning of the line: "Quantize DLC files to 8 bit fixed point for running on the Hexagon DSP"
* Quantization is a process of reducing the number of bits used to represent data while preserving essential information.
*  "8-bit fixed point" means that each value in the data will be represented using 8 bits and will be interpreted as a fixed-point number.
*  The processed data, now quantized to 8-bit fixed point, is intended to be executed on the Hexagon DSP. This is a specialized digital signal processor designed by Qualcomm.

