# B2Z-docker-install

```bash
sudo apt -y update && apt -y upgrade
```

USER: 👩🏼‍💻
```bash
sudo adduser deploy
sudo usermod -aG sudo deploy
sudo su deploy
```

DOWNLOAD INSTALL: 💾
```bash
sudo apt install -y git && git clone https://github.com/VespertineWeb/B2Z-docker-install install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```

NEW INSTANCE INSTALL: 🐵
```bash
cd && cd ./install && sudo ./install_instancia
```

