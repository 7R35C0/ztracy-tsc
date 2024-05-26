## IMPORTANT

The repo is a fork from [zig-gamedev/libs/ztracy](https://github.com/zig-gamedev/zig-gamedev/tree/main/libs/ztracy) library.

Recommended for use is [ztracy](https://github.com/7R35C0/ztracy.git).

However, if you get an error like:

```txt
$ zig build run
Tracy Profiler initialization failure: CPU doesn't support invariant TSC.
Define TRACY_NO_INVARIANT_CHECK=1 to ignore this error, *if you know what you are doing*.
Alternatively you may rebuild the application with the TRACY_TIMER_FALLBACK define to use lower resolution timer.
...
```

try to use this.

All the best!
