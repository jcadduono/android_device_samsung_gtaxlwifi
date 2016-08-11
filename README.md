## TWRP device tree for Galaxy Tab A 10.1 WiFi (2016 Exynos)

Add to `.repo/local_manifests/gtaxlwifi.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/gtaxlwifi" name="android_device_samsung_gtaxlwifi" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/android_kernel_samsung_exynos7870/tree/twrp-6.0

