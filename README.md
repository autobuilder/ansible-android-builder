---

# ansible-android-builder

<img src="https://www.ansible.com/hubfs/2016_Images/Assets/Ansible-Mark-Large-RGB-Pool.png?hsLang=en-us" width="10%" height="10%" alt="Ansible logo" align="right"/>
<img src="https://pngriver.com/wp-content/uploads/2018/04/Download-Android-PNG-Transparent-Picture.png" width="9%" height="9%" alt="Ansible logo" align="right"/>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat)](https://opensource.org/licenses/Apache-2.0)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/autobuilder/ansible-isp-speedtest/issues)

![Platform](https://img.shields.io/badge/platform-ubuntu-dd4814.svg?style=flat)

Ansible role for setup linux-based android buidler.

---

### Requirements:

* None

### Dependencies:

* Oracle-Java

---

### Variables:

| Variable Name             | Default Vaule                        | Description                                  |
|:--------------------------|:-------------------------------------|:---------------------------------------------|
|use_custom_user_name       | ```false```                          | Custom 'Builder' user                        |
|builder_user               | ```androbuilder```                   | Builder user-name                            |
|builder_group              | ```androbuilder```                   | Builder group-name                           |
|install_gradle             | ```true```                           | Install [Gradle][gradle]                     |
|install_apk_tool           | ```true```                           | Install [APK-Tool][apktool]                  |
|install_android_sdk        | ```true```                           | Install [Android-SDK][androidsdk]            |
|install_android_ndk        | ```true```                           | Install [Android-NDK][androidndk]            |
|android_base_path          | ```"/usr/share/android"```           | Path to Android base directory               |
|android_sdk_path           | ```"/usr/share/android/sdk"```       | Path to Android SDK base directory           |
|android_sdk_version        | ```26.1.1```                         | Android SDK version                          |
|android_ndk_path           | ```"/usr/share/android/ndk"```       | Path to Android NDK base directory           |
|android_ndk_version        | ```"b"```                            | Android NDK version                          |
|android_ndk_subversion     | ```"16"```                           | Android NDK sub-version                      |
|android_apk_tool_path      | ```"/usr/share/android/apk_tool"```  | Path to Android APK_Tool base directory      |
|android_apk_tool_version   | ```2.4.0```                          | Install [APK-Tool][apktool]                  |

---

### Example Playbook:

```yaml
    - hosts: servers
      roles:
        - ansible-android-builder
```

---

### Test Automation:

Automated tests run with [Kitchen-CI][kitchenci] and [Ansible Lint][ansiblelint].
Tested platforms are the below linux-based distros:

* Ubuntu 18.04

---

### License:

This project is made available under the terms of the [Apache-2.0][apache2].

See the [LICENSE][license] file that accompanies this distribution for the full text of the license.

---

### Author Information:

[AutoBuilder][autobuilder]

[speedtestcli]: https://github.com/sivel/speedtest-cli
[kitchenci]: https://kitchen.ci
[apache2]: https://www.apache.org/licenses/LICENSE-2.0.html
[license]: https://github.com/autobuilder/ansible-android-builder/blob/master/LICENSE
[autobuilder]: https://github.com/autobuilder
[ansiblelint]: https://docs.ansible.com/ansible-lint/
[androidsdk]: https://developer.android.com/studio
[androidndk]: https://developer.android.com/ndk
[gradle]: https://gradle.org
[apktool]: https://ibotpeaches.github.io/Apktool/
