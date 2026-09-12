# 🚚 Sistema Completo de Delivery

Sistema profissional de delivery com app para entregadores, plataforma para comerciantes e painel administrativo.

## 🏗️ Arquitetura do Projeto

```
delivery-system-complete/
├── backend/                    # API REST Node.js
├── web-merchant/              # Plataforma web para comerciantes
├── web-admin/                 # Painel administrativo
├── mobile-driver/             # App mobile React Native para entregadores
├── shared/                    # Tipos e utilitários compartilhados
└── docs/                      # Documentação
```

## 🎯 Funcionalidades Principais

### 👨‍💼 Comerciante
- ✅ Cadastro e autenticação
- ✅ Criar e gerenciar entregas
- ✅ Atribuir entregadores
- ✅ Rastreamento em tempo real
- ✅ Histórico de entregas
- ✅ Relatórios e ganhos
- ✅ Integração com pagamentos
- ✅ Notificações push

### 🚴 Entregador
- ✅ Cadastro e autenticação
- ✅ Receber entregas disponíveis
- ✅ Aceitar/rejeitar entregas
- ✅ GPS em tempo real
- ✅ Navegação com mapas
- ✅ Histórico de ganhos
- ✅ Sistema de avaliações
- ✅ Suporte in-app

### 👨‍💻 Administrador
- ✅ Dashboard analytics
- ✅ Gerenciar usuários
- ✅ Gerenciar transações
- ✅ Relatórios detalhados
- ✅ Suporte ao cliente
- ✅ Configurações do sistema

## 🛠️ Stack Tecnológico

### Backend
- Node.js + Express
- PostgreSQL + Sequelize
- JWT + OAuth2
- Socket.io (tempo real)
- Redis (cache/fila)
- Stripe/PayPal (pagamentos)
- SendGrid (emails)
- Firebase (notificações push)

### Web - Comerciante
- React 18
- TypeScript
- Redux Toolkit
- Material-UI
- Google Maps API
- Axios

### Web - Admin
- React 18
- TypeScript
- Redux Toolkit
- Chart.js
- Ant Design

### Mobile - Entregador
- React Native
- Expo
- TypeScript
- Redux Toolkit
- React Navigation
- Google Maps
- Geolocation

## 📦 Instalação

### Pré-requisitos
- Node.js 18+
- PostgreSQL 14+
- Redis
- npm ou yarn

### Setup Rápido

```bash
# Clone o repositório
git clone https://github.com/rodrigobalboa0-source/delivery-system-complete.git
cd delivery-system-complete

# Instale dependências
npm run install:all

# Configure variáveis de ambiente
cp .env.example .env

# Execute migrações
npm run db:migrate

# Inicie o servidor de desenvolvimento
npm run dev
```

## 📚 Documentação

- [API REST](./docs/API.md)
- [Banco de Dados](./docs/DATABASE.md)
- [Autenticação](./docs/AUTH.md)
- [Tempo Real (WebSockets)](./docs/REALTIME.md)

## 📄 Licença

MIT License - veja LICENSE.md

## 👥 Suporte

Para dúvidas ou issues, abra uma [issue no GitHub](https://github.com/rodrigobalboa0-source/delivery-system-complete/issues)