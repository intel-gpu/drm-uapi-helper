# Drm Uapi Helper for intel-dgpu releases

## Main URLs:

[Intel® GPGPU Documents and Releases](https://dgpu-docs.intel.com/ "Intel® software for general purpose GPU capabilities").

[Intel® DGPU Linux Kernel Source Reference](https://github.com/intel-gpu/kernel)

## Goals

* Provide an **unified** view of the i915/xe uAPI available on these reference releases. In especial with the "PRELIM" uAPIs available in i915_drm_prelim.h/xe_drm_prelim.h.
* Establish a **synchronized** update flow of uAPIs with all the user space drivers available in the [Intel® GPGPU Documents and Releases](https://dgpu-docs.intel.com/ "Intel® software for general purpose GPU capabilities") for i915.
* Provides uAPIs for user space consumers of preview xe driver available at https://github.com/ayazahma/xekmd-backports.


## Directory structure

* drm-uapi: make headers_install INSTALL_HDR_PATH=drm-uapi

* i915-shared-headers: Other i915 headers that are usually copied to user space components.

## branches

* **master:**
   i915 uAPIs syncronized with [Intel® GPGPU Documents and Releases](https://dgpu-docs.intel.com/ "Intel® software for general purpose GPU capabilities")

*   **xe:** xe uAPIs syncronized with [xekmd-backports](https://github.com/ayazahma/xekmd-backports ).
