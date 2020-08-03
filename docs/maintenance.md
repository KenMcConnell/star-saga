# Server Maintenance


+ Check to see if another instance of mkdocs is running: lsof -i :8080
+ Retire that instance: kill -9 PID
+ Before starting server, or deploying build the site.
+ Start mkdocs: mkdocs Start
+
u55362473@home302109391.1and1-data.host
FTP: u55362473  
SFTP Port: 22


To deploy:

1. mkdocs build locally.
2. git commmit changes
3. git push changes
4. remote to Server
5. remote git pull
6. refresh server page
