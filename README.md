
# PYNQ-Sobel for PYNQ 2.6

A demo for accelerating sobel in xilinx's fpga pynq.

This is nearly identical to Clancy Lea's [original project](https://github.com/clancylea/pynq-sobel/). Small bits are changed for it to run on PYNQ 2.6, on a PYNQ-Z1 board.

----

Original readme from Clancy,

# pynq-sobel
A demo for accelerating sobel in xilinx's fpga pynq  
  ![system](https://github.com/clancylea/pynq-sobel/blob/master/picture/system.jpg)

# 1.clone or download this repo
# 2.change the bit and picture path via your path

      #the bitstream path (The name of .tcl must be same as the name of .bit)
      overlay = Overlay("/home/xilinx/jupyter_notebooks/sobel/sobel.bit")
      
      #image path
      orig_img_path = "/home/xilinx/jupyter_notebooks/sobel/test_1080p.bmp"

# 3.run all and check the result

   ![result](https://github.com/clancylea/pynq-sobel/raw/master/picture/result.png)
   
*rebuild this prj reference：**vivado** repo
