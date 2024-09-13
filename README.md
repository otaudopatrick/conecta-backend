# Conecta Backend

# Requisitos
Node.js (v18 ou superior recomendado)
npm (v8 ou superior recomendado)

## Instalação e Configuração

### Instalar Dependências
Execute o comando abaixo para instalar as dependências do projeto:
```bash
npm install
```

### buildar o projeto
Execute o comando abaixo para dar build no projeto:
```bash
npm run build
```

### subir banco de dev e redis
Execute o comando abaixo para subir o banco de dev no projeto:
```bash
docker compose up
```

### rodar as migratrions
Execute o comando abaixo para rodar as migrations no projeto:
```bash
node run db:migrate
```