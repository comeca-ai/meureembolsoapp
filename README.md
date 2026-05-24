# Meu Reembolso App 💰

Aplicação Node.js para gerenciamento de reembolsos.

## 🚀 Quick Start

### Pré-requisitos
- Node.js 16+ instalado
- npm ou yarn

### Instalação

```bash
# Clonar o repositório
git clone https://github.com/comeca-ai/meureembolsoapp.git
cd meureembolsoapp

# Instalar dependências
npm install

# Criar arquivo .env (baseado em .env.example)
cp .env.example .env
```

### Desenvolvimento

```bash
# Rodando em modo desenvolvimento com hot-reload
npm run dev

# Servidor estará disponível em http://localhost:3000
```

### Produção

```bash
# Iniciar aplicação
npm start
```

## 📋 API Endpoints

### Health Check
- **GET** `/api/health` - Verificar status do servidor

### Reembolsos
- **GET** `/api/reembolsos` - Listar reembolsos
- **POST** `/api/reembolsos` - Criar novo reembolso

## 🧪 Testes

```bash
npm test
```

## 📁 Estrutura do Projeto

```
meureembolsoapp/
├── src/
│   └── server.js          # Arquivo principal da aplicação
├── .env.example           # Exemplo de variáveis de ambiente
├── .gitignore             # Arquivos a ignorar no git
├── package.json           # Dependências do projeto
└── README.md              # Este arquivo
```

## 🔧 Variáveis de Ambiente

```
NODE_ENV=development
PORT=3000
API_URL=http://localhost:3000
```

## 📦 Dependências

- **express** - Framework web
- **cors** - Middleware CORS
- **morgan** - Logger HTTP
- **dotenv** - Gerenciamento de variáveis de ambiente

## 🚢 Deploy

Para fazer deploy, consulte a documentação de deploy no arquivo `.github/workflows/` (será criado em breve).

## 📝 Licença

MIT

## 👤 Autor

comeca-ai
