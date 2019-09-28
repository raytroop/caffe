## build 
make all -j`nproc`<br>
make test<br>
make runtest<br>
make pycaffe<br>

```bash
$ ldd build/lib/libcaffe.so
linux-vdso.so.1 =>  (0x00007fffd209e000)
libcudart.so.10.0 => /usr/local/cuda/lib64/libcudart.so.10.0 (0x00007f4f4a362000)
libcublas.so.10.0 => /usr/local/cuda/lib64/libcublas.so.10.0 (0x00007f4f45dcc000)
libcurand.so.10.0 => /usr/local/cuda/lib64/libcurand.so.10.0 (0x00007f4f41c65000)
libglog.so.0 => /usr/local/lib/libglog.so.0 (0x00007f4f41a2f000)
libgflags.so.2.2 => /usr/local/lib/libgflags.so.2.2 (0x00007f4f4180e000)
libprotobuf.so.8 => /usr/local/lib/libprotobuf.so.8 (0x00007f4f41515000)
libboost_system.so.1.68.0 => /usr/local/lib/libboost_system.so.1.68.0 (0x00007f4f41311000)
libboost_filesystem.so.1.68.0 => /usr/local/lib/libboost_filesystem.so.1.68.0 (0x00007f4f410f6000)
libleveldb.so.1 => /usr/lib/x86_64-linux-gnu/libleveldb.so.1 (0x00007f4f40e9c000)
liblmdb.so.0 => /usr/lib/x86_64-linux-gnu/liblmdb.so.0 (0x00007f4f40c87000)
libhdf5_serial_hl.so.10 => /usr/lib/x86_64-linux-gnu/libhdf5_serial_hl.so.10 (0x00007f4f40a67000)
libhdf5_serial.so.10 => /usr/lib/x86_64-linux-gnu/libhdf5_serial.so.10 (0x00007f4f405c9000)
libopencv_core.so.3.4 => /usr/local/lib/libopencv_core.so.3.4 (0x00007f4f3ff82000)
libopencv_imgproc.so.3.4 => /usr/local/lib/libopencv_imgproc.so.3.4 (0x00007f4f3f6bc000)
libopencv_imgcodecs.so.3.4 => /usr/local/lib/libopencv_imgcodecs.so.3.4 (0x00007f4f3f268000)
libboost_thread.so.1.68.0 => /usr/local/lib/libboost_thread.so.1.68.0 (0x00007f4f3f03f000)
libstdc++.so.6 => /usr/lib/x86_64-linux-gnu/libstdc++.so.6 (0x00007f4f3ecbd000)
libcudnn.so.7 => /usr/local/cuda/lib64/libcudnn.so.7 (0x00007f4f2737f000)
libboost_python-py27.so.1.58.0 => /usr/lib/x86_64-linux-gnu/libboost_python-py27.so.1.58.0 (0x00007f4f27133000)
libpython2.7.so.1.0 => /usr/lib/x86_64-linux-gnu/libpython2.7.so.1.0 (0x00007f4f26ba5000)
libcblas.so.3 => /usr/lib/libcblas.so.3 (0x00007f4f26983000)
libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 (0x00007f4f2667a000)
libgcc_s.so.1 => /lib/x86_64-linux-gnu/libgcc_s.so.1 (0x00007f4f26464000)
libpthread.so.0 => /lib/x86_64-linux-gnu/libpthread.so.0 (0x00007f4f26247000)
libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f4f25e7d000)
libdl.so.2 => /lib/x86_64-linux-gnu/libdl.so.2 (0x00007f4f25c79000)
librt.so.1 => /lib/x86_64-linux-gnu/librt.so.1 (0x00007f4f25a71000)
/lib64/ld-linux-x86-64.so.2 (0x00007f4f4b2e3000)
libz.so.1 => /lib/x86_64-linux-gnu/libz.so.1 (0x00007f4f25857000)
libsnappy.so.1 => /usr/lib/x86_64-linux-gnu/libsnappy.so.1 (0x00007f4f2564f000)
libsz.so.2 => /usr/lib/x86_64-linux-gnu/libsz.so.2 (0x00007f4f2544c000)
libtbb.so.2 => /usr/lib/x86_64-linux-gnu/libtbb.so.2 (0x00007f4f2520f000)
liblapack.so.3 => /usr/lib/liblapack.so.3 (0x00007f4f24a2c000)
libjpeg.so.8 => /usr/lib/x86_64-linux-gnu/libjpeg.so.8 (0x00007f4f247d3000)
libpng12.so.0 => /lib/x86_64-linux-gnu/libpng12.so.0 (0x00007f4f245ae000)
libtiff.so.5 => /usr/lib/x86_64-linux-gnu/libtiff.so.5 (0x00007f4f24339000)
libjasper.so.1 => /usr/lib/x86_64-linux-gnu/libjasper.so.1 (0x00007f4f240e4000)
libutil.so.1 => /lib/x86_64-linux-gnu/libutil.so.1 (0x00007f4f23ee1000)
libatlas.so.3 => /usr/lib/libatlas.so.3 (0x00007f4f23943000)
libgfortran.so.3 => /usr/lib/x86_64-linux-gnu/libgfortran.so.3 (0x00007f4f23618000)
libaec.so.0 => /usr/lib/x86_64-linux-gnu/libaec.so.0 (0x00007f4f23410000)
libopenblas.so.0 => /usr/lib/libopenblas.so.0 (0x00007f4f2137c000)
liblzma.so.5 => /lib/x86_64-linux-gnu/liblzma.so.5 (0x00007f4f2115a000)
libjbig.so.0 => /usr/lib/x86_64-linux-gnu/libjbig.so.0 (0x00007f4f20f4c000)
libquadmath.so.0 => /usr/lib/x86_64-linux-gnu/libquadmath.so.0 (0x00007f4f20d0d000)
```
---
# Caffe

[![Build Status](https://travis-ci.org/BVLC/caffe.svg?branch=master)](https://travis-ci.org/BVLC/caffe)
[![License](https://img.shields.io/badge/license-BSD-blue.svg)](LICENSE)

Caffe is a deep learning framework made with expression, speed, and modularity in mind.
It is developed by Berkeley AI Research ([BAIR](http://bair.berkeley.edu))/The Berkeley Vision and Learning Center (BVLC) and community contributors.

Check out the [project site](http://caffe.berkeleyvision.org) for all the details like

- [DIY Deep Learning for Vision with Caffe](https://docs.google.com/presentation/d/1UeKXVgRvvxg9OUdh_UiC5G71UMscNPlvArsWER41PsU/edit#slide=id.p)
- [Tutorial Documentation](http://caffe.berkeleyvision.org/tutorial/)
- [BAIR reference models](http://caffe.berkeleyvision.org/model_zoo.html) and the [community model zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo)
- [Installation instructions](http://caffe.berkeleyvision.org/installation.html)

and step-by-step examples.

## Custom distributions

 - [Intel Caffe](https://github.com/BVLC/caffe/tree/intel) (Optimized for CPU and support for multi-node), in particular Intel® Xeon processors.
- [OpenCL Caffe](https://github.com/BVLC/caffe/tree/opencl) e.g. for AMD or Intel devices.
- [Windows Caffe](https://github.com/BVLC/caffe/tree/windows)

## Community

[![Join the chat at https://gitter.im/BVLC/caffe](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/BVLC/caffe?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Please join the [caffe-users group](https://groups.google.com/forum/#!forum/caffe-users) or [gitter chat](https://gitter.im/BVLC/caffe) to ask questions and talk about methods and models.
Framework development discussions and thorough bug reports are collected on [Issues](https://github.com/BVLC/caffe/issues).

Happy brewing!

## License and Citation

Caffe is released under the [BSD 2-Clause license](https://github.com/BVLC/caffe/blob/master/LICENSE).
The BAIR/BVLC reference models are released for unrestricted use.

Please cite Caffe in your publications if it helps your research:

    @article{jia2014caffe,
      Author = {Jia, Yangqing and Shelhamer, Evan and Donahue, Jeff and Karayev, Sergey and Long, Jonathan and Girshick, Ross and Guadarrama, Sergio and Darrell, Trevor},
      Journal = {arXiv preprint arXiv:1408.5093},
      Title = {Caffe: Convolutional Architecture for Fast Feature Embedding},
      Year = {2014}
    }
