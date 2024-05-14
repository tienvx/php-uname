# php-uname

Run `echo php_uname($mode)` and `echo OS_RELATED_CONSTANTS` in different operating systems so you don't have to

## Results

| Command | Windows 2022 | Ubuntu 22.04 | macOS 14 (ARM) | macOS 13 |
| :--- | :---- | :--- | :--- | :--- |
| PHP_OS | WINNT | Linux | Darwin | Darwin |
| PHP_OS_FAMILY | Windows | Linux | Darwin | Darwin |
| PHP_SHLIB_SUFFIX | dll | so | so | so |
| DIRECTORY_SEPARATOR | \ | / | / | / |
| PATH_SEPARATOR | ; | : | : | : |
| php_uname('s') | Windows NT | Linux | Darwin | Darwin |
| php_uname('n') | fv-az1564-217 | fv-az887-494 | Mac-1715588808985.local | Mac-1715587506927.local |
| php_uname('r') | 10.0 | 6.5.0-1018-azure  | 23.4.0 |  22.6.0 |
| php_uname('v') | build 20348 (Windows Server 2022) | #19~22.04.2-Ubuntu SMP Thu Mar 21 16:45:46 UTC 2024 | Darwin Kernel Version 23.4.0: Fri Mar 15 00:10:50 PDT 2024; root:xnu-10063.101.17~1/RELEASE_ARM64_VMAPPLE | Darwin Kernel Version 22.6.0: Mon Feb 19 19:48:53 PST 2024; root:xnu-8796.141.3.704.6~1/RELEASE_X86_64 |
| php_uname('m') | AMD64 | x86_64 | arm64 | x86_64 |

[runners]: https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners/about-github-hosted-runners#supported-runners-and-hardware-resources
