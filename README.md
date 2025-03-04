## 🛠️ Configuració  

### 🔹 **1. Instal·lar Docker i Docker Compose**  
Si no tens Docker i Docker Compose instal·lats, fes-ho amb:  

```bash
sudo apt update && sudo apt install docker docker-compose -y
```

## Clonar aquest repositori
git clone https://github.com/EricPasto/developer_env.git
cd proyecto_docker## Construir i executar els contenidors
```
docker-compose up --build
```

## 🖥️ Com accedir als serveis

## Developer:
```
ssh developer@localhost -p 2223

```
🔹 Accedir a PostgreSQL des de Developer

## Un cop dins del contenidor developer:

```
psql -h postgres_db -U user -d mydatabase

```

## Connexió VNC a Developer
Connecta’t a localhost:5900 amb un client VNC.

# 📌 Notes
Les credencials d'accés als contenidors són:

### Usuari Developer: developer / password
### PostgreSQL: user / password / Base de dades: mydatabase
