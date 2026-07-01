Traditional convolution operations are an essential part of image processing and deep learning, 
but they are often slow and require a lot of memory and hardware resources. This makes them 
less suitable for real-time and low-power applications. To solve this problem, this project uses 
a less complex method called the Conv-Inheritance technique. 
The main goal of this work is to design and implement three types of Conv-Inheritance 
algorithms using software tools. These algorithms focus on how pixel values can be inherited 
from nearby pixels to reduce calculations while still keeping the image quality. The results are 
analyzed by checking how the image gets reconstructed and how close it is to the original. 
The same logic is then implemented in Verilog hardware, where image data is processed in real 
time. The Verilog model is carefully designed to match FPGA requirements and uses fewer 
logic resources.  
