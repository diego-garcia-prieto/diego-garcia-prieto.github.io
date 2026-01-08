# 📊 Portfólio - Diego da Silva Garcia Prieto

Portfolio profissional de projetos em Business Intelligence e Data Analytics.

🌐 **URL:** https://seu-usuario.github.io

---

## 🚀 Como Colocar no Ar (Passo a Passo)

### **PASSO 1: Criar Conta no GitHub**

1. Acesse: https://github.com
2. Clique em **"Sign up"** (Cadastrar)
3. Crie sua conta (use um nome de usuário profissional, ex: `diego-garcia-prieto`)
4. Confirme seu email

---

### **PASSO 2: Criar Repositório**

1. No GitHub, clique no **"+"** no canto superior direito
2. Selecione **"New repository"**
3. Configure:
   - **Repository name:** `seu-usuario.github.io` (IMPORTANTE: use exatamente o nome do seu usuário + `.github.io`)
   - **Public** (deixe marcado)
   - ✅ Marque **"Add a README file"**
4. Clique em **"Create repository"**

---

### **PASSO 3: Fazer Upload dos Arquivos**

**OPÇÃO A - Via Web (Mais Fácil):**

1. No seu repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste TODOS os arquivos do portfólio:
   - `index.html`
   - Pasta `css/` (com `style.css` e `project.css`)
   - Pasta `images/` (com suas imagens)
   - Pasta `projects/` (com as páginas HTML dos projetos)
3. Escreva uma mensagem de commit: `"Adiciona portfólio inicial"`
4. Clique em **"Commit changes"**

**OPÇÃO B - Via GitHub Desktop (Recomendado se for atualizar muito):**

1. Baixe GitHub Desktop: https://desktop.github.com/
2. Instale e faça login
3. Clone o repositório
4. Copie todos os arquivos para a pasta local
5. Commit → Push

---

### **PASSO 4: Ativar GitHub Pages**

1. No repositório, vá em **"Settings"** (Configurações)
2. No menu lateral, clique em **"Pages"**
3. Em **"Source"**, selecione:
   - Branch: `main`
   - Folder: `/ (root)`
4. Clique em **"Save"**
5. Aguarde 1-2 minutos
6. **PRONTO!** Seu site estará em: `https://seu-usuario.github.io`

---

## 📁 Estrutura de Arquivos

```
portfolio/
│
├── index.html              # Página principal
├── README.md               # Este arquivo
│
├── css/
│   ├── style.css          # Estilos gerais
│   └── project.css        # Estilos das páginas de projeto
│
├── images/
│   ├── profile.jpg        # Sua foto (VOCÊ PRECISA ADICIONAR!)
│   ├── da-dashboard.png
│   ├── reclamacoes-dashboard.png
│   ├── zendesk-dashboard.png
│   ├── rpa-interface.png
│   └── prophet-model.png
│
└── projects/
    ├── customer-service.html
    ├── complaints-analysis.html
    ├── zendesk-automation.html
    ├── rpa-automation.html
    └── prophet-forecasting.html
```

---

## 🖼️ Preparar as Imagens

### **Imagens que você precisa adicionar:**

1. **profile.jpg** - Sua foto profissional
   - Tamanho recomendado: 400x400px
   - Formato: JPG ou PNG
   - Dica: Fundo neutro, roupa profissional

2. **da-dashboard.png** - Screenshot do Dashboard de Atendimento
3. **reclamacoes-dashboard.png** - Screenshot do Dashboard de Reclamações
4. **zendesk-dashboard.png** - Screenshot do Dashboard Zendesk
5. **rpa-interface.png** - Screenshot da interface RPA
6. **prophet-model.png** - Gráfico do modelo Prophet

**Onde colocar:** Pasta `images/`

---

## ✏️ Personalizar o Portfólio

### **1. Editar suas informações (index.html):**

Procure e substitua:

```html
<!-- Linha ~35 -->
<a href="https://www.linkedin.com/in/seu-linkedin" target="_blank">

<!-- Linha ~38 -->
<a href="https://github.com/seu-github" target="_blank">

<!-- Linha ~41 -->
<a href="mailto:seu-email@exemplo.com">
```

### **2. Adicionar sua foto:**

```html
<!-- Linha ~25 -->
<img src="images/profile.jpg" alt="Diego Garcia">
```

---

## 🔄 Como Atualizar o Portfólio

1. Faça as mudanças nos arquivos HTML/CSS
2. No GitHub:
   - Opção A: Upload direto via web
   - Opção B: GitHub Desktop → Commit → Push
3. Aguarde 1-2 minutos
4. Atualize a página no navegador (Ctrl + F5)

---

## 📱 Adicionar ao LinkedIn

### **Seção "Destaque":**

1. No seu perfil LinkedIn, vá em **"Destaque"**
2. Clique em **"+"** → **"Adicionar link"**
3. Cole a URL: `https://seu-usuario.github.io`
4. Título: **"Portfólio de Projetos - Data Analytics & BI"**
5. Descrição (opcional): "Confira meus principais projetos em Business Intelligence, análise de dados e automação."

### **Campo "Website":**

1. Edite seu perfil
2. Seção "Informações de contato"
3. Adicione a URL no campo **"Website"**

---

## 🎨 Cores do Tema

- **Primary:** #2563eb (Azul)
- **Secondary:** #1e40af (Azul Escuro)
- **Success:** #10b981 (Verde)
- **Warning:** #f59e0b (Laranja)

Para mudar as cores, edite o arquivo `css/style.css` nas linhas 10-16.

---

## ❓ Dúvidas Frequentes

**Q: Quanto tempo demora para o site ficar online?**
A: 1-2 minutos após ativar o GitHub Pages.

**Q: Posso usar domínio próprio (ex: diegogarcia.com)?**
A: Sim! No GitHub Pages Settings, você pode configurar custom domain.

**Q: É gratuito?**
A: Sim, 100% gratuito no GitHub Pages.

**Q: Como adiciono mais projetos?**
A: Duplique uma página de projeto existente, renomeie e edite o conteúdo. Depois adicione o card na `index.html`.

---

## 🆘 Suporte

Se tiver dúvidas:
1. Consulte a documentação: https://docs.github.com/pt/pages
2. Revise os passos neste README
3. Peça ajuda no GitHub Community

---

**Bom trabalho! 🚀**
