# yolov5-streamlit

Deploy [YOLOv5](https://github.com/ultralytics/yolov5/releases/tag/v5.0) detection with [Streamlit](https://github.com/streamlit/streamlit)

教學網址： <https://xugaoxiang.com/2021/08/27/yolov5-streamlit/>

# 線上體驗

體驗網址： <https://share.streamlit.io/xugaoxiang/yolov5-streamlit/main/main.py>

# 安裝依賴

```
# 本機安裝的話，請將opencv-python-headless改成opencv-python
pip install -r requirements.txt
```

如果有`GPU`的话，将`torch`替换成`gpu`版本可加速检测

# 執行指令

```
streamlit run main.py
```

**圖片檢測**

![streamlit yolov5 image detection](data/images/image.png)

**視頻檢測**

![streamlit yolov5 video detection](data/images/video.png)
