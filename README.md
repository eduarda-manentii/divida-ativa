# Gestão de Dívida Ativa – Attus

MVP do sistema de **Gestão de Dívida Ativa**, desenvolvido pela **Attus**.  
A aplicação é composta por um **frontend em React (Vite + TypeScript)** e um **backend em Node.js com Express e MongoDB**, todos orquestrados via **Docker Compose**.

---

## Tecnologias Utilizadas

### Frontend
- React 18
- Vite 6
- TypeScript
- Recharts (gráficos e dashboards)

### Backend
- Node.js 22+
- Express 5
- Mongoose 9
- MongoDB

### Infraestrutura
- Docker Engine
- Docker Compose
- Rede isolada e persistência de dados via volumes

---

---

## Pré-requisitos

Antes de iniciar, verifique se possui instalados:

- Docker Engine e Docker Compose v2.24 ou superior
- (Opcional) Node.js LTS caso queira rodar localmente sem containers

---

## Como Executar com Docker

Na raiz do projeto, execute:

```bash

sudo docker compose up --build
Isso iniciará os serviços:

MongoDB: mongodb://localhost:27017

Backend (API): http://localhost:3001

Frontend (Vite): http://localhost:5176

Para parar e remover containers:

bash
Copiar código
sudo docker compose down
Para limpar volumes e dados persistidos:

bash
Copiar código
sudo docker compose down -v
