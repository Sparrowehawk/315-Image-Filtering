# 315-Image-Filtering
A set of Morphological operation filter using PYNQ Z2 books

Group 3 project on Hardware Accelerated (HWA) Image Filters. We've decided to go with Morphology due to the importance the field has to computer vision (CV) as a whole. 

Inside the Notebook folder is everything you need to run this project, no need to use terminal. To start, download the file, connect ZYNQ board via network mapping / SMB share, drag and drop inside the \jupyter_notebooks and enjoy. It is split into the OpenCV section which is a pure PS implementation; whereas the Simulink section is a PL integrated section which utilises HWA to speed up the processes. Some of the speed gain of using PL is ~0.1s, or ~ 10%, depending on complexity of the image.

Any image can be used; however, it has to be:
- 1920 x 1080p
- 3 bit colours
  - 8 bit Red
  - 8 bit Green
  - 8 bit Blue
- Tested to work with a JPG image; however, high chance other formats work as well 


HLS doesn't work