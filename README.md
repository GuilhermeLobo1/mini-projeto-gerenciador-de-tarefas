# Gerenciador de Tarefas 

Mini projeto prático desenvolvido durante a formação **Geração Tech**.

## Funcionalidades
- Cadastro de tarefas via modal interativo
- Filtro de pesquisa de tarefas por título em tempo real
- Armazenamento / integração via API local (`api.json`)

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript (Vanilla)
- Boxicons
- JSON Server (Node.js)

## Como rodar o projeto localmente

1. Clone o repositório:
```bash
git clone https://github.com/GuilhermeLobo1/mini-projeto-gerenciador-de-tarefas.git
```

2. Acesse a pasta do projeto:
```bash
cd mini-projeto-gerenciador-de-tarefas
```

3. Instale as dependências:
```bash
npm install
```

4. Inicie o servidor da API:
```bash
npx json-server --watch api.json --port 3000
```

5. Abra o arquivo `index.html` no seu navegador.
