# Ansible Role: Remi Repository

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>


Installs [Remi's RPM repository](http://rpms.famillecollet.com/) for RHEL/CentOS.

## Requirements

On RHEL 8 or newer, you should make sure to install or enable the EPEL repository. I recommend using the `nholuong.repo-epel` repository.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    remi_repo_url: "https://rpms.remirepo.net/enterprise/remi-release-{{ ansible_distribution_major_version }}.rpm"

The URL from which the Remi repo `.rpm` will be downloaded and installed.

    remi_repo_gpg_key_url: "https://rpms.remirepo.net/RPM-GPG-KEY-remi2018"

Remi repo GPG key location. Can be set to a local file or to the URL from Remi's website.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - nholuong.repo-remi

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
