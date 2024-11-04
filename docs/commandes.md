# Commandes

- **Changer de version de java** : 
```bash
sudo alternatives --config java
```

- **Lancez le backend avec mvn**:
```bash
exec:java-Dexec.mainClass="com.example.area_backend.AreaBackendApplication” (ou bien mvn spring-boot:run)
```
- **Build Docker Compose (Racine repo)**:
```bash
sudo docker-compose build
```
- **Run les Docker Image (Racine repo)**:
```bash
sudo docker-compose up
```
- **Delete Docker Container (Racine repo):**
```bash
sudo docker-compose down
```
- **Refresh all Backend (Database and Server)**:
```bash
sudo docker-compose down --volumes --rmi all && sudo docker-compose up --build
```
