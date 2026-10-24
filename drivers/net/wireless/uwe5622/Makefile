# Source: https://github.com/Hiyajomaho-num9/uwe5621ds-rockchip
# Revision: 4c63dfbe1e860c45a7c5e326cddd1a87f44e4fb3
# Original source: "uwe5621ds for armbian linux 6.1" (SDIO transport).
# Original authors and per-file license notices are retained.
obj-$(CONFIG_RK_WIFI_DEVICE_UWE5621) += unisocwcn/
obj-$(CONFIG_WLAN_UWE5621)    += unisocwifi/
obj-$(CONFIG_TTY_OVERY_SDIO)  += tty-sdio/

UNISOCWCN_DIR := $(abspath $(srctree)/$(src)/unisocwcn)
UNISOC_BSP_INCLUDE := $(UNISOCWCN_DIR)/include
export UNISOC_BSP_INCLUDE

TARGET_BUILD_VARIANT := user
export TARGET_BUILD_VARIANT

UNISOC_FW_PATH_CONFIG := "/lib/firmware/uwe5621ds/"
export UNISOC_FW_PATH_CONFIG
