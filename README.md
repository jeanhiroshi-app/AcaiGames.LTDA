# Açaí Games LTDA - Website

Site oficial da Açaí Games LTDA, estúdio independente de desenvolvimento de jogos digitais.

## 🎮 Sobre o Projeto

Landing page profissional desenvolvida para apresentar a empresa, suas áreas de atuação, oportunidades de carreira e planos de expansão.

## 📁 Estrutura de Arquivos

```
acai-games-website/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Scripts JavaScript
└── README.md           # Este arquivo
```

## 🚀 Como Hospedar no GitHub Pages

### Passo 1: Criar um Repositório no GitHub

1. Acesse [GitHub](https://github.com) e faça login
2. Clique no botão **"New"** (Novo) para criar um novo repositório
3. Nomeie o repositório (ex: `acai-games-website`)
4. Deixe como **Public** (Público)
5. **NÃO** marque "Add a README file"
6. Clique em **"Create repository"**

### Passo 2: Fazer Upload dos Arquivos

#### Opção A: Via Interface Web do GitHub (Mais Fácil)

1. No seu repositório recém-criado, clique em **"uploading an existing file"**
2. Arraste os arquivos para a área indicada:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Adicione uma mensagem de commit (ex: "Adicionar arquivos iniciais do site")
4. Clique em **"Commit changes"**

#### Opção B: Via Git Command Line

```bash
# No terminal, navegue até a pasta com os arquivos
cd caminho/para/pasta

# Inicialize o Git
git init

# Adicione os arquivos
git add .

# Faça o commit
git commit -m "Adicionar arquivos iniciais do site"

# Adicione o repositório remoto (substitua SEU-USUARIO e SEU-REPOSITORIO)
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git

# Envie os arquivos
git branch -M main
git push -u origin main
```

### Passo 3: Ativar o GitHub Pages

1. No seu repositório, vá em **Settings** (Configurações)
2. No menu lateral, clique em **Pages**
3. Em **"Source"**, selecione **"Deploy from a branch"**
4. Em **"Branch"**, selecione **"main"** e pasta **"/ (root)"**
5. Clique em **"Save"**
6. Aguarde alguns minutos (geralmente 2-5 minutos)
7. Seu site estará disponível em: `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`

## 🌐 URL do Site

Após a configuração, seu site ficará disponível em:
```
https://SEU-USUARIO.github.io/acai-games-website/
```

Substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub.

## ✨ Funcionalidades

- ✅ Design responsivo (funciona em mobile e desktop)
- ✅ Animações suaves ao rolar a página
- ✅ Navegação smooth scroll
- ✅ Seções informativas sobre a empresa
- ✅ Formulário de contato
- ✅ Layout moderno e profissional

## 🎨 Personalização

### Alterar Cores

Edite o arquivo `styles.css` e modifique as cores do gradiente:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Alterar Conteúdo

Edite o arquivo `index.html` para modificar textos, adicionar seções ou alterar informações.

### Adicionar Imagens

1. Crie uma pasta `images` no repositório
2. Faça upload das imagens
3. No HTML, use: `<img src="images/nome-da-imagem.jpg">`

## 📧 Contato

Para sugestões ou problemas, entre em contato através de:
- Email: contato@acaigames.com.br

## 📝 Licença

© 2024 Açaí Games LTDA. Todos os direitos reservados.

---

**Desenvolvido com ❤️ para Açaí Games LTDA**