# Install SELinux packages
sudo yum install selinux-policy* -y

# Edit config file
sudo vi /etc/selinux/config

# Set to disabled
SELINUX=disabled

# Verify
grep SELINUX= /etc/selinux/config

