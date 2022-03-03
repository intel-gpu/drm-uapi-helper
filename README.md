# Drm Uapi Helper for intel-dgpu releases

## Main URLs:

[Intel® GPGPU Documents and Releases](https://dgpu-docs.intel.com/ "Intel® software for general purpose GPU capabilities").

[Intel® DGPU Linux Kernel Source Reference](https://github.com/intel-gpu/kernel)

## Goals

* Provide an **unified** view of the i915 uAPI available on these reference releases. In especial with the "PRELIM" uAPIs available in i915_drm_prelim.h.
* Establish a **synchronized** update flow of these uAPIs with all the user space drivers available in the [Intel® GPGPU Documents and Releases](https://dgpu-docs.intel.com/ "Intel® software for general purpose GPU capabilities").

## Directory structure

* drm-uapi: make headers_install INSTALL_HDR_PATH=drm-uapi

* i915-shared-headers: Other i915 headers that are usually copied to user space components.
