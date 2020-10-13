---
layout: default
---

Many amputees still reject their prescribed prosthetic leg due to a sub-optimal interaction between the socket and the residual limb tissues. Factors like stress, volume fluctuation, and temperature affect the stump-socket interface and reduce the comfort/stability of the prosthetic leg. The socket represents a critical interface between the amputee and the prosthetic device. A socket has to ensure efficient fitting, appropriate load transmission, stability, and control. 

The traditional socket manufacturing process is a labor-intensive process. A prosthetist evaluates the topology of an amputee’s residual limb, takes reference measurements of the stump, and obtains a negative mold of the residual limb. This negative mold is then removed after hardening, and a positive mold is made by filling the cast, and additional modifications are made if required. Lack of skilled personnel can significantly affect the quality of fit, leading to instability and pistoning effect.

A non-contact/remote methodology using 3D reconstruction techniques can eliminate a chunk of manpower, time, and inconsistency involved in the traditional socket manufacturing process. Depth sensors like Kinect, leap, etc can be used to reconstruct the residual limb. Photogrammetry (SFM) can also be used.

# Residual limb scanner

\\
A WPF application for scanning the residual limb of an amputee with Kinect sensor. More details on how to install the application and its usage can be found [here](https://github.com/homebrew-bionics/Residual-Limb-Scanner){:target="_blank"}.

![rlscanner](https://github.com/homebrew-bionics/Residual-Limb-Scanner/blob/main/rlscanner.png)

The application exports a point cloud which can then be converted to a 3D printable stl file with Blender or any preferred application.

