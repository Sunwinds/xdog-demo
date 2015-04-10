# xdog-demo
Automatically exported from code.google.com/p/xdog-demo
Recent extensions to the standard Difference-of-Gaussians (DoG) edge detection operator have rendered it less susceptible to noise and increased its aesthetic appeal. Despite these advances, the technical subtleties and stylistic potential of the DoG operator are often overlooked. This paper offers a detailed review of the DoG operator and its extensions, highlighting useful relationships to other image processing techniques. It also presents many new results spanning a variety of styles, including pencil-shading, pastel, hatching, and woodcut. Additionally, we demonstrate a range of subtle artistic effects, such as ghosting, speed-lines, negative edges, indication, and abstraction, all of which are obtained using an extended DoG formulation, or slight modifications thereof. In all cases, the visual quality achieved by the extended DoG operator is comparable to or better than those of systems dedicated to a single style.

This program provides a reference implementation for the extended DoG operator. It was written by Jan Eric Kyprianidis while working as a research scientist for the computer graphics systems group of the Hasso-Plattner-Institut at the University of Potsdam, Germany.

Note: On Mac OS X the NVIDIA Mac OS X CUDA driver is required to run the binary!

Building
Building requires CMake, CUDA, and the Qt cross platform toolkit. Recommended CUDA version is >= 4.0 and recommended Qt version is 4.8.2. The program has been tested to successfully build with Visual Studio 2008 SP1 on Windows, Qt Creator 2.5.0 on Mac OS X, and the default toolchain on Ubuntu 11.04. See build.bat/build.sh to get started. Video processing requires libav or FFmpeg, but is optional.

Related Publications
Winnemöller, H., Kyprianidis, J. E., & Olsen, S. C. (2012). XDoG: An eXtended difference-of-Gaussians compendium including advanced image stylization. Computers & Graphics, 36(6), pp. 740-753."
Winnemöller, H. (2012). XDoG: Advanced image stylization with eXtended Difference-of-Gaussians. In: Proc. Symposium on Non-Photorealistic Animation and Rendering (NPAR), pp. 147-156.
Kyprianidis, J. E. & Döllner, J. (2008). Image abstraction by structure adaptive filtering. In Proc. EG UK Theory and Practice of Computer Graphics, pp. 51–58.
Winnemöller, H., Olsen, S. C., & Gooch, B. (2012). Real-Time video abstraction. ACM Transactions on Graphics, 25(3), pp. 1221-1226.

