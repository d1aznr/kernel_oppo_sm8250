# SPDX-License-Identifier: GPL-2.0-only

ccflags-y += -I$(srctree)/techpack/camera-oppo/include/uapi
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_utils
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_cpas/include
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_sensor_module/cam_sensor_io
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_sensor_module/cam_res_mgr
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_sensor_module/cam_sensor_utils
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_req_mgr
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_sensor_module/cam_cci
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_smmu
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_core/
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_sensor_module/cam_ois/
ccflags-y += -I$(srctree)/techpack/camera-oppo/drivers/cam_sensor_module/oplus/cam_ois/

obj-$(CONFIG_SPECTRA_CAMERA) += HighLevelCmd.o DownloadCmd.o E2PromCmd.o

CFLAGS_REMOVE_HighLevelCmd.o := -mgeneral-regs-only
CFLAGS_REMOVE_DownloadCmd.o := -mgeneral-regs-only
CFLAGS_REMOVE_E2PromCmd.o := -mgeneral-regs-only
CFLAGS_HighLevelCmd.o += -mno-implicit-float
CFLAGS_DownloadCmd.o += -mno-implicit-float
CFLAGS_E2PromCmd.o += -mno-implicit-float
