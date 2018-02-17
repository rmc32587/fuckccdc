# quick other / multi-OS
[split shell screen](https://unix.stackexchange.com/questions/7453/how-to-split-the-terminal-into-more-than-one-view)

[ansible hardening guide](https://github.com/openstack/ansible-hardening)

[25 linux hardening tips](https://www.tecmint.com/linux-server-hardening-security-tips/)

[set up yum package manager](https://www.digitalocean.com/community/tutorials/how-to-set-up-and-use-yum-repositories-on-a-centos-6-vps)

[sans linux hardening cheat sheet](https://www.sans.org/media/score/checklists/LinuxCheatsheet_2.pdf)


# Ubuntu

### important
Check ubuntu version: lsb_release -a

[ubuntu sources.list generator](https://repogen.simplylinux.ch/)

[First 15-20 minute slides](https://docs.google.com/presentation/d/1yb0wOAaC579Mp_ngEzBH_Zs5YvsuWVUhj9yuXZtwaBQ/edit?usp=sharing)

[break into ubuntu 13](https://www.liberiangeek.net/2013/03/unlock-the-root-account-reset-the-root-password-change-username-in-ubuntu-13-04-raring-ringtail/)

[break into ubuntu 12](https://www.liberiangeek.net/2012/09/recover-lost-passwords-in-ubuntu-12-04-recovery-mode/)

### ubuntu 12.04
[ubuntu 12.04 server hardening script](https://www.ostechnix.com/ubuntu-server-secure-script-secure-harden-ubuntu/)

[hardening ubuntu 12.04 with bastille](https://itandsecuritystuffs.wordpress.com/2014/04/08/hardening-linux-ubuntu-12-04-using-bastille/)

[ubuntu 12.04 LTS configuration guide](https://www.rationallyparanoid.com/articles/ubuntu-12-lts-security.html)

### ubuntu 10.04
[ubuntu 10.04 security configuration guide](https://www.rationallyparanoid.com/articles/ubuntu-10-lts-security.html)

# Debian

### important
check debian version: cat /etc/os-release

[debian sources.list generator](https://debgen.simplylinux.ch/)

[break into debian squeeze](https://pve.proxmox.com/wiki/Root_Password_Reset)

[break into debian](http://www.debianadmin.com/how-to-reset-debian-root-password.html)

### debian 7
[hardening debian 7](https://noobsysadmin.wordpress.com/2014/03/05/hardening-your-linux-debian-7-wheezy-part-1/)

[hardening debian 7/8 script](https://github.com/ovh/debian-cis)

[hardening debian weezy](https://technpol.wordpress.com/2013/08/12/hardening-a-debian-wheezy-linux-apache-server/)

# Red Hat

### important
check redhat version: cat /etc/redhat-release

[configuring yum repository](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system_administrators_guide/sec-configuring_yum_and_yum_repositories)

[hardening guides for RHEL](https://linux-audit.com/hardening-guides-tools-red-hat-linux-rhel/)

[top 10 redhat linux 5 security checks](https://www.upguard.com/articles/top-10-red-hat-enterprise-linux-5-security-checks)

[break into rhel 7](https://www.rootusers.com/how-to-reset-root-user-password-in-centos-rhel-7/)

[recover root password rhel 7](https://linuxconfig.org/recover-a-forgotten-root-password-on-redhat-7-linux-selinux-system)

[break into rhel](https://www.tecmint.com/reset-forgotten-root-password-in-rhel-centos-and-fedora/)

[disallowing root access](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/4/html/Security_Guide/s2-wstation-privileges-noroot.html)

### RHEL 7
[redhat security guide RHEL 7](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/security_guide/index)

[giac RHEL7 hardening guide](https://www.giac.org/paper/gcux/97/red-hat-linux-71-installation-hardening-checklist/102167)

[CIS RHEL7 benchmark checklist](https://nvd.nist.gov/ncp/checklist/495)

[RHEL7 ansible CIS STIG](https://github.com/MindPointGroup/RHEL7-CIS)

[SCAP security guide RHEL7](https://github.com/RedHatGov/ssg-el7-kickstart)

### RHEL 6
[redhat 6 security guide LONG](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/pdf/Security_Guide/Red_Hat_Enterprise_Linux-6-Security_Guide-en-US.pdf)

[RHEL 6 hardening script](https://access.redhat.com/discussions/1588783)

[HKUST RHEL6 hardening guide](https://itsc.ust.hk/sites/itscprod.sites.ust.hk/files/RHEL%206%20Hardening%20Guide.pdf)

[RHEL 6 hardening config](https://static.open-scap.org/ssg-guides/ssg-rhel6-guide-C2S.html)

[rehat linux hardening tips and bash script](http://www.binbert.com/blog/2011/01/redhat-linux-hardening/)

[DISA STIG/USGBCB/NSA SNAC hardening scripts for red hat 6](https://github.com/fcaviggia/hardening-script-el6)

[red hat 6 enterprise security guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/security_guide/index)

### RHEL 5
[hardening RHEL5](https://people.redhat.com/sgrubb/files/hardening-rhel5.pdf)

### RHEL 3/4
[securing and hardening red hat linux production systems](http://www.puschitz.com/SecuringLinux.shtml)

# Fedora

### important 
check fedora version: cat /etc/fedora-release

[break into fedora](https://fedoraproject.org/wiki/How_to_reset_a_root_password)

[recover root password fedora - look at bottom](https://docs-old.fedoraproject.org/en-US/Fedora/12/html/Installation_Guide/ap-rescuemode.html)

### fedora 20 and below
[fedora basic hardening guide](https://docs-old.fedoraproject.org/en-US/Fedora/17/html/Security_Guide/chap-Security_Guide-Basic_Hardening.html)

[fedora selinux guide](http://www.linuxtopia.org/online_books/fedora_selinux_guides/fedora_11_security_guide/index.html)

# CentOS

### important
check centos version: hostnamectl or rpm --query centos-release

[centos wiki hardening guide](https://wiki.centos.org/HowTos/OS_Protection)

### centos 6
[hardening guide for apache on centos 6](https://security-24-7.com/hardening-guide-for-apache-2-4-6-on-centos-6-4-64bit-edition/)

[Centos6 PCI hardening guide](https://www.scribd.com/document/276209256/RHEL-6-CentOS-6-PCI-Hardening-Guide)

### centos 5
[hardening rhel centos 5.x](https://centostricks.wordpress.com/2011/08/16/hardening-rhelcentos-5-x/)

[centos 5 x64 hardening script](http://www.webhostingtalk.com/showthread.php?t=1133458)

[audit suse with zypper: vulnerable packages](https://linux-audit.com/audit-suse-with-zypper-vulnerable-packages/)

# Suse

### important
check suse version: cat /etrc/suse-release

[zypper cheat sheet](https://en.opensuse.org/images/1/17/Zypper-cheat-sheet-1.pdf)

[suse hardening guide](https://www.suse.com/docrep/documents/5ncjgxbnn9/TUT88693_system_security_hardening.pdf)

[hardening openSUse](https://h963453.wordpress.com/category/hardening-opensuse/)

[hardening SUSE/SLES](https://wiki.microfocus.com/index.php/SUSE/SLES/Hardening)

[recover root password suse](https://en.opensuse.org/SDB:Recover_root_password)

### suse 12
[security and hardening guide suse 12](https://www.suse.com/documentation/sles-12/pdfdoc/book_hardening/book_hardening.pdf)

### suse 11
[suse linux enterprise 11 sp4 hardening guide](https://www.suse.com/documentation/sles11/singlehtml/book_hardening/book_hardening.html)

# FreeBSD

### important
check freeBSD version: uname -mrs or freebsd-version -k

[freeBSD hardening script](https://jonlabelle.com/snippets/view/shell/freebsd-system-hardening-script)

[basic freeBSD hardening](https://www.funzi.org/2015/03/01/basic-freebsd-hardening/)

### FreeBSD 4/5
[hardening freebsd](http://www.bsdguides.org/2005/hardening-freebsd/)

[openBSD hardening](http://daemonforums.org/showthread.php?t=4120)

[recover freebsd root password](https://www.techrepublic.com/blog/it-security/recover-freebsd-root-access-when-you-forgot-the-password/)

[break into freebsd](https://www.cyberciti.biz/tips/howto-freebsd-reset-recover-root-password.html)

# OpenBSD

### important
[harening linux and OpenBSD](https://cromwell-intl.com/cybersecurity/linux-hardening.html)

[break into openbsd](https://swordfish.wordpress.com/2006/06/23/openbsd-hack-single-user-mode-reset-root-password/)

[advanced openbsd hardening](http://spb.sdf.org/presentations/openbsd.pdf)

# Services

###guides

[lesson 2: break in, log view, harden ssh](https://docs.google.com/document/d/1GANAT_QISVediPUKnhiT85GeWqdqTLcZ9a3CBnrGyNY/edit?usp=sharing)

[lesson 4: LAMP, sFTP, DNS](https://docs.google.com/document/d/1Qfp1eFpQzf3RtMrAGtFqCR14FrCp1cHjAHyFpj2A1qk/edit?usp=sharing)

[lesson 5: incident reponse](https://docs.google.com/document/d/1E-oGqhn-J3x6hTfVqQ0EIlx6R6SCd8L2xVcRvgNj6pg/edit?usp=sharing)

### Web
[securing apache on ubuntu](https://www.maketecheasier.com/securing-apache-ubuntu/)

[harden apache on centos 7](https://devops.profitbricks.com/tutorials/how-to-harden-the-apache-web-server-on-centos-7/)

[13 apache security tips](https://www.tecmint.com/apache-security-tips/)

### email
[harden postfix](https://linux-audit.com/postfix-hardening-guide-for-security-and-privacy/)

[hardening ssl of apache, dovecot, and postfix](https://tipstricks.itmatrix.eu/hardening-the-ssl-security-in-postfix/)

### dns
[harden bind8 dns](http://www.boran.com/security/sp/bind_hardening8.html)

# Tools 
[package manager: Lynis](https://cisofy.com/documentation/lynis/get-started/#installation-package)

[git: Lynis](https://cisofy.com/documentation/lynis/get-started/#installation-git)

[wget: Lynis](https://cisofy.com/documentation/lynis/get-started/#installation-manual)

[Artillery](https://github.com/BinaryDefense/artillery)

[ossec ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ossec-security-notifications-on-ubuntu-14-04)

[ossec ubuntu 12.04](https://adilmehmoodbutt.wordpress.com/2014/04/29/ossec-install-on-ubuntu-12-04-lts-with-wui/)

[ossec debian 7](https://linode.com/docs/uptime/monitoring/ossec-ids-debian-7/)

[tiger](http://www.nongnu.org/tiger/)

[nixarmor linux hardening automation - 2015](https://github.com/emirozer/nixarmor)

[linuxsecurity tiger and lynis tips](http://www.linuxsecurity.com/content/view/164493/171/)

[fail2ban](http://www.fail2ban.org/wiki/index.php/Main_Page)

[sshguard](https://www.sshguard.net/docs/setup/compile-install/)

# Tips

[disable root login for ssh](https://mediatemple.net/community/products/dv/204643810/how-do-i-disable-ssh-login-for-the-root-user)

