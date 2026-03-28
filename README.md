# 🌐 Site - Luiza Rosa Neto | Psicóloga Psicomotricidade

Site profissional em Node.js com SEO otimizado para "psicóloga psicomotricidade".

---

## 🚀 Como rodar localmente

```bash
# 1. Instalar dependências
npm install

# 2. Rodar em desenvolvimento
npm run dev

# 3. Abrir no navegador
# http://localhost:3000
```

---

## ☁️ Como publicar na web (Railway — GRATUITO)

### Passo 1 — Criar conta no GitHub
- Acesse https://github.com e crie uma conta gratuita

### Passo 2 — Criar repositório
- Clique em "New repository"
- Nome: `luiza-rosa-psicologa`
- Clique em "Create repository"

### Passo 3 — Enviar o código
```bash
git init
git add .
git commit -m "Site Luiza Rosa Neto"
git remote add origin https://github.com/SEU_USUARIO/luiza-rosa-psicologa.git
git push -u origin main
```

### Passo 4 — Deploy no Railway
1. Acesse https://railway.app
2. Faça login com sua conta GitHub
3. Clique em "New Project" → "Deploy from GitHub repo"
4. Selecione o repositório `luiza-rosa-psicologa`
5. Railway detecta automaticamente Node.js e faz o deploy ✅
6. Acesse "Settings" → "Domains" → gere um domínio gratuito

---

## 🔍 Como aparecer no Google

### 1. Google Search Console (OBRIGATÓRIO)
1. Acesse https://search.google.com/search-console
2. Clique em "Adicionar propriedade"
3. Insira a URL do site (ex: `https://luiza-rosa-psicologa.up.railway.app`)
4. Faça a verificação conforme instruções
5. Vá em "Sitemaps" → insira `https://SEU_SITE/sitemap.xml`
6. Clique em "Enviar"

### 2. Google Meu Negócio (MUITO IMPORTANTE para aparecer localmente)
1. Acesse https://business.google.com
2. Crie ou reivindique o perfil da Luiza Rosa Neto
3. Preencha: endereço, telefone, horário, especialidade
4. Adicione fotos profissionais
5. Solicite avaliações de clientes

### 3. Atualize o Instagram
- Na bio do Instagram, adicione o link do site
- Isso aumenta a autoridade do site para o Google

### 4. Dicas extras de SEO
- Peça para outras psicólogas ou blogs linkarem para o site
- Publique posts no Instagram com a hashtag #psicomotricidade
- Atualize o site periodicamente com novos conteúdos

---

## ✏️ Como personalizar o site

### Alterar o handle do Instagram
No arquivo `public/index.html`, procure por:
```
@luiza.rosa
```
E substitua pelo perfil correto.

### Adicionar foto
Substitua a seção `.sobre-frame` por uma tag `<img>` com sua foto profissional.

### Adicionar CRP
Procure por `CRP XX/XXXXX` e substitua pelo número real.

### Alterar cor de fundo
No `:root` do CSS, altere `--chocolate: #3B1F0E` para a cor desejada.

---

## 📁 Estrutura do projeto

```
luiza-rosa-psicologa/
├── server.js          # Servidor Node.js/Express
├── package.json       # Dependências
├── railway.toml       # Config de deploy
├── .gitignore
├── README.md
└── public/
    └── index.html     # Site completo (HTML + CSS + JS)
```
