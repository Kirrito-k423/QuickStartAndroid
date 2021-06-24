
# cpu
cat /proc/cpuinfo 或者 getprop ro.product.cpu.abi

# memery
cat /proc/meminfo

# GPU
cat /proc/gpu_memory
dumpsys SurfaceFlinger |grep GLES

```
130|HWELE:/ $ dumpsys SurfaceFlinger |grep GLES
GLES: ARM, Mali-G76, OpenGL ES 3.2 v1.r18p0-01rel0.03a31fb463b14c043b85e5070853d58b
GLES: ARM, Mali-T830, OpenGL ES 3.2 v1.r20p0-01rel0.9a7fca3f7dd712a473937294a8ae24b1
```

#  model
getprop ro.product.model

# Screen Resolution
wm size
wm density

# Android version
getprop ro.build.version.release

#  battery
dumpsys battery
scale 代表最大电量，level 代表当前电量

# if change
cat /system/build.prop

# software 

AIDA64