vendor := $(srctree)/$(src)

subdir-y += qcom

# Build oneplus dts' if the target device is lemonade/p or martini.
ifeq ($(strip $(BRAND_SHOW_FLAG)), oneplus)
subdir-y += oplus/lemonadev
subdir-y += oplus/martini
else
subdir-y += oplus/lunaa
endif