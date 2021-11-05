# Image and Video Stitching
This algorithm runs through a video file, or a set of images, and stitches them together to form a single image. It can be
used for scanning in large documents where the resolution from a single photo may not be sufficient. 

## In Progress
Fix Image Blurring
Evaluating frame Quality
Lens Distortion

## Quick Start
Clone > Get Requirements > Run!

## Requirements
numpy
opencv-python>=4.5
opencv-contrib-python>=4.5
yapf
pylint

```bash
# Clone the repo
git clone https://github.com/deepratnaawale/Video-to-Panorama/ && cd ImageStitching

# Install dependencies
pip install -r requirements.txt

# Run the stitching!
python stitching.py <path to image directory or video files> --display --save
```

## Demonstration
Coming soon!

## References
[Automatic Panoramic Image Stitching using Invariant Features](https://www.cs.bath.ac.uk/brown/papers/ijcv2007.pdf)
