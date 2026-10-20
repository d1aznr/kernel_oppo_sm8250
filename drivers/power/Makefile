obj-$(CONFIG_POWER_AVS)		+= avs/
obj-$(CONFIG_POWER_RESET)	+= reset/
obj-$(CONFIG_POWER_SUPPLY)	+= supply/

ifeq ($(CONFIG_CHARGER_OPPO),y)
obj-$(CONFIG_OPLUS_SM8250_CHARGER)	+= oppo/
else
obj-$(CONFIG_OPLUS_SM8250_CHARGER)	+= oplus/
endif
