subdir-ccflags-y		:= -Wformat

obj-$(CONFIG_DRV_SAMSUNG)	+= sec_class.o sec_kcompat.o
obj-$(CONFIG_SEC_PARAM)		+= sec_param.o
obj-$(CONFIG_SEC_MPARAM)	+= sec_mparam.o
obj-$(CONFIG_SEC_SYSUP)		+= sec_sysup.o
obj-y				+= debug/
obj-$(CONFIG_SEC_MISC)		+= misc/
obj-$(CONFIG_SEC_QUEST)		+= quest/

obj-$(CONFIG_SEC_DEBUG_TEST)	+= debug/
GCOV_PROFILE_sec_class.o		:=y

obj-$(CONFIG_SAMSUNG_LMKD_DEBUG)		+= lmkd_debug.o
