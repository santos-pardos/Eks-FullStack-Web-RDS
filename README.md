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
kubectl exec -it car-web-deploy-69b77b8b8d-rztrw sh
```
```
docker-compose build --no-cache --pull
docker-compose up -d
docker-compose down
docker rmi $(docker images -q)
docker build --pull --no-cache --tag myimage:version .
```
## DBeaver
```
docker run -d --name cloudbeaver --rm -ti -p 80:8978 -v /opt/cloudbeaver/workspace dbeaver/cloudbeaver:latest
```
# Visual Studio Code Webserver URL
```
https://github.com/santos-pardos/Hands-On-Lab-in-AWS/tree/main/Containers/Vsc_Web_Ec2
```
```
https://vscode.dev/tunnel/vscode-demo-tunnel
```


