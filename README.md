```
sudo ansible-playbook --connection=local -i localhost, --limit localhost playbook.yml
```

```
sudo chsh -s /usr/bin/fish ${USER}
```

```
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher
```

```
fisher install jethrokuan/z
```

```
fcitx-configtool
```

https://docs.docker.com/engine/install/debian/

```
sudo mkdir -m 0755 -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/debian $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```
