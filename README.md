# nondisplaced-femoral-neck-fracture
we unpack our py code to linux executable file for demo testing
#### how to run the pipline
- In a linux environment ( with or without gpu )
- download the executable file "demo", test images ,config file and weights
- run command: 
	```{path to "demo"} --data-path {your folder to test images} --pretrained {your folder to model weights}```
- example: 
```./demo --data-path "/data4/qcc/test/" --pretrained "/data4/qcc/dat/output/dat_tiny/pair-cv10-backbone-merge-turning-lr3e-03-minlr1e-05/ckpt_best_cv1.pth" --cfg "/data4/qcc/dat/configs/dat_tiny.yaml"```
- runing resluts will be displayed as below ( Notes: logs may not be displaed immediately, please wait one minute or more regarding to your device )
![logs.png](https://upload-images.jianshu.io/upload_images/10447075-3ed7051fd61d66c7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

get model weights in https://drive.google.com/drive/folders/1iHyo67v5cWjCvnFYFqpx0ymwj-m-wT2c?usp=sharing
