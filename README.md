# Modules

# This file will be read by# This file will be read by resetprop
# Example: Change dpi
# ro.sf.lcd_density=320

#ngentouch improve
touch.pressure.scale=0.0001
persist.sys.ui.hw=1
view.scroll_friction=10
touch.size.calibration=diameter
touch.size.scale=1
touch.size.bias=0
touch.size.isSummed=0
touch.orientation.calibration=none
touch.distance.calibration=none
touch.distance.scale=0
touch.coverage.calibration=box
touch.gestureMode=spots
MultitouchMinDistance=1px
MultitouchSettleInterval=1ms
TapInterval=1ms
TapSlop=1px

#Improve global touch screen response
debug.egl.hw=1
video.accelerate.hw=1

#FixRender
debug.hwui.renderer=skiavk


#ram
ro.HOME_APP_ADJ=1

#Open the first-in-first-out interface thread
ro.telephony.call_ring.delay=0
ring.delay=0

#Turn off vertical sync (V-Sync)
debug.hwui.disable_vsync=true
hwui.disable_vsync=true


