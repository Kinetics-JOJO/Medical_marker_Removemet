# Medical_marker_Removemet  
A Medical_marker_Removemet based on Deep image prior  

## Deep image prior  
An implementation of image reconstruction methods from [Deep Image Prior (Ulyanov et al., 2017)](https://arxiv.org/abs/1711.10925) in PyTorch.  

## Requirements  
Python3 with PyTorch, torchvision and NumPy. CUDA and cuDNN are optional (settable within the script in a self-explanatory way) but strongly recommended.  

##Dataset source  
Multi-Modality Ovarian Tumor Ultrasound (MMOTU) image dataset consists of two sub-sets with two modalities, which are OTU_2d and OTU_CEUS respectively including 1469 2d ultrasound images and 170 CEUS images.  
MMOTU ：![MMOTU](https://github.com/cv516Buaa/MMOTU_DS2Net)

##To use
1.Prepare marker mask by using tool such as ImgageJ  
Ovarian Data with Marker：  
![885](https://github.com/Kinetics-JOJO/Medical_marker_Removemet/assets/52592905/fb0bf032-6484-4d14-8509-fd82c28f7389)  
Marker mask generated by Imagej：  
![885](https://github.com/Kinetics-JOJO/Medical_marker_Removemet/assets/52592905/2e74cabb-7d4f-4745-9b0c-4d02a7cbd5b9)  
  
Removement visualization：  
![885](https://github.com/Kinetics-JOJO/Medical_marker_Removemet/assets/52592905/656652fc-3881-48bf-930b-97c543d89e4f)
