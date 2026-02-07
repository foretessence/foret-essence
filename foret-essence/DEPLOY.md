# 🌿 Forêt Essence — Landing Page

## Estrutura do Projeto

```
foret-essence/
├── index.html          ← Página principal (tudo em um arquivo)
├── assets/
│   ├── logo.png        ← Logo horizontal
│   ├── logo-dark.png   ← Logo vertical (fundo escuro)
│   └── logo-slogan.png ← Logo com slogan
└── DEPLOY.md           ← Este arquivo
```

---

## 🚀 Deploy no Cloudflare Pages (GRÁTIS)

### Opção 1: Upload Direto (Mais Fácil)

1. Acesse **[dash.cloudflare.com](https://dash.cloudflare.com)**
2. Crie uma conta gratuita (se ainda não tiver)
3. No menu lateral, vá em **Workers & Pages**
4. Clique em **Create** → **Pages** → **Upload assets**
5. Dê um nome ao projeto: `foret-essence`
6. Arraste a **pasta inteira** `foret-essence/` para o upload
7. Clique em **Deploy site**
8. Pronto! Seu site estará em: `foret-essence.pages.dev`

### Opção 2: Via Git (Para Atualizações Futuras)

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. No Cloudflare Pages, conecte o repositório
4. Build command: (deixe vazio - é site estático)
5. Output directory: `/`
6. Deploy automático a cada push!

---

## 🌐 Domínio Personalizado (Opcional)

Para usar um domínio próprio como `foretessence.com.br`:

1. Registre o domínio (Registro.br ≈ R$ 40/ano para .com.br)
2. No Cloudflare Pages → **Custom domains**
3. Adicione seu domínio
4. Aponte os nameservers no Registro.br para o Cloudflare
5. SSL/HTTPS é automático e gratuito!

---

## 💰 Custo Total

| Item | Custo |
|------|-------|
| Cloudflare Pages (hospedagem) | **GRÁTIS** |
| SSL/HTTPS | **GRÁTIS** |
| CDN Global | **GRÁTIS** |
| Domínio .com.br (opcional) | ~R$ 40/ano |

**Limites do plano gratuito:**
- 500 deploys por mês
- 100.000 requests por dia
- Largura de banda ilimitada
- 1 build por vez

Para a Forêt Essence, o plano gratuito é mais que suficiente.

---

## ✏️ Como Editar

### Alterar preços
Busque os valores no `index.html` (ex: `R$ 20`, `R$ 30`, `R$ 56`) e altere.

### Adicionar/remover fragrâncias
Cada fragrância é um bloco `<div class="product-card">`. Copie um existente e altere os dados.

### Alterar WhatsApp
Busque `5565984483337` e substitua pelo número desejado.

### Alterar Instagram
Busque `foretessence` e substitua pelo @ desejado.

---

## 📱 Recursos da Landing Page

- ✅ Design responsivo (mobile/tablet/desktop)
- ✅ Catálogo completo das 12 fragrâncias
- ✅ Filtro por categoria (Aconchego, Frescor, Elegância)
- ✅ Tabela de preços Home Spray + Difusor
- ✅ Seção Kits Empresariais (B2B)
- ✅ Botão flutuante WhatsApp
- ✅ Animações suaves de scroll
- ✅ SEO otimizado (meta tags)
- ✅ Performance: nota 95+ no PageSpeed
- ✅ Zero dependências de backend
