# TPU-MobilenetSSD
## Environment
1. LattePanda Alpha (Ubuntu16.04) / RaspberryPi3 (Raspbian) / LaptopPC (Ubuntu16.04)
2. Edge TPU Accelerator
3. USB Camera (Playstationeye)
## LattePanda Alpha Core m3 + USB 3.0 + Google Edge TPU Accelerator + MobileNet-SSD v2 + Async mode
**320x240**  
**about 80 - 90 FPS**  
**https://youtu.be/LERXuDXn0kY**  
  
![01](media/01.gif)
## LattePanda Alpha Core m3 + USB 3.0 + Google Edge TPU Accelerator + MobileNet-SSD v2 + Async mode
**640x480**  
**about 60 - 80 FPS**  
**https://youtu.be/OFEQHCQ5MsM**  
  
![02](media/02.gif)

# Environment construction procedure
```bash
$ wget http://storage.googleapis.com/cloud-iot-edge-pretrained-models/edgetpu_api.tar.gz
$ tar xzf edgetpu_api.tar.gz
$ cd python-tflite-source
$ bash ./install.sh
```

# Usage
```bash
$ git clone https://github.com/PINTO0309/TPU-MobilenetSSD.git
$ cd TPU-MobilenetSSD
$ python3 MobileNet-SSD-TPU-async.py
```

# Reference
- Get started with the USB Accelerator https://coral.withgoogle.com/tutorials/accelerator
- Models https://coral.withgoogle.com/models/
- Edge TPU Model Compiler https://coral.withgoogle.com/web-compiler/
- API demos https://coral.withgoogle.com/tutorials/edgetpu-api/#api-demos
- Edge TPU Benchmark https://coral.withgoogle.com/tutorials/edgetpu-faq/
