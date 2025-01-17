# DeepStream Python Apps

This repository contains Python bindings and sample applications for the [DeepStream SDK](https://developer.nvidia.com/deepstream-sdk).  

SDK version supported: 5.1  

Download the latest release package complete with bindings and sample applications from the [release section](../../releases).  

Please report any issues or bugs on the [Deepstream SDK Forums](https://devtalk.nvidia.com/default/board/209).  

* [Python Bindings](#metadata_bindings)
* [Sample Applications](#sample_applications)

<a name="metadata_bindings"></a>
## Python Bindings

DeepStream pipelines can be constructed using Gst Python, the GStreamer framework's Python bindings. For accessing DeepStream MetaData, 
Python bindings are provided in the form of a compiled module which is included in the DeepStream SDK. This module is generated using [Pybind11](https://github.com/pybind/pybind11).  

<p align="center">
<img src=".python-app-pipeline.png" alt="bindings pipeline" height="600px"/>
</p>

These bindings support a Python interface to the MetaData structures and functions. Usage of this interface is documented in the [HOW-TO Guide](HOWTO.md) and demonstrated in the sample applications.  
This release adds bindings for decoded image buffers (NvBufSurface) as well as inference output tensors (NvDsInferTensorMeta).

<a name="sample_applications"></a>
## Aplikasi Penghitung Kendaraan Otomatis

<p align="center">
<img src="SentSerial.png" alt="sent serial screenshot" height="400px"/>
</p>

