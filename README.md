<details open>
<summary>Install</summary>

[**Python>=3.6.0**](https://www.python.org/) is required with all
[requirements.txt](https://github.com/yasarberk/License-Plate-Detection-with-YOLOv5/blob/main/requirements.txt) installed including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/):
<!-- $ sudo apt update && apt install -y libgl1-mesa-glx libsm6 libxext6 libxrender-dev -->

```bash
$ git clone https://github.com/yasarberk/License-Plate-Detection-with-YOLOv5
$ cd License-Plate-Detection-with-YOLOv5
$ pip install -r requirements.txt
```

</details>

<details open>
<summary>Inference with detect.py</summary>

```bash
$ python detect.py --source 0  # webcam
                            file.jpg  # image 
                            file.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            'https://youtu.be/NUsoVlDFqZg'  # YouTube
                            'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```

</details>

<details open>
<summary>Sample Outputs</summary>

<div align="center">
<p>
   <img width="640" src="https://github.com/yasarberk/License-Plate-Detection-with-YOLOv5/blob/main/Sample_Outputs/1.jpg"></a>
</p>
<br />
<div align="center">
<p>
   <img width="640" src="https://github.com/yasarberk/License-Plate-Detection-with-YOLOv5/blob/main/Sample_Outputs/2.jpg"></a>
</p>

<div align="center">
<p>
   <img width="640" src="https://github.com/yasarberk/License-Plate-Detection-with-YOLOv5/blob/main/Sample_Outputs/3.jpg"></a>
</p>
 
</details>
