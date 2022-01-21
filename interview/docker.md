# Docker Skills
1. How is Docker different from a virtual machine?
Benefits of Containers:
* Reduced IT management resources.
* Faster spin ups.
* Smaller size means one physical machine can host many containers.
* Reduced & simplified security updates.
* Less code to transfer, migrate, and upload workloads.


| Heavyweight.                |  Lightweight.             |
|:---------------------------:|:-------------------------:|
| Limited performance.	      |  Native performance.      |
| Each VM runs in its own OS.	 All containers share the host OS. |
| Hardware-level virtualization. | OS virtualization.     |
| Startup time in minutes.    | Startup time in milliseconds. |
| Allocates required memory.  | Requires less memory space. |
| Fully isolated and hence more secure. | Process-level isolation, possibly less secure. |

2. How build docker image and pass result to new image?
Multi-stage dockerfile or with ci artifact.

