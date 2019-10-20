## ライブカメラを使いましょう．


```bash
# C++
$ ./imagenet-camera                          # using GoogleNet, default MIPI CSI camera (1280x720)
$ ./imagenet-camera --network=resnet-18      # using ResNet-18, default MIPI CSI camera (1280x720)
$ ./imagenet-camera --camera=/dev/video0     # using GoogleNet, V4L2 camera /dev/video0 (1280x720)
$ ./imagenet-camera --width=640 --height=480 # using GoogleNet, default MIPI CSI camera (640x480)

# Python
$ ./imagenet-camera.py                          # using GoogleNet, default MIPI CSI camera (1280x720)
$ ./imagenet-camera.py --network=resnet-18      # using ResNet-18, default MIPI CSI camera (1280x720)
$ ./imagenet-camera.py --camera=/dev/video0     # using GoogleNet, V4L2 camera /dev/video0 (1280x720)
$ ./imagenet-camera.py --width=640 --height=480 # using GoogleNet, default MIPI CSI camera (640x480)
```

