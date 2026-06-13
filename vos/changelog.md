# 13/06/2026 - VoltageOS 5.10
- Update from OS3.0.5.0.WNRMIXM (@grewal)
- Updated Miui Camera from OS3.0.5.0.WNRMIXM (@grewal)
- Include Gapps
- Switch back to Lunaris Dolby UI
- Include JamesDSP
- Drop Spatial Audio
- dolby: Patch libdolbyvision.so to allocate GraphicBuffer with new size (@ArianK16a)
- surfaceflinger: Reduce max acquired frame buffers to 2
- overlay: Add overlay to improve signal reception
- reduce uclamp.min value to 125
- props: Set ro.netflix.bsp_rev from stock
- Import V837.0.7 GPU drivers (@adrenolaboratory)
- Relax thermal limits and optimize charging behavior (@zerotwo-alt)
- kernel: Merge branch 'android12-5.10-lts' of https://android.googlesource.com/kernel/common (5.10.257)
- Merge tag 'KERNEL.PLATFORM.1.0.r3-07500-kernel.0' of https://git.codelinaro.org/clo/la/kernel/msm-5.10
- Merge tag 'CAMERA.LA.2.0.r2-06600-WAIPIO.0' of https://git.codelinaro.org/clo/la/platform/vendor/opensource/camera-kernel
- Merge tag 'DISPLAY.LA.2.0.r3-04000-WAIPIO.0' of https://git.codelinaro.org/clo/la/platform/vendor/opensource/display-drivers
- Merge tag 'VIDEO.LA.2.0.r2-04500-WAIPIO.0' of https://git.codelinaro.org/clo/la/platform/vendor/opensource/video-driver
- Merge tag 'LA.VENDOR.1.0.r2-16600-WAIPIO.QISI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom-opensource/wlan/qcacld-3.0
- Merge tag 'LA.VENDOR.1.0.r2-16600-WAIPIO.QISI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom-opensource/wlan/qca-wifi-host-cmn
Merge tag 'LA.VENDOR.1.0.r2-16600-WAIPIO.QISI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom-opensource/wlan/fw-api
- cpufreq: reflex: avoid startup race in rfx_start
- kernel: ANDROID: Build multi-gen LRU
- kernel: ANDROID: Enable CONFIG_LAZY_RCU
- kernel: Enable BBRplus

# 11/05/2026 - VoltageOS 5.9
- Sync with LineageOS device tree
- Explicitly disable Enable GL comp backpressure
- Rm package cache on early boot
- parts: GPU Manager, Kernel Manager, Clear Speaker & Bypass Charge UI changes.
- Switch to Moto Dolby
- Add support for Dolby Spatial Audio
- Enable Dolby Vision support
- cpufreq: reflex: call android_vh_map_util_freq to fix SODs
- kernel: Merge Linux Stable branch (5.10.255)
- KernelSU-Next 3.2.0 & SUSFS 2.1.0 included

---
# 28/04/2026 - VoltageOS 5.8
- Kang Adreno driver from aurora OS3.0.7.0.WNACNXM (V@762.36 OGL & VK 1.3.128)
- Use hwui and add some hwui props for improve perf
- Set vulkan as default renderer
- Relax thermal limits and optimize charging behavior (cr @Flyingsquirrel02)
- Move Xiaomi Parts to one section
- GameBar update (cr @ph12nex)
- KernelSU-Next 3.2.0 & SUSFS 2.1.0 included
- Kernel rebase & upstream 5.10.254-rc1 (cr @ramabondanp)
- Added KProfiles
- kernel: Imported Adaptive Deadline I/O Scheduler (ADIOS) v3.2.0
- kernel: Import Reflex CPUFreq Governor v0.3.0r2
- kernel: Enabled IP set support
- power: Improved deep sleep and switched to suspend-to-idle
- f2fs: Optimized GC, fsync, and cache pressure
- zRAM: Fixed race conditions and optimized entry flags
- GPU: Forced idle timeout to 58ms for better balance
- system: Reduced OOM and scheduler logspam
- Various upstream fixes and improvements for block & I/O scheduler

---
# 15/03/2026 - VoltageOS 5.7
- Switch to LOS kernel
- Pre-rooted with multi manager support
- Import V@762.36 OGL & VK driver from houji
- Vulkan rendering by default
- Added XiaomiParts
- props: Enable support for kernel idle timer
- Disable logging sensors-hal events
- Improve scrolling and responsiveness
- disable_gl_backpressure
- Enable frame pacing for smoother visual performance
- props: Add missing layer buffer slots cache clear property
- Enable debug.performance.tuning
- Enable AOSP surfaceflinger
- Enable Qualcomm TrueWireless™ Stereo
- Default HWUI renderer to SkiaVk
- Use HintManager for HWUI

---
# 01/03/2026 - VoltageOS 5.6
- Initial release  
