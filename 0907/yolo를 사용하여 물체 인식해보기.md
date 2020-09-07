# yolo를 사용하여 물체 인식해보기

## 1. Python 설치

* python 3.7.7 버젼 다운
* Add Python 3.7 to PATH 체크

##  2. tensorflow 설치

* pip install tensorflow==2.0.0	
* pip install tensorflow-gpu=2.0.0
  * 더 빠르게 설치 할 수 있다. 
* pip install opencv-python
* pjreddie.com/media/files/yolov3.weights
  * yolo 가중치 파일 다운
* github.com/zzh8829/yolov3-tf2
* yolov3.weights 파일 복사 후 data폴더에 붙여넣기
* cmd 압축을 풀어준 경로로 이동 
* python convert.py
* python detect_video.py --video 0

## 3. 참고

