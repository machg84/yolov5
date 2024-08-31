curl -L "https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5s.pt" -o yolov5m.pt

pip install -r requirements.txt

python detect.py --weights yolov5s.pt --source 0
