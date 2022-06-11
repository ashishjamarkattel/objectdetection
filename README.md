## Apple And Oranges Detection 


#### Yolov5

Build a custom model using a Yolov5 model for detecting the apples
and oranges. 





### Test

```
git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
download weights from drive provided
replace detect.py of yolov5 to detect.py from https://github.com/ashishjamarkattel/objectdetection 

## Run

python detect.py --weights (location of weights download from drive)/best.pt --source your video location or images location  and (0 for webcam)


```
#### Drive : https://drive.google.com/drive/folders/1Fbbs3nn69o0c8_P45G5LgE_9nUX1t8w1?usp=sharing
### Improvement 

Model was trained only for 25 epoch higher epoch could give better result.

## Demo


![alt text](https://imgur.com/a/8Mn56Rr)

<blockquote class="imgur-embed-pub" lang="en" data-id="a/8Mn56Rr" data-context="false" ><a href="//imgur.com/a/8Mn56Rr"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>


## License

[MIT](https://choosealicense.com/licenses/mit/)

