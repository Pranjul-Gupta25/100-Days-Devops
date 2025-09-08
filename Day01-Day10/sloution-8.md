# Install pip3 if missing
sudo yum install python3-pip -y

# Install ansible 4.10.0
sudo pip3 install ansible==4.10.0

# Verify global binary
which ansible
ansible --version

