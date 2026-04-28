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
