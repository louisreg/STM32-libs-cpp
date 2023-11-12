# STM32-libs-cpp


## Add STM32 header, linker, startup file and svd to lib:
  todo
  1. If MCU files not found (how to know??):
   - Create a new CubeMX project:
       - Select the target MCU
       - Config clocks and peripherals as needed
       - In "Project Manager":
         - In "Project" select "Toolchain / IDE: Makefile"
         - In "Code Generator" tick "Copy only the necessary library files" and "Generate  [...] per peripheral"
         - In "Advanced Settings" select "LL" instead of "HAL" in Driver Selector

