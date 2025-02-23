# hardware/oplus

## Soong options

| Namespace | Variable | Description | Default |
| --------- | -------- | ----------- | ------- |
| OPLUS_LINEAGE_LIVEDISPLAY_HAL | ENABLE_AF | Enable AntiFlicker feature | false |
| OPLUS_LINEAGE_LIVEDISPLAY_HAL | ENABLE_DM | Enable DisplayModes feature | false |
| OPLUS_LINEAGE_LIVEDISPLAY_HAL | ENABLE_PA | Enable PictureAdjustment feature | true |
| OPLUS_LINEAGE_LIVEDISPLAY_HAL | ENABLE_SE | Enable SunlightEnhancement feature | true |
| OPLUS_LINEAGE_TOUCH_HAL | INCLUDE_DIR | Device specific include dir path | |
| OPLUS_LINEAGE_VIBRATOR_HAL | INCLUDE_DIR | Device specific include dir path | |
| OPLUS_LINEAGE_VIBRATOR_HAL | USE_EFFECT_STREAM | Enable effect stream feature | false |
| QTI_GPT_UTILS | USE_BSG_FRAMEWORK | Enable BSG framework feature | true |

If you are getting errors about wakeUpWithProximityCheck while building PixelOS refer: https://github.com/SuperiorOS-Devices/hardware_oplus/commit/2e110ac82499ebddc36e4ca269efef18a734792c
