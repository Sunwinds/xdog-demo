Recent extensions to the standard Difference-of-Gaussians (DoG) edge detection operator have rendered it less susceptible to noise and increased its aesthetic appeal. Despite these advances, the technical subtleties and stylistic potential of the DoG operator are often overlooked. This paper offers a detailed review of the DoG operator and its extensions, highlighting useful relationships to other image processing techniques. It also presents many new results spanning a variety of styles, including pencil-shading, pastel, hatching, and woodcut. Additionally, we demonstrate a range of subtle artistic effects, such as ghosting, speed-lines, negative edges, indication, and abstraction, all of which are obtained using an extended DoG formulation, or slight modifications thereof. In all cases, the visual quality achieved by the extended DoG operator is comparable to or better than those of systems dedicated to a single style.

This program provides a reference implementation for the extended DoG operator. It was written by [Jan Eric Kyprianidis](http://www.kyprianidis.com) while working as a research scientist for the [computer graphics systems group](http://www.hpi3d.de) of the [Hasso-Plattner-Institut](http://www.hpi.uni-potsdam.de) at the University of Potsdam, Germany.

![http://wiki.xdog-demo.googlecode.com/git/screenshot.jpg](http://wiki.xdog-demo.googlecode.com/git/screenshot.jpg)

**Note:** On Mac OS X the [NVIDIA Mac OS X CUDA driver](http://www.nvidia.com/object/mac-driver-archive.html) is required to run the binary!

## Building ##

Building requires [CMake](http://www.cmake.org), [CUDA](http://developer.nvidia.com/cuda-toolkit), and the [Qt cross platform toolkit](http://qt.nokia.com). Recommended CUDA version is >= 4.0 and recommended Qt version is 4.8.2. The program has been tested to successfully build with Visual Studio 2008 SP1 on Windows, Qt Creator 2.5.0 on Mac OS X, and the default toolchain on Ubuntu 11.04. See build.bat/build.sh to get started. Video processing requires [libav](http://www.libav.org) or [FFmpeg](http://www.ffmpeg.org), but is optional.

## Related Publications ##

  * [Winnemöller, H.](http://www.adobe.com/technology/people/seattle/winnemoeller.html), [Kyprianidis, J. E.](http://www.kyprianidis.com), & [Olsen, S. C.](http://www.cs.northwestern.edu/~sco590) (2012). [XDoG: An eXtended difference-of-Gaussians compendium including advanced image stylization](http://dx.doi.org/10.1016/j.cag.2012.03.004).  _Computers & Graphics_, 36(6), pp. 740-753."

  * [Winnemöller, H.](http://www.adobe.com/technology/people/seattle/winnemoeller.html) (2012). [XDoG: Advanced image stylization with eXtended Difference-of-Gaussians](http://dx.doi.org/10.1145/2024676.2024700). In: _Proc. Symposium on Non-Photorealistic Animation and Rendering (NPAR)_, pp. 147-156.

  * [Kyprianidis, J. E.](http://www.kyprianidis.com) & [Döllner, J.](http://www.hpi3d.de) (2008). [Image abstraction by structure adaptive filtering](http://www.kyprianidis.com/tpcg2008.html). In _Proc. EG UK Theory and Practice of Computer Graphics_, pp. 51–58.

  * [Winnemöller, H.](http://www.adobe.com/technology/people/seattle/winnemoeller.html), [Olsen, S. C.](http://www.cs.northwestern.edu/~sco590), & [Gooch, B.](http://webhome.cs.uvic.ca/~bgooch) (2012). [Real-Time video abstraction](http://dx.doi.org/10.1145/1141911.1142018). _ACM Transactions on Graphics_, 25(3), pp. 1221-1226.