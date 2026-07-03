# Lampions Marketing — Site Completo

Site profissional da **Lampions Marketing**, agência de marketing digital em Recife/PE.

## O que tem aqui

| Arquivo | O que é |
|---|---|
| `index.html` | Landing page principal da agência |
| `roi-calculator.html` | Calculadora de ROI para apresentar a clientes |
| `assets/style.css` | Estilos compartilhados entre as páginas |

---

## Como hospedar no GitHub Pages (passo a passo)

> Não precisa saber programar. Só seguir as etapas abaixo.

### Etapa 1 — Criar conta no GitHub
1. Acesse [github.com](https://github.com) e clique em **Sign up**
2. Crie sua conta (é grátis)

---

### Etapa 2 — Criar um repositório
1. Depois de entrar, clique no botão verde **"New"** (ou no ícone **+** no canto superior direito → New repository)
2. Preencha assim:
   - **Repository name:** `lampions` (ou `site-lampions`)
   - **Visibility:** Public (obrigatório para GitHub Pages gratuito)
   - Deixa as outras opções como estão
3. Clique em **"Create repository"**

---

### Etapa 3 — Fazer upload dos arquivos
1. Na página do repositório que acabou de criar, clique em **"uploading an existing file"** (o link aparece no texto central)
2. **Arraste todos os arquivos** desta pasta para a área de upload:
   - `index.html`
   - `roi-calculator.html`
   - A pasta `assets/` com o arquivo `style.css` dentro
3. Lá embaixo, em **"Commit changes"**, deixa como está e clica em **"Commit changes"** (botão verde)

> **Atenção:** Para a pasta `assets/`, você precisa entrar nela e fazer o upload do `style.css` separadamente, ou usar o GitHub Desktop (veja abaixo).

---

### Etapa 3 (alternativa mais fácil) — Usar o GitHub Desktop
Se tiver dificuldade com o upload manual da pasta, use o **GitHub Desktop**:

1. Baixe em [desktop.github.com](https://desktop.github.com)
2. Faça login com sua conta do GitHub
3. Clique em **"Add an Existing Repository from your Hard Drive"**
4. Ou crie um repositório novo direto pelo app
5. Copie todos os arquivos do projeto para a pasta do repositório
6. No app, clique em **"Commit to main"** e depois em **"Push origin"**

---

### Etapa 4 — Ativar o GitHub Pages
1. No seu repositório, clique na aba **"Settings"** (engrenagem)
2. No menu lateral esquerdo, clique em **"Pages"**
3. Em **"Source"**, selecione: **Deploy from a branch**
4. Em **"Branch"**, selecione: **main** → **(root)** → clique em **Save**
5. Aguarde 1-2 minutos

---

### Etapa 5 — Acessar o site
Após ativar, o GitHub vai mostrar o endereço do seu site. Vai ser algo como:

```
https://SEU-USUARIO.github.io/lampions/
```

Guarda esse link — é o endereço do site! Você pode colocar na bio do Instagram.

---

## Personalizações antes de publicar

Antes de colocar o site no ar, lembre de ajustar:

### 1. Número de WhatsApp
Dentro dos arquivos `index.html` e `roi-calculator.html`, busque por:
```
5581999999999
```
E substitua pelo número real do WhatsApp do Paulo (com DDI 55 + DDD + número, sem espaços ou traços).

Exemplo: se o número for (81) 98765-4321, coloca `5581987654321`

### 2. Foto do Paulo
No `index.html`, há uma seção "Sobre Paulo" com um espaço reservado para foto. Para adicionar:
- Coloque a foto na pasta `assets/` com o nome `paulo.jpg`
- No `index.html`, encontre `<div class="about-photo">` e substitua o conteúdo interno por:
```html
<img src="assets/paulo.jpg" alt="Paulo Lampions" style="width:100%;height:100%;object-fit:cover;" />
```

### 3. Depoimentos reais
Os depoimentos no `index.html` são exemplos. Substitua pelos depoimentos reais de clientes.

### 4. Números de resultados
Nos cases e nos stats do hero, substitua pelos números reais da agência.

---

## Domínio personalizado (opcional)

Se quiser usar um domínio como `lampionsmarketing.com.br` em vez do link do GitHub:

1. Compre o domínio em [registro.br](https://registro.br) ou [GoDaddy](https://godaddy.com)
2. No GitHub Pages (Settings → Pages), adicione o domínio em **"Custom domain"**
3. Configure os DNS do domínio apontando para o GitHub (o GitHub mostra as instruções)

Ou hospede direto no **Netlify** (mais fácil para domínio personalizado):
1. Acesse [netlify.com](https://netlify.com) e crie conta
2. Arraste a pasta do projeto para o painel do Netlify
3. O site fica no ar em segundos com um link próprio

---

## Dúvidas?

Fala com quem fez esse projeto ou consulta a documentação oficial:
- GitHub Pages: [docs.github.com/pages](https://docs.github.com/en/pages)
- Netlify: [docs.netlify.com](https://docs.netlify.com)
