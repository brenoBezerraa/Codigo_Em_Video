# Codigo_Em_Video

Plataforma de ensino desenvolvida e gerenciada por alunos da Unifor.

## Como rodar:

### Front:
```bash
cd frontend/
npm install --legacy-peer-deps #(somente na primeira vez)
npm run dev
```
### Back:
```bash
cd backend/
npm i #(somente na primeira vez)
# Crie seu .env baseado no .env.example
npx prisma generate #(somente na primeira vez)
npm start dev
```
