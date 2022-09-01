# php-uname

Run `echo php_uname($mode)` and `echo OS_RELATED_CONSTANTS` in different operating systems so you don't have to

## Results

### PHP 7.4

| Command | Windows Server 2022 | Windows Server 2019 | Ubuntu 22.04 | Ubuntu 20.04 | Ubuntu 18.04 | macOS Monterey 12 | macOS Big Sur 11 | macOS Catalina 10.15 |
| :--- | :---- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| echo PHP_OS | WINNT | WINNT | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo PHP_OS_FAMILY | Windows | Windows | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo PHP_SHLIB_SUFFIX | dll | dll | so | so | so | so | so | so |
| echo DIRECTORY_SEPARATOR | \ | \ | / | / | / | / | / | / |
| echo PATH_SEPARATOR | ; | ; | : | : | : | : | : | : |
| echo php_uname('s') | Windows NT | Windows NT | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo php_uname('n') | fv-az206-635 | fv-az478-741 | fv-az573-514 | fv-az127-355 | fv-az266-272 | Mac-1662034000522.local | Mac-1662034129560.local | Mac-1662036874833.local |
| echo php_uname('r') | 10.0 | 10.0 | 5.15.0-1017-azure | 5.15.0-1017-azure | 5.4.0-1086-azure | 21.6.0 | 20.6.0 | 19.6.0 |
| echo php_uname('v') | build 20348 (Windows Server 2016) | build 17763 (Windows Server 2016) | #20-Ubuntu SMP Fri Aug 5 12:00:24 UTC 2022 | #20~20.04.1-Ubuntu SMP Fri Aug 5 12:16:53 UTC 2022 | #91~18.04.1-Ubuntu SMP Thu Jun 23 20:33:05 UTC 2022 | Darwin Kernel Version 21.6.0: Wed Aug 10 14:25:27 PDT 2022; root:xnu-8020.141.5~2/RELEASE_X86_64 | Darwin Kernel Version 20.6.0: Tue Jun 21 20:50:28 PDT 2022; root:xnu-7195.141.32~1/RELEASE_X86_64 | Darwin Kernel Version 19.6.0: Tue Jun 21 21:18:39 PDT 2022; root:xnu-6153.141.66~1/RELEASE_X86_64 |
| echo php_uname('m') | AMD64 | AMD64 | x86_64 | x86_64 | x86_64 | x86_64 | x86_64 | x86_64 |

### PHP 8.0

| Command | Windows Server 2022 | Windows Server 2019 | Ubuntu 22.04 | Ubuntu 20.04 | Ubuntu 18.04 | macOS Monterey 12 | macOS Big Sur 11 | macOS Catalina 10.15 |
| :--- | :---- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| echo PHP_OS | WINNT | WINNT | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo PHP_OS_FAMILY | Windows | Windows | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo PHP_SHLIB_SUFFIX | dll | dll | so | so | so | so | so | so |
| echo DIRECTORY_SEPARATOR | \ | \ | / | / | / | / | / | / |
| echo PATH_SEPARATOR | ; | ; | : | : | : | : | : | : |
| echo php_uname('s') | Windows NT | Windows NT | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo php_uname('n') | fv-az449-360 | fv-az555-841 | fv-az561-998 | fv-az208-467 | fv-az76-528 | Mac-1662033143159.local | Mac-1662034156208.local | Mac-1662031030549.local |
| echo php_uname('r') | 10.0 | 10.0 | 5.15.0-1017-azure | 5.15.0-1017-azure | 5.4.0-1086-azure | 21.6.0 | 20.6.0 | 19.6.0 |
| echo php_uname('v') | build 20348 (Windows Server 2016) | build 17763 (Windows Server 2016) | #20-Ubuntu SMP Fri Aug 5 12:00:24 UTC 2022 | #20~20.04.1-Ubuntu SMP Fri Aug 5 12:16:53 UTC 2022 | #91~18.04.1-Ubuntu SMP Thu Jun 23 20:33:05 UTC 2022 | Darwin Kernel Version 21.6.0: Wed Aug 10 14:25:27 PDT 2022; root:xnu-8020.141.5~2/RELEASE_X86_64 | Darwin Kernel Version 20.6.0: Tue Jun 21 20:50:28 PDT 2022; root:xnu-7195.141.32~1/RELEASE_X86_64 | Darwin Kernel Version 19.6.0: Tue Jun 21 21:18:39 PDT 2022; root:xnu-6153.141.66~1/RELEASE_X86_64 |
| echo php_uname('m') | AMD64 | AMD64 | x86_64 | x86_64 | x86_64 | x86_64 | x86_64 | x86_64 |

### PHP 8.1

| Command | Windows Server 2022 | Windows Server 2019 | Ubuntu 22.04 | Ubuntu 20.04 | Ubuntu 18.04 | macOS Monterey 12 | macOS Big Sur 11 | macOS Catalina 10.15 |
| :--- | :---- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| echo PHP_OS | WINNT | WINNT | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo PHP_OS_FAMILY | Windows | Windows | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo PHP_SHLIB_SUFFIX | dll | dll | so | so | so | so | so | so |
| echo DIRECTORY_SEPARATOR | \ | \ | / | / | / | / | / | / |
| echo PATH_SEPARATOR | ; | ; | : | : | : | : | : | : |
| echo php_uname('s') | Windows NT | Windows NT | Linux | Linux | Linux | Darwin | Darwin | Darwin |
| echo php_uname('n') | fv-az192-526 | fv-az56-52 | fv-az370-739 | fv-az212-321 | fv-az27-657 | Mac-1662034208447.local | Mac-1662034119138.local | Mac-1662030992739.local |
| echo php_uname('r') | 10.0 | 10.0 | 5.15.0-1017-azure | 5.15.0-1017-azure | 5.4.0-1086-azure | 21.6.0 | 20.6.0 | 19.6.0 |
| echo php_uname('v') | build 20348 (Windows Server 2022) |  build 17763 (Windows Server 2019) | #20-Ubuntu SMP Fri Aug 5 12:00:24 UTC 2022 | #20~20.04.1-Ubuntu SMP Fri Aug 5 12:16:53 UTC 2022 |  #91~18.04.1-Ubuntu SMP Thu Jun 23 20:33:05 UTC 2022 | Darwin Kernel Version 21.6.0: Wed Aug 10 14:25:27 PDT 2022; root:xnu-8020.141.5~2/RELEASE_X86_64 | Darwin Kernel Version 20.6.0: Tue Jun 21 20:50:28 PDT 2022; root:xnu-7195.141.32~1/RELEASE_X86_64 | Darwin Kernel Version 19.6.0: Tue Jun 21 21:18:39 PDT 2022; root:xnu-6153.141.66~1/RELEASE_X86_64 |
| echo php_uname('m') | AMD64 | AMD64 | x86_64 | x86_64 | x86_64 | x86_64 | x86_64 | x86_64 |

## Some notes

* Windows Server 2022 based on Windows 10
* Windows Server 2019 based on Windows 10
* Ubuntu 18.04 runner [deprecated](runners) and will be removed soon
* macOS Catalina 10.15 runner [deprecated](runners) and will be removed soon
* All runners are github-hosted virtual machines
* Only contains results for supported PHP versions

[runners]: https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners#supported-runners-and-hardware-resources
