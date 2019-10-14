
# ansible-android-builder

Ansible role for setup linux-based android buidler.

Currently this works on Debian and RedHat based linux systems.
**Tested platforms are:**

* Ubuntu 14.04
* Ubuntu 16.04
* Ubuntu 18.04
* Debian 8
* Debian 9
* CentOS 7


## Requirements

* Outbound network connectivity


## Dependencies

None


## Variables

None


## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
    - hosts: servers
      roles:
        - ansible-android-builder
```

## Testing

This playbook uses [Kitchen][kitchenci] for CI and local testing.


## License

**This project is made available under the terms of the [GPLv3][gplv3]. See the [LICENSE][license] file that accompanies this distribution for the full text of the license.**



## Author Information

**Lior Lifshitz**


[kitchenci]: https://kitchen.ci
[gplv3]: https://www.gnu.org/licenses/gpl.html
[license]: https://github.com/liorlifshitz/ansible-linux-squid/blob/master/LICENSE

