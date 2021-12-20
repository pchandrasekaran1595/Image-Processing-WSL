- Assumes all necessary prerequisites are installed.

- After starting up the ubuntu terminal instance, switch to appropriate folder and run `. setup.sh`

- Compile and Build executable with `. build.sh`

- Run Executable with `./app -args <value>`

<br>

## **CLI Arguments**

<br>

- `--file, -f` - Image Filename (including extension)

<br>

- `--gauss-blur, -gb` &nbsp; - Gaussian Blur Kernel Size,Gaussian SigmaX(Optional)
- `--avg-blur, -ab` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Average Blur Kernel Size 
- `--median-blur, -mb` - Median Blur Kernel Size

<br>

- `--gamma, -g` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Gamma Value
- `--linear, -l` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Linear Contrast Alpha
- `--clahe, -ae` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Cliplimit,Tile Grid Size(Optional)
- `--hist-equ, -he` - Histogram Equalization Flag

<br>

- `--hue` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Hue Multiplier
- `--saturation, -sat` - Saturation Multiplier
- `--vibrance, -v` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Vibrance Multiplier

<br>

- `--sharpen, -sh` - Sharpen Kernel Size

<br>

- `--width, -w` &nbsp; - New Width
- `--height, -h` - New Height
