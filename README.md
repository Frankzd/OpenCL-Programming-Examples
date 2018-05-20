# OpenCL-Programming-Examples
These are OpenCL Programming Examples for learning.

The codes are running with Visual Stdio 2017,  
you need to setup your tool to make OpenCL porgrams run firstly. 

Codes copied from <The OpenCL Programming Book> are marked with "TOPB".  
if this makes you unhappy, please conntact me to delete.  
  
moving_average_filter1 ("TOPB")  
  >----  function   
    >>---- process one channel data of stock price   
  >---- codes   
    >>---- main.cpp                 : host program  
    >>---- moving_average.cl        : opencl kernel  
    >>---- stock_array1.txt         : test file  

moving_average_filter2 ("TOPB")  
  >---- function  
    >>---- process 4 channels data of stock price at one time  
  ---- codes  
    ---- main.cpp                 : host program  
    ---- moving_average_vec4.cl   : opencl kernel  
    ---- stock_array_4.txt        : test file  
    
moving_average_filter3 ("TOPB")  
  ---- function  
    ---- process 8 channels data of stock price based on kernel "moving_average_vec4.cl"  
  ---- codes  
    ---- main.cpp                 : host program  
    ---- moving_average_many.cl   : opencl kernel  
    ---- stock_array_many.txt     : test file  

moving_average_filter4 ("TOPB")  
  ---- function  
    ---- process 8 channels data of stock price based on kernel based on parallel model  
  ---- codes  
    ---- main.cpp                 : host program  
    ---- moving_average_vec4_para.cl : opencl kernel  
    ---- stock_array_vec4_par.txt : test file  






