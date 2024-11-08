## 1.Abuot this project

### Project name

shopping-test

### The purpsse of this project

The project demonstrates how to operate a system using React, Go, and PostgreSQL within Docker containers.

## 2.Tech stack

| Language・Framework |  version |
| -------------------- | ---------- |
| React.ts             | 18         |
| Go                   | 1.23       |
| PostgresSQL          | latest     |
| Docker               | 27.2.0     |

## 3. Command List

| Command                               |    Process to execute         |
| --------------------------------------| ------------------------------|
| docker-compose down                   | Stop docker                   |
| docekr-compose up -d                  | Start Docker background       |
| docker-compose up --build             | Build + Start Docker          |
| docker builder prune --all --force    | Delete all cash in Docker     |

## 4. SQL command

### 1.Move root directory and connect to database
```
docker-compose exec database bash
```

### 2. Signin with username and database name
```
psql -U user_namee -d database_name
```

### 3.Check if table exist
```
\dt
```

### 4. Move to table
```
SELECT * FROM table_name
```

### 5. Quite table
```
\q
```

### 6. Exit sql
```
exit
```