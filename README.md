# Farcaster

****** +16 G RAM  
+4 Core CPU  
+200 G HARD  
UBUNTU 22  

```
sudo apt update
sudo apt install ca-certificates curl gnupg
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
sudo chmod 644 /etc/apt/keyrings/docker.gpg
```


```
echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt update
```


```
sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

git clone https://github.com/farcasterxyz/hub-monorepo.git

```

```
apt install screen

screen -S Hubble

```

```

curl -sSL https://download.thehubble.xyz/bootstrap.sh | bash


```
```
sudo systemctl start docker
```


FOR UPGRADING NODE
```
cd ~/hubble && ./hubble.sh upgrade
```
