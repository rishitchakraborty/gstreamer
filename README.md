# gstreamer

Introduction

Hi everyone! Today I'm going to be giving you a crash course in video processing using Python. Coming out of this talk, you'll be able to take video from pretty much any source, decode it, apply visual effects, and display it on-screen. To do this, we're going to be using a library named GStreamer, an incredibly powerful and versatile framework. This is the same tool that the pros use, but don't feel intimidated! GStreamer actually makes it very easy to do impressive things with video and you'll be well on your way to making something great in just the time it takes to watch this talk.

If you fall behind at any point during the live presentation, don't worry! I have a text version of this talk available with the same content and more. There should be a link in the description.


# gstreamer dependencies (Ubuntu)

sudo apt-get install -y libgstreamer1.0-0 \
            gstreamer1.0-plugins-base \
            gstreamer1.0-plugins-good \
            gstreamer1.0-plugins-bad \
            gstreamer1.0-plugins-ugly \
            gstreamer1.0-libav \
            gstreamer1.0-doc \
            gstreamer1.0-tools \
            libgstreamer1.0-dev \
            libgstreamer-plugins-base1.0-dev \
            cmake \
            protobuf-compiler \
            libgtk2.0-dev \
            libgstrtspserver-1.0-dev \
            libx265-dev \
            libz-dev \
            libbz2-dev \
            libgstreamer1.0-dev \
            libgstreamer-plugins-base1.0-dev \
            libgstreamer-plugins-good1.0-dev \
            libgstreamer-plugins-bad1.0-dev \
            ocl-icd-opencl-dev
            


sudo apt install libgstreamer1.0-0 gstreamer1.0-plugins-{base,good,bad,ugly} gstreamer1.0-tools python3-gi gir1.2-gstreamer-1.0
