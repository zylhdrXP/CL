## FleurX v2 Changelog - 4/03/2026

### Performance & CPU
* **upstream:** android12-5.10.251
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
  
