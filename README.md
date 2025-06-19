# object-detection
Object detection in images using YOLOv11

This project detects animals in images using the YOLOv11 object detection model via the [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) interface. 


## How It Works

- Uses YOLOv11 pretrained weights (e.g., `yolo11x.pt`)
- COCO dataset classes are used
- Detects objects in the image
- Maps all animal-like classes to the label `Animal`
- Draws bounding boxes and labels
