# arm64-kernel-tools

Cross compilation of latest linux kernel for arm64 devices

# Kernel Compiler and Installer tools

## Usage:
    - Run 'sudo ./install.sh' to install all dependencies on your amd64 Host.
    - Run 'sudo ./makekernel.sh' on your amd64 Host to download and compile
      the latest availible Kernel and Header files.
    - Copy 'installkernel.sh' and the generated 'Kernel-X.X.X-rcX.zip' files to
      your arm64 device and...
    - Run 'sudo ./installkernel_arm64 Kernel*.zip' on your arm64 device
      to install latest availible Linux Kernel and Headers.
