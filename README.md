# NLW Agents

Aplicação web para demonstrar o uso de agentes inteligentes.

## 🛠️ Tecnologias

- **React 19** - Biblioteca para construção de interfaces
- **TypeScript** - Tipagem estática para JavaScript
- **Vite** - Build tool e dev server
- **React Router DOM** - Roteamento da aplicação
- **TanStack Query** - Gerenciamento de estado e cache
- **Tailwind CSS** - Framework CSS utilitário
- **Radix UI** - Componentes acessíveis
- **Lucide React** - Ícones
- **Biome** - Linter e formatter

## 📁 Estrutura do Projeto

```
src/
├── components/
│   └── ui/          # Componentes base (shadcn/ui)
├── lib/
│   └── utils.ts     # Utilitários
├── pages/
│   ├── create-room.tsx
│   └── room.tsx
└── app.tsx          # Componente principal
```

## 🚀 Setup

1. **Clone o repositório**
```bash
git clone <url-do-repositorio>
cd nlw-agents/web
```

2. **Instale as dependências**
```bash
npm install
```

3. **Execute o projeto**
```bash
npm run dev
```

4. **Acesse a aplicação**
```
http://localhost:5173
```

## 📜 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção

## 🎨 Padrões de Projeto

- **Componentes UI**: Utiliza padrão shadcn/ui com Radix UI
- **Roteamento**: React Router DOM para navegação
- **Estado**: TanStack Query para gerenciamento de estado
- **Estilização**: Tailwind CSS com class-variance-authority
- **Formatação**: Biome para linting e formatação

## 🔧 Configurações

- **TypeScript**: Configurado com strict mode
- **Path Mapping**: Alias `@` para `./src`
- **Vite**: Configurado com plugin React e Tailwind
- **Biome**: Extensão do ultracite para formatação 

## Backend
O projeto consome uma API que deve estar rodando na porta 3333. Certifique-se de que o backend esteja configurado e executando antes de iniciar o frontend.