---
name: From binary
---

# Install from binary

**Downloads are only available for latest releases, older downloads can be found at [releases](https://github.com/gogs/gogs/releases).**

All downloads come with **MySQL**, **PostgreSQL**, **MSSQL** and **TiDB** (via MySQL protocol) support, and build **with tags `cert`**. Keep in mind that support status may be different from older releases, please follow the instructions on older Gogs instances.

## Notes

- `mws` means builtin Windows service support. Please use the other one if you're using NSSM.

## How to use downloads?

1. Extract the archive.
2. `cd` into the directory just created.
3. Execute `./gogs web` and you're done.

### 0.11.43 @ 2018-03-31

|System|Type|SQLite|PAM|Download ([GitHub](https://github.com/gogs/gogs/releases/tag/v0.11.43))|
|------|----|------|---|--------|
|Linux|386|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_386.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/0.11.43/gogs_0.11.43_linux_386.zip) \| [TAR.GZ](https://cdn.gogs.io/0.11.43/gogs_0.11.43_linux_386.tar.gz)|
|Linux|amd64|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_amd64.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/0.11.43/gogs_0.11.43_linux_amd64.zip) \| [TAR.GZ](https://cdn.gogs.io/0.11.43/gogs_0.11.43_linux_amd64.tar.gz)|
|Linux|armv5|❌|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_armv5.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.43/gogs_0.11.43_linux_armv5.zip)|
|Raspberry Pi|v2/v3 / armv6|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_raspi2_armv6.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.43/gogs_0.11.43_raspi2_armv6.zip)|
|Windows|386|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_386.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_386_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.43/gogs_0.11.43_windows_386.zip) \| [ZIP w/mws](https://cdn.gogs.io/0.11.43/gogs_0.11.43_windows_386_mws.zip)|
|Windows|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_amd64.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_amd64_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.43/gogs_0.11.43_windows_amd64.zip) \| [ZIP w/ mws](https://cdn.gogs.io/0.11.43/gogs_0.11.43_windows_amd64_mws.zip)|
|Mac OS|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_darwin_amd64.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.43/gogs_0.11.43_darwin_amd64.zip)|

### 0.11.34 @ 2017-11-22

|System|Type|SQLite|PAM|Download ([GitHub](https://github.com/gogs/gogs/releases/tag/v0.11.34))|
|------|----|------|---|--------|
|Linux|386|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.34/linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.34/linux_386.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/0.11.34/linux_386.zip) \| [TAR.GZ](https://cdn.gogs.io/0.11.34/linux_386.tar.gz)|
|Linux|amd64|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.34/linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.34/linux_amd64.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/0.11.34/linux_amd64.zip) \| [TAR.GZ](https://cdn.gogs.io/0.11.34/linux_amd64.tar.gz)|
|Linux|armv5|❌|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.34/linux_armv5.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.34/linux_armv5.zip)|
|Raspberry Pi|v2/v3 / armv6|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.34/raspi2_armv6.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.34/raspi2_armv6.zip)|
|Windows|386|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.34/windows_386.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.34/windows_386_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.34/windows_386.zip) \| [ZIP w/mws](https://cdn.gogs.io/0.11.34/windows_386_mws.zip)|
|Windows|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.34/windows_amd64.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.34/windows_amd64_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.34/windows_amd64.zip) \| [ZIP w/ mws](https://cdn.gogs.io/0.11.34/windows_amd64_mws.zip)|
|Mac OS|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.34/darwin_amd64.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.34/darwin_amd64.zip)|

### 0.11.29 @ 2017-08-15

|System|Type|SQLite|PAM|Download ([GitHub](https://github.com/gogs/gogs/releases/tag/v0.11.29))|
|------|----|------|---|--------|
|Linux|386|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.29/linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.29/linux_386.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/0.11.29/linux_386.zip) \| [TAR.GZ](https://cdn.gogs.io/0.11.29/linux_386.tar.gz)|
|Linux|amd64|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.29/linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.29/linux_amd64.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/0.11.29/linux_amd64.zip) \| [TAR.GZ](https://cdn.gogs.io/0.11.29/linux_amd64.tar.gz)|
|Linux|armv5|❌|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.29/linux_armv5.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.29/linux_armv5.zip)|
|Raspberry Pi|v2 / armv6|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/0.11.29/raspi2_armv6.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.29/raspi2_armv6.zip)|
|Windows|386|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.29/windows_386.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.29/windows_386_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.29/windows_386.zip) \| [ZIP w/mws](https://cdn.gogs.io/0.11.29/windows_386_mws.zip)|
|Windows|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.29/windows_amd64.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.29/windows_amd64_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.29/windows_amd64.zip) \| [ZIP w/ mws](https://cdn.gogs.io/0.11.29/windows_amd64_mws.zip)|
|Mac OS|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/0.11.29/darwin_amd64.zip) - CDN: [ZIP](https://cdn.gogs.io/0.11.29/darwin_amd64.zip)|

### v0.9.141 @ 2017-02-11

|System|Type|SQLite|PAM|Download ([GitHub](https://github.com/gogs/gogs/releases/tag/v0.9.141))|
|------|----|------|---|--------|
|Linux|386|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.9.141_linux_386.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_linux_386.zip) \| [TAR.GZ](https://cdn.gogs.io/gogs_v0.9.141_linux_386.tar.gz)|
|Linux|amd64|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.9.141_linux_amd64.tar.gz) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_linux_amd64.zip) \| [TAR.GZ](https://cdn.gogs.io/gogs_v0.9.141_linux_amd64.tar.gz)|
|Linux|armv5|❌|❌|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_linux_armv5.zip) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_linux_armv5.zip)|
|Linux|armv6|❌|❌|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_linux_armv6.zip) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_linux_armv6.zip)|
|Raspberry Pi|v2|✅|✅|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_raspi2_armv6.zip) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_raspi2_armv6.zip)|
|Windows|386|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_windows_386.zip) \| [ZIP w/ mws](https://dl.gogs.io/gogs_v0.9.141_windows_386_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_windows_386.zip) \| [ZIP w/mws](https://cdn.gogs.io/gogs_v0.9.141_windows_386_mws.zip)|
|Windows|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_windows_amd64.zip) \| [ZIP w/ mws](https://dl.gogs.io/gogs_v0.9.141_windows_amd64_mws.zip) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_windows_amd64.zip) \| [ZIP w/ mws](https://cdn.gogs.io/gogs_v0.9.141_windows_amd64_mws.zip)|
|Mac OS|amd64|✅|❌|LOCAL: [ZIP](https://dl.gogs.io/gogs_v0.9.141_darwin_amd64.zip) - CDN: [ZIP](https://cdn.gogs.io/gogs_v0.9.141_darwin_amd64.zip)|

See [Configuration and run](/docs/installation/configuration_and_run.html) to go further.