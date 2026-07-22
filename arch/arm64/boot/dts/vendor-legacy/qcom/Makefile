dtb-y :=
dtbo-y :=
dtb-$(CONFIG_MACH_MEIZU_M1721) += meizu-m1721.dtb
dtb-$(CONFIG_MACH_MEIZU_M1822) += sdm632-m1822.dtb
dtbo-$(CONFIG_MACH_MEIZU_M1822) += sdm632-m1822-overlay.dtbo
sdm632-m1822-overlay.dtbo-base := sdm632-m1822.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo