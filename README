# pi-node-ubuntu


# pi node for ubuntu 20.04LTS

# dpkg -i windscribe_2.4.8_beta_amd64.deb

sudo apt-get update
sudo apt-get install ca-certificates curl gnupg lsb-release
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt update
sudo apt-get -y install qemu-system-x86 docker-ce docker-ce-cli containerd.io docker-compose-plugin

# 
# Then run sudo apt-get install ./docker-desktop-<version>-<arch>.deb
# https://docs.docker.com/desktop/linux/install/

docker pull pinetwork/pi-node-docker

# docker exec -t pi-consensus supervisorctl status horizon
