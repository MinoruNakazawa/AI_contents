##　ライブカメラを用いた物体検出

```bash
C++
$ ./detectnet-camera                          # using PedNet,  default MIPI CSI camera (1280x720)
$ ./detectnet-camera --network=facenet        # using FaceNet, default MIPI CSI camera (1280x720)
$ ./detectnet-camera --camera=/dev/video0     # using PedNet,  V4L2 camera /dev/video0 (1280x720)
$ ./detectnet-camera --width=640 --height=480 # using PedNet,  default MIPI CSI camera (640x480)
Python
$ ./detectnet-camera.py                          # using PedNet,  default MIPI CSI camera (1280x720)
$ ./detectnet-camera.py --network=facenet        # using FaceNet, default MIPI CSI camera (1280x720)
$ ./detectnet-camera.py --camera=/dev/video0     # using PedNet,  V4L2 camera /dev/video0 (1280x720)
$ ./detectnet-camera.py --width=640 --height=480 # using PedNet,  default MIPI CSI camera (640x480)
```