#
# This file was created by Xilinx Vitis tool.
#


#
# tools
#

RM = rm -f
RMDIR = rm -rf



#
# variables
#

SDCARD_GEN = sdcard_gen
GENERATE_BIF = ::scw::generate_bif

XPFM_PATH = /qtdata03/home/wook/work/project/0_MAIN/FPGA/DemoPlatform_LoopBack/mipi_csi2_rx_subsystem_0_ex.vitis/mipi_demoplatform/export/mipi_demoplatform/mipi_demoplatform.xpfm
SYS_CONFIG = mipi_demoplatform
DOMAINS = standalone_domain
BIF_PATH = /qtdata03/home/wook/work/project/0_MAIN/FPGA/DemoPlatform_LoopBack/mipi_csi2_rx_subsystem_0_ex.vitis/xmipi_vck190_example_1_system/Debug/system.bif

SD_FILES = --elf /qtdata03/home/wook/work/project/0_MAIN/FPGA/DemoPlatform_LoopBack/mipi_csi2_rx_subsystem_0_ex.vitis/xmipi_vck190_example_1/Debug/xmipi_vck190_example_1.elf,versal_cips_0_pspmc_0_psv_cortexa72_0

#
# primary build targets
#

package:
	-@echo Generating BOOT.BIN in system project is not supported for versal devices. Use the bootgen utility to create a bootable image.

clean:
	$(RMDIR) ./_sds
	${RMDIR} package
	${RM} system.bif

.PHONY: all package clean

all: package


