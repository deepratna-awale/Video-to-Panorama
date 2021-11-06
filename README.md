# Image and Video Stitching
This algorithm runs through a video file, or a set of images, and stitches them together to form a single image. It can be
used for scanning in large documents where the resolution from a single photo may not be sufficient. 

## Requirements
* numpy

* opencv-python>=4.5

* opencv-contrib-python>=4.5

## In Progress
> Fix Image Blurring

> Evaluating frame Quality

> Lens Distortion

> Extract images according to FPS

## Quick Start
Clone > Get Requirements > Run!



```bash
# Clone the repo
git clone https://github.com/deepratnaawale/Video-to-Panorama/ && cd image_stitching

# Install dependencies
pip install -r requirements.txt

# Run the stitching!
python main.py <path to image directory or video files> --display --save
```

[Demo on Youtube](https://youtu.be/DxBgM8vc6R8)

## References
[Automatic Panoramic Image Stitching using Invariant Features](http://matthewalunbrown.com/papers/ijcv2007.pdf)
