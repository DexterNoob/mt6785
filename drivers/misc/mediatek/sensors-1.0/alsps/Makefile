# In case the platform does NOT support this type of sensors
ifneq ($(call cc-option,-Wno-array-parameter),)
ccflags-y += -Wno-array-parameter
endif
ccflags-y += -I$(srctree)/drivers/misc/mediatek/sensors-1.0/hwmon/include
obj-y   +=  alsps.o
obj-y   +=  alsps_factory.o
obj-y   +=  aal_control.o

obj-$(CONFIG_MTK_ALSPSHUB)      +=  alspshub/
obj-$(CONFIG_MTK_CM36558)	+=  cm36558/
obj-$(CONFIG_MTK_LTR303)	+=  ltr303/
