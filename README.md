# Hard Hat OS
The Hard Hat operating system (HOS) is a hardened Fedora Linux that aims to utilize SELinux, seccomp, and other security technologies to provide a more secure desktop experience. **HOS is currently under development, it is not considered stable!**

### Package Repository: [[Link](https://copr.fedorainfracloud.org/coprs/hardhatos/)]
This repository contains all HOS packages for the latest version of Fedora Linux. It's hosted on Copr, which is a publically available build system [[1](https://docs.pagure.org/copr.copr/user_documentation.html#what-is-the-purpose-of-copr)].

#### Instructions
To enable the HOS repository, enter the following commands as the root user:

1. Enable the Copr repository: `dnf copr enable hardhatos/release`

2. Update the cache: `dnf update`

3. You can now search and install software, all of which are located here: [[Link](https://copr.fedorainfracloud.org/coprs/hardhatos/release/packages/)]

### Developers
The following is an exhaustive list of all official developers for HOS:

>**Head Developer**: noatsecure [[GitHub](https://github.com/noatsecure)]
