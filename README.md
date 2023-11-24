Hals for Redmi 10C "Fog/Rain/Wind"

Add this line to the ROM manifest.xml before repo sync in the hardware/qcom-caf/common line :
```
    <linkfile src="os_pickup_audio-ar.mk" dest="hardware/qcom-caf/bengal/audio/Android.mk" />
    <linkfile src="os_pickup_qssi.bp" dest="hardware/qcom-caf/bengal/Android.bp" />
    <linkfile src="os_pickup.mk" dest="hardware/qcom-caf/bengal/Android.mk" />
```

# CLONE
```
git clone https://github.com/KDEFFALT/hardware_qcom-caf_bengal -b thirteen hardware/qcom-caf/bengal
```
