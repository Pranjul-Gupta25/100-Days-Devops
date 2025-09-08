# Edit SSH configuration
sudo vi /etc/ssh/sshd_config

# Change line from:
# PermitRootLogin yes
# To:
PermitRootLogin no

# Restart SSH service
sudo systemctl restart sshd

# Verify by trying root login
ssh root@<server-ip>   # should fail

