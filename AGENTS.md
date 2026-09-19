# Build and run

From the relevant PlatformIO project folder:

```sh
pio run
pio run -t upload
pio device monitor
```

# Standard

Follow applicable C++ Core Guidelines, with RAII and checked status returns
(no exceptions or RTTI). Use BARR-style snake_case, four-space indentation,
Allman braces, and an 80-column limit. Apply BARR-C where applicable to C code.
