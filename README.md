## EKS + App + API + AWS RDS

SQL Server Management Studio (SSMS)
```
https://learn.microsoft.com/es-es/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
```
DBeaver Community 24.3.4  (Portable: Zip file)
```
https://dbeaver.io/download/
```

# Tools
```
docker run --name cloudbeaver --rm -ti -d -p 8080:8978 -v /opt/cloudbeaver/workspace dbeaver/cloudbeaver:latest
```
```
docker run -it  nicolaka/netshoot sh
```
```
kubectl run tmp-shell --rm -i --tty --image nicolaka/netshoot
```
```
docker-compose build --no-cache --pull
docker build --pull --no-cache --tag myimage:version .
```
# Visual Studio Code Webserver URL
```
https://vscode.dev/tunnel/vscode-demo-tunnel
```

# Install Docker in AMI Linux 2023 (Fedora)
```
sudo dnf install docker
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -aG docker $USER
newgrp docker
```

Install Docker extension
```
ls -l /var/run/docker.sock
sudo chmod 666 /var/run/docker.sock
sudo systemctl restart docker.service
```

# Install Docker-Compose
```
sudo curl -s https://api.github.com/repos/docker/compose/releases/latest | grep browser_download_url | grep docker-compose-linux-x86_64 | cut -d '"' -f 4 | wget -qi -
```
```
sudo chmod +x docker-compose-linux-x86_64
```
```
sudo mv docker-compose-linux-x86_64 /usr/local/bin/docker-compose
```
```
docker-compose --version
```
