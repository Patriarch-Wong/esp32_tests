# ESP32 tests

Standalone ESP32 experiments, each in its own project directory.

| Project | Description | Validation |
| --- | --- | --- |
| [codec_test](codec_test/) | ESP32-S3 N16R8 Opus encode/store/decode test | UART and native USB builds passed; three hardware round trips passed over UART |

Open the project directory in PlatformIO, or change into it before running commands:

```sh
cd codec_test
pio run
```

See each project README for hardware requirements, upload instructions, and measured results.
