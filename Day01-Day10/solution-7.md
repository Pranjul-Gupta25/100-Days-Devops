# Generate SSH key on jump host as user thor
su - thor
ssh-keygen -t rsa

# Copy key to each app server via their sudo user
ssh-copy-id tony@stapp01
ssh-copy-id steve@stapp02
ssh-copy-id banner@stapp03

# Verify login without password
ssh tony@stapp01
