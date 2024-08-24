# The Fork of the SSD300 v1.1 For PyTorch


It is a part of the AirDetection study. The Main repo can be found [under this link](https://github.com/theATM/AirDetection). Original SSD300 Repository [Here](https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/Detection/SSD)

Training can be done using the main.py script with example parameters:

main.py --data ./data/rsdcoco --batch-size 32 --eval-batch-size 16 --freeze 7 <br>
--epochs 100 --amp --num-workers 5 --log-interval 20 --save ./checkpoints/rsd --save-interval 5 <br>
--weights ./pretrained/coco/nvidia_ssdpyt_amp_200703_coco2017.pt --num-classes 6 --train-set-size 7213 <br>
--evaluation 0 5 10 25 50 75 100 150 199 --multistep 25 50 100 150 <br>


### Results of the Best SSD Model on the RSD-GOD dataset

![image](https://github.com/theATM/NviSSD/assets/48883111/8fcacbbc-2b8c-4fe3-af86-00ea53bb7acb)


### Detection Examples

![image](https://github.com/theATM/NviSSD/assets/48883111/fa710736-d77c-4c72-b1ff-6adc23953370)


* Pretrained S21 Model Donwnload [Here](https://drive.google.com/file/d/1TVtVp_qJ0GdEV0s-6AZsdF_A8kXXnT4U/view?usp=sharing) 


* Original README [Here](README_ORIGINAL.md)

