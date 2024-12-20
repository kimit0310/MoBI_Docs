# Logitech C922 Pro HD Stream Webcam

[C922 Pro HD Stream Webcam](https://www.logitech.com/en-us/products/webcams/c922-pro-stream-webcam.960-001087.html)

<center><img src="../img/Video/webcam.png" width='350px'></center>

<br>

<center><img src="../img/Video/webcam_tripod.png" width='350px'></center>

## Specifications

| _Specification_ | Details  |
|------------|-----------|
| _Resolution_| 1080p/30 fps, 720p/ 60 fps, 720p/ 30 fps |
| _Mounting_         | Universal mounting clip (included) compatible with tripods, laptops, LCD, or monitors |
| _Camera Mega Pixel_  | 3 |
| _Lens Type_ |  Full HD Glass Lens 
| _Focus Type_ |  20-step autofocus|
| _Mic Pattern_ | Built-in Dual Stereo |
|_Fields of View_ |  Diagonal: 78° |
| |  Horizonal: 70.42° |
| |  Vertical: 43.3° |
| _Digital Zoom_ | 1.2x |
| _Night Vision_ | No |
| _Onboard Storage_ | No |
| _UVC Support_ | 1.1 |
| _Right Light_| Automatic low-light correction |
| _Video Effects_ | Background replacement with Cameo by Personify |
| _Privacy Shade_ | No |
| _Dimensions_         | 1.73 in (44 mm) x 3.74 in (95 mm) x 2.8 in (71 mm) (including mounting clip) |
| _Weight_         | 5.71 oz (162 g) |
| _Cable_ | USB-A |
| _Cable Length_         | 5 ft (1.5 m) |
| _Compatibility_ | Windows 8 or later|
|  | macOS 10.10 or later| 
|  | ChromeOS|

Documentation from Logitech for setup, downloads, videos, warranty information, and more [here](https://support.logi.com/hc/en-us?webcontent=productgettingstarted&mID=12558).

### In the Box

The following should be included in the box:

- C922 Pro HD Stream Webcam
- USB-A cable
- Tripod
- User documentation
- 3 month premium XSplit license

## Hardware Setup

1. Open your C922 Pro HD Stream Webcam.
2. Plug it in.

## Software Setup

Open ‘Command Prompt’ and cd into the directory that contains the script “**webcam_video.py**”. 
``` py 
>> cd ~/Documents
```

Open LabRecorder.

Run the following at the command line. You must specify a file name for the .avi file.

``` py
>> python webcam_video.py –filename name_your_file
```

Click “update” on LabRecorder and you should see the stream available.

<center>![LabRecorder](img/Video/1.png)</center>
