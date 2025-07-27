# JPEG-Compression-Analysis-with-MATLAB-and-libjpeg-turbo
This repository contains the third lab assignment for the Multimedia Information Systems course, developed by Eray Samet Gündüz.

Overview
In this study, a JPEG image (octavia.jpg) was downloaded and used to analyze the performance of the libjpeg-turbo codec for image compression. The project evaluates the relationship between compression quality and image fidelity by calculating PSNR, SSIM, and MSE values at various quality levels.

Tools and Libraries
MATLAB (used for scripting, analysis, and visualization)
libjpeg-turbo (used for image compression via cjpeg.exe)

Image quality metrics: PSNR (Peak Signal-to-Noise Ratio), SSIM (Structural Similarity Index), and MSE (Mean Squared Error)

Workflow
Image Preparation
The original JPEG image was converted to .ppm format to be compatible with libjpeg-turbo's cjpeg.exe.

Compression Process
Compression was applied using quality levels of 10, 30, 50, 70, and 90.
For each level, the compressed image was saved and analyzed.

Quality Metric Calculation

PSNR and MSE were calculated between the original and compressed images.
SSIM was calculated using downscaled versions of both images (scaled to 50%).

Visualization
MATLAB script performing:
JPEG compression using an external codec
PSNR, SSIM, and MSE calculations
Data plotting for quality vs. bitrate analysis

Notes
Make sure libjpeg-turbo is installed, and the path to cjpeg.exe is correctly set in the script.
The image used (octavia.jpg) and compressed outputs should be in the working directory or properly linked.
