## EKS + App + API + AWS RDS

SQL Server Management Studio (SSMS)
```
https://learn.microsoft.com/es-es/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
```
DBeaver Community 24.3.4  (Portable: Zip file)
```
https://dbeaver.io/download/
```
# Docker - Docker-compose - Buildx - AMI Linux 2023
```
sudo dnf install docker -y
sudo systemctl start docker
sudo systemctl enable docker
sudo dnf install git -y
sudo usermod -aG docker $USER
```
```
sudo curl -s https://api.github.com/repos/docker/compose/releases/latest | grep browser_download_url | grep docker-compose-linux-x86_64 | cut -d '"' -f 4 | wget -qi -
sudo chmod +x docker-compose-linux-x86_64
sudo mv docker-compose-linux-x86_64 /usr/local/bin/docker-compose
docker-compose --version
```
```
mkdir -p ~/.docker/cli-plugins
curl -L https://github.com/docker/buildx/releases/download/v0.17.0/buildx-v0.17.0.linux-amd64 \
  -o ~/.docker/cli-plugins/docker-buildx
chmod +x ~/.docker/cli-plugins/docker-buildx
docker buildx version
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
kubectl exec -it car-web-deploy-69b77b8b8d-rztrw sh
```
```
docker-compose build --no-cache --pull
docker-compose up -d
docker-compose down
docker rmi $(docker images -q)
docker build --pull --no-cache --tag myimage:version .
```

# Visual Studio Code Webserver URL
```
https://github.com/santos-pardos/Hands-On-Lab-in-AWS/tree/main/Containers/Vsc_Web_Ec2
```
```
https://vscode.dev/tunnel/vscode-demo-tunnel
```


