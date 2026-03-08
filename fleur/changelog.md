## FleurX v2.2 Changelog - 08/03/2026

* slub: Optimized SLUB Memory Allocator
* msm: kgsl: Remove sync fence names
* ptrace: reset ptrace_message on resume to prevent PID leak
* mm: kmemleak: Don't die when memory allocation fails
* mm/slab_common: Align all caches' objects to hardware cachelines
* mm: Tweak memory pressure
* locking/qspinlock: Micro-optimize pending state waiting for unlock
* SU: Pre-rooted with multi manager support

## FleurX v2.1 Changelog - 05/03/2026

* **upstream:** android12-5.10.252
* **SU:** KernelSU Next v3 & SUSFS 2.0
* **merge:** Merged rama staging branch https://github.com/ramabondanp/android_kernel_common-5.10

---

## FleurX v2 Changelog - 04/03/2026

### Performance & CPU
* **upstream:** android12-5.10.251
* **SU:** Pre-rooted with multi manager support (KernelSU-Next, SukiSU-Ultra, KowSU, RKSU, WildKSU, MamboSU, VortexSU)
* **hz:** Set CONFIG_HZ=300
* **clang:** Compiled with Clang 21 & LTO_CLANG_FULL
* **core:** Enable full PREEMPT for improved system responsiveness
* **cpufreq:** Introduce a simple CPU (max) boost driver
* **cpufreq/schedutil:** Set default rate limit to 2000 us
* **cpufreq/schedutil:** Allow CPU frequency changes to be amended before they are set
* **devfreq:** Reduce polling interval to 50ms
* **gki_defconfig:** Enable boost max driver

### Memory Management
* **mm/vmscan:** Increase default swappiness from 60 to 80
* **mm/vmscan:** Skip reclaim throttle on critical processes
* **mm/vmscan:** Use OOM scoring in `task_is_critical()` to apply on binder-spawned tasks

### Power & Thermals
* **thermal_sysfs:** Use `vmalloc` for `cooling_device_stats_setup()`
* **config:** Disable sync when entering suspend for faster sleep

---

## FleurX v1 Changelog - 30/01/26

* **kernel:** Initial Release
* **clang:** Compiled with Clang 20 & LTO_CLANG_THIN
* **hz:** Set CONFIG_HZ 300 & 500
  
