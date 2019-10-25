# system-checker
A simple console application to check your system for [lacmus](https://github.com/lizaalert/lacmus) usage.

Supports `Windows`\ `Linux`\ `macOS` platform.

## Usage

*Install python 3.6 (or later) and pip to use it*

```bash
$ pip install -r requirements.txt 
$ python main.py
```

## Example
```bash
$ python main.py
==== CPU INFO ====
Name: Intel(R) Core(TM) i5-4590 CPU @ 3.30GHz
Architecture: X86_64
Core numbers: 4
Flags: 3dnow, abm, acpi, aes, apic, avx, avx2, bmi1, bmi2, clflush, cmov, cx16, cx8, de, dts, erms, est, f16c, fma, fpu, fxsr, ht, hypervisor, ia64, invpcid, lahf_lm, mca, mce, mmx, movbe, msr, mtrr, osxsave, pae, pat, pbe, pcid, pclmulqdq, pdcm, pge, pni, popcnt, pse, pse36, rdrnd, sep, serial, smep, ss, sse, sse2, sse4_1, sse4_2, ssse3, tm, tm2, tsc, vme, xsave, xtpr
==== RAM INFO ====
RAM: 16 GB
==== GPU INFO ====
Name: GeForce GT 740
Vidio memory: 2048.0 MB
Id: 0
==== COMPATIBILITY INFO ====
Architecture compatibility: True
CPU avx compatibility: True
CPU multicore compatibility: True
RAM compatibility: True
GPU compatibility: True
Congratulations! Your device supports GPU version! You can use 'gpu' version.
Remember that 'gpu' version works ONLY on Linux. Please install linux (e.g. Ubuntu) if you have other os!

You can download the latest release here: https://github.com/lizaalert/lacmus/releases
```

**Known issues**

In some cases for `windows` it can generate more than one ouplut. So you shold look at the last one.
