## 🌐 [English Version of README](README_EN.md)

# Pong - Jogador vs Computador

Este projeto é uma versão interativa do clássico jogo Pong, permitindo uma disputa entre um jogador e o computador. Ele apresenta diferentes níveis de dificuldade, personalização de nome do jogador, efeitos sonoros e uma experiência visual imersiva com animações e imagens dinâmicas.

## 🔨 Funcionalidades do Projeto

- **Modos de dificuldade:** Fácil, Médio e Difícil, ajustando o comportamento da inteligência artificial.
- **Controle total:** O jogador pode interagir usando teclado e mouse para configurar e jogar.
- **Personalização:** Insira o nome do jogador antes de iniciar o jogo.
- **Placar:** Registro de pontos para determinar o vencedor.
- **Interatividade sonora:** Sons exclusivos para colisões e gols.
- **Tela inicial e de reinício:** Navegação entre diferentes estados do jogo com botões intuitivos.

### Exemplo Visual do Projeto
![chrome-capture-2024-11-17](https://github.com/user-attachments/assets/e2e7401c-7ab5-4ce1-8ca9-bb911b9d85dd)

## ✔️ Técnicas e Tecnologias Utilizadas

- **JavaScript**: Lógica do jogo e manipulação de eventos.
- **Biblioteca p5.js**: Renderização e animações interativas.
- **HTML5**: Estruturação da aplicação.
- **CSS3**: Estilização e design responsivo.
- **p5.sound**: Implementação de efeitos sonoros.
- **Imagens e Áudio**: Sprites personalizados e arquivos de som.

## 📁 Estrutura do Projeto

- **index.html**: Estrutura principal da página.
- **script/**
    - `sketch.js`: Contém toda a lógica do jogo.
- **sounds/**
    - `bounce.wav`: Som de colisão.
    - `goal.wav`: Som de gol.
- **sprites/**
    - `barra01.png`: Sprite da raquete do jogador.
    - `barra02.png`: Sprite da raquete do computador.
    - `bola.png`: Sprite da bola.
    - `fundo1.png`, `fundo2.png`: Sprites do fundo do jogo.
    - `fundo_inicio.jfif`: Fundo da tela inicial.
- **style/**
    - `reset.css`: Reseta estilos padrão.
    - `style.css`: Configurações visuais e responsividade.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
    - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:
      ```bash
      node -v
      ```
    - Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:
      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

3. **Instale um servidor local**:
    - Use um servidor local como o [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code ou configure um servidor com:
      ```bash
      npx serve
      ```

4. **Abra o projeto**:
    - Navegue até o diretório do projeto e inicie o servidor local. Abra o navegador na URL fornecida.

## 🌐 Deploy

Para publicar o projeto e disponibilizá-lo online, você pode seguir os passos abaixo utilizando serviços gratuitos como o **GitHub Pages**, **Vercel**, ou **Netlify**:

### 1. **GitHub Pages**
- Faça o upload dos arquivos do projeto para um repositório no GitHub.
- Vá para as configurações do repositório no GitHub.
- Em **Settings > Pages**, configure a branch `main` (ou outra branch com o projeto) para servir o site.
- Após alguns minutos, seu projeto estará disponível no link fornecido pelo GitHub Pages (geralmente no formato `https://<seu-usuario>.github.io/<nome-do-repositorio>`).

### 2. **Vercel**
- Crie uma conta no [Vercel](https://vercel.com/).
- Clique em **New Project** e importe seu repositório GitHub.
- Configure as opções básicas e clique em **Deploy**.
- O Vercel gerará um link único para acessar o seu projeto (exemplo: `https://seu-projeto.vercel.app`).

### 3. **Netlify**
- Crie uma conta no [Netlify](https://www.netlify.com/).
- Arraste e solte a pasta do seu projeto na interface de deploy do Netlify.
- Aguarde a publicação e acesse o link gerado automaticamente (exemplo: `https://seu-projeto.netlify.app`).

### Requisitos para o Deploy
- Certifique-se de que todos os arquivos do projeto (HTML, CSS, JavaScript, sons e imagens) estão organizados corretamente.
- Ajuste os caminhos relativos no código, se necessário, para que todos os arquivos sejam encontrados no ambiente online.
- Teste localmente antes de fazer o deploy para evitar problemas de compatibilidade.

Escolha a plataforma que melhor atende às suas necessidades e publique seu projeto para compartilhá-lo com o mundo!
