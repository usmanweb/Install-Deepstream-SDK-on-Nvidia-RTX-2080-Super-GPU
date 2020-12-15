<meta name="google-site-verification" content="iNnkrgmRKfdXmJaZu2YUXCCWVD-IP0BXgX6pi7amvrs" />

# Install Deepstream SDK on Nvidia RTX 2080 Super GPU
(For other GPUs see driver version: https://docs.nvidia.com/deeplearning/cudnn/support-matrix/index.html)

## Follow this tutorial: https://docs.nvidia.com/metropolis/deepstream/dev-guide/text/DS_Quickstart.html#dgpu-setup-for-ubuntu
Follow section dGPU setup for Ubuntu with exception: ## You must install the following components: - Ubuntu 18.04 - GStreamer 1.14.1 - **NVIDIA driver 440.33** - CUDA 10.2 - TensorRT 7.0.X 

## To run DeepStream Python Apps:

Install packages required by all samples:\
   $ sudo apt update\
   $ sudo apt install python3-gi python3-dev python3-gst-1.0 -y\
Optionally install additional dependencies required by specific samples.\
   See README in app's directory for such requirements.\
   $ sudo apt install python3-opencv\
   $ sudo apt install python3-numpy\
   $ sudo apt install libgstrtspserver-1.0-0 gstreamer1.0-rtsp\
   $ sudo apt install libgirepository1.0-dev\
   $ sudo apt install gobject-introspection gir1.2-gst-rtsp-server-1.0

