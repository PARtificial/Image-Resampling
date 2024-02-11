# Image-Resampling
This script performs resampling of a 2D digital image using bilinear interpolation. It allows for both upsampling and downsampling by an arbitrary positive float-type scale factor.

## Prerequisite

- MATLAB (This script has been tested on MATLAB R2023a)
- An input image file in PGM, BMP, JPG, or PNG format.

## Usage

1. Place the script `ParyaImageProcessing1.m` in your working directory.
2. Place the image you wish to resample in the same directory or ensure the path to the image is correctly specified in the script.
3. Run the script from the MATLAB command window by typing `ParyaImageProcessing1` or Run from interace.
4. When prompted, enter a positive float-type scale factor. 
5. For the sample results I have used:`0.1` for downsampling, and `20.24` for upsampling.
5. The script will output a resampled image in the same directory as the script, with a filename indicating whether it is upsampled or downsampled along with the scale factor used.
6. After each processing, the script will ask if you wish to process another image. Enter `yes` to continue or `no` to stop.

## Output

- The output images will be saved in the same directory as the script with the following naming convention:
    - `downsampled_image_[scale_factor].png` for downsampled images.
    - `upsampled_image_[scale_factor].png` for upsampled images.
- Replace `[scale_factor]` with the actual scale factor you entered.

## Notes

- The script will continue to prompt for new scale factors until you enter `no` when asked to continue.
