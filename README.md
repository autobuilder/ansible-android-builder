# ansible-android-builder

Ansible role for setup linux-based android buidler.

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat)](https://opensource.org/licenses/Apache-2.0)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/liorlifshitz/ansible-isp-speedtest/issues)

Tested platforms are the below linux-based distros:

![Platform](https://img.shields.io/badge/platform-ubuntu-dd4814.svg?style=flat)
![Platform](https://img.shields.io/badge/platform-centos-932279.svg?style=flat)

* Ubuntu 18.04
* CentOS 7

## Requirements

None

## Dependencies

Oracle-Java

## Variables

None

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
    - hosts: servers
      roles:
        - ansible-android-builder
```
## Test Automation

Automated tests run with [Kitchen-CI][kitchenci] and [Ansible Lint][ansiblelint].

## License

This project is made available under the terms of the [Apache-2.0][apache2].

See the [LICENSE][license] file that accompanies this distribution for the full text of the license.

## Author Information

**[Lior Lifshitz][liorlifshitz]**

[speedtestcli]: https://github.com/sivel/speedtest-cli
[kitchenci]: https://kitchen.ci
[apache2]: https://www.apache.org/licenses/LICENSE-2.0.html
[license]: https://github.com/liorlifshitz/ansible-isp-speedtest/blob/master/LICENSE
[liorlifshitz]: https://github.com/liorlifshitz
[ansiblelint]: https://docs.ansible.com/ansible-lint/