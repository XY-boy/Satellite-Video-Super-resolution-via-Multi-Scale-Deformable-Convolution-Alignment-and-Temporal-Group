# Satellite Video Super-resolution via Multi-Scale Deformable Convolution Alignment and Temporal Grouping Projection
## Introuction
This is the official implementation of our paper "Satellite Video Super-resolution via Multi-Scale Deformable Convolution Alignment and Temporal Grouping Projection" published on IEEE Transactions on Geoscience and Remote Sensing (**TGRS**).  

### The network structure  
 ![image](/img/network.png)
 
 ### Quantitive results
 ![image](/img/res1png.png)
 
 ### Qualitive results
 ![image](/img/res2.png)
 #### More details can be found in our paper!
 
 ## Training
```
python main.py
```
 ### Data directory structure
trainset--  
&emsp;|&ensp;train--  
&emsp;&emsp;|&ensp;LR4x---  
&emsp;&emsp;&emsp;| 000.png  
&emsp;&emsp;&emsp;| ···.png  
&emsp;&emsp;&emsp;| 099.png  
&emsp;&emsp;|&ensp;GT---   
&emsp;&emsp;|&ensp;Bicubic4x--- 

testset--  
&emsp;|&ensp;eval--  
&emsp;&emsp;|&ensp;LR4x---  
&emsp;&emsp;&emsp;| 000.png  
&emsp;&emsp;&emsp;| ···.png  
&emsp;&emsp;&emsp;| 099.png  
&emsp;&emsp;|&ensp;GT---   
&emsp;&emsp;|&ensp;Bicubic4x--- 

## Test
```
python eval.py
```

## Citation
If you find our work helpful, please cite:  

## Acknowledgement
Our work is built upon RBPN(https://github.com/alterzero/RBPN-PyTorch) and TDAN (https://github.com/YapengTian/TDAN-VSR-CVPR-2020).  
Thanks to the author for the source code !



 


