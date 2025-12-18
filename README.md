#FindYourDuo_App # FindYourDuo App

**Tags**: #CSS #Docker #Express #Html #JavaScript #Markdown #Node #Prisma #React #Tailwind #TypeScript

**Status**: `#Project/Fullstack` `#React` `#Node` `#Mobile`

## 📝 Descrição
O **FindYourDuo** é uma plataforma completa (Web, Server, Mobile) para conectar gamers que desejam encontrar parceiros (duos) para jogar online.

## 🔗 Repositório
projeto criado no evento NLW eSports.

## 🚀 Como Rodar (Docker)

O ambiente completo (Back + Front) sobem com um único comando.

### Pré-requisitos
- Docker & Docker Compose.

### Passos
1. Navegue até a pasta:
   ```bash
   cd 01_Projetos/FindYourDuo_App
   ```
2. Inicie os serviços:
   ```bash
   docker-compose up --build
   ```
   Isso iniciará:
   - **Server** (Node.js/Prisma/SQLite) na porta `3333`
   - **Web** (Vite/React/Nginx) na porta `5173` (mapeada para 80 interna)

### Endpoints
- **API**: http://localhost:3333
- **Web**: http://localhost:5173

## 📂 Módulos
- **`server/`**: API RESTful com Express e Prisma.
- **`web/`**: Frontend web com React e Tailwind.
- **`mobile/`**: App mobile (React Native). *Nota: O Docker Compose atual cobre Server e Web.*
