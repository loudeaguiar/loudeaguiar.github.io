# Portfólio Louise Aguiar

Site profissional para posicionamento em oportunidades de impacto social.

## 🚀 Como publicar no GitHub Pages

### Passo 1: Criar repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique no botão **"+"** (canto superior direito) → **"New repository"**
3. Nome do repositório: `louiseaguiar.github.io` (exatamente assim!)
4. Deixe como **Public**
5. **NÃO** marque nenhuma opção (README, .gitignore, etc)
6. Clique em **"Create repository"**

### Passo 2: Preparar os arquivos

1. Baixe os arquivos deste portfólio
2. Adicione sua foto (renomeie para `eu.png`) na mesma pasta
3. Adicione screenshots do Democratizar (opcional neste momento)
4. Adicione seu CV em PDF (opcional)

### Passo 3: Subir os arquivos

**Opção A - Fazer upload direto pelo GitHub (mais fácil):**

1. No repositório criado, clique em **"uploading an existing file"**
2. Arraste os arquivos: `index.html`, `style.css`, `eu.png`
3. No campo de commit, escreva: "Primeiro commit - portfólio online"
4. Clique em **"Commit changes"**

**Opção B - Usar linha de comando (se souber Git):**

```bash
# Na pasta do seu projeto
git init
git add .
git commit -m "Primeiro commit - portfólio online"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/louiseaguiar.github.io.git
git push -u origin main
```

### Passo 4: Ativar GitHub Pages

1. No repositório, vá em **Settings** (⚙️)
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione: **Deploy from a branch**
4. Em **Branch**, selecione: **main** e pasta **/ (root)**
5. Clique em **Save**

### Passo 5: Aguardar e acessar

Aguarde 2-5 minutos e acesse:
**https://louiseaguiar.github.io**

Pronto! Seu site está no ar! 🎉

---

## 📝 Personalizações importantes

### 1. Adicionar imagens do Democratizar

No arquivo `index.html`, localize esta seção:

```html
<div class="projeto-image-placeholder">
    <p>Screenshot do Dashboard Democratizar.cc</p>
    <span>Adicione sua imagem aqui</span>
</div>
```

Substitua por:

```html
<img src="democratizar-dashboard.png" alt="Dashboard Democratizar.cc" class="projeto-image">
```

E adicione a imagem `democratizar-dashboard.png` no repositório.

### 2. Adicionar download do CV

No arquivo `index.html`, localize:

```html
<a href="#" class="btn btn-primary" download>Download CV</a>
```

Substitua por:

```html
<a href="Louise-Aguiar-CV.pdf" class="btn btn-primary" download>Download CV</a>
```

E adicione seu CV em PDF com este nome no repositório.

### 3. Atualizar conteúdos

Todos os textos estão no `index.html` e são fáceis de editar. Basta abrir no editor de texto e modificar.

---

## 🎨 Paleta de cores usada

- **Burgundy Dark:** #5C1A1A
- **Burgundy Main:** #7D2828
- **Burgundy Light:** #9B3636
- **Accent Orange:** #E85D04
- **Accent Light:** #F77F00

---

## 🔧 Manutenção

### Como atualizar o site depois de publicado

1. Edite os arquivos localmente
2. Volte ao repositório no GitHub
3. Clique em **Add file** → **Upload files**
4. Arraste os arquivos atualizados
5. Commit com mensagem descritiva
6. Aguarde 1-2 minutos para as mudanças aparecerem

### Adicionar Google Analytics (opcional)

Adicione antes do `</head>` no `index.html`:

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=SEU-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'SEU-ID');
</script>
```

---

## 📱 Compatibilidade

O site é 100% responsivo e funciona em:
- ✅ Desktop (Windows, Mac, Linux)
- ✅ Tablets
- ✅ Smartphones (iOS e Android)
- ✅ Todos os navegadores modernos

---

## 🆘 Problemas comuns

**Site não aparece após 5 minutos:**
- Verifique se o nome do repositório está correto: `louiseaguiar.github.io`
- Confirme que os arquivos estão na raiz (não em pastas)
- Verifique em Settings → Pages se está ativado

**Imagens não aparecem:**
- Confirme que os nomes dos arquivos estão exatos (case-sensitive)
- Verifique se as imagens foram enviadas para o repositório

**Fontes não carregam:**
- O site usa Google Fonts (precisa de internet)
- Elas carregam automaticamente

---

## 📞 Contatos do projeto

Louise Aguiar
- Email: loudeaguiar@gmail.com
- LinkedIn: linkedin.com/in/louiseaguiar
- Portfolio: louiseaguiar.github.io

---

**Última atualização:** Dezembro 2025
