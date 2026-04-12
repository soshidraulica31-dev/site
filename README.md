# SOS Hidráulica — Site Oficial

Site institucional da **SOS Hidráulica**, publicado via GitHub Pages.

**Endereço:** Estrada Viçoso Jardim, 853 — Cubango, Niterói/RJ — CEP 24140-169
**WhatsApp:** (21) 98049-8568
**E-mail:** soshidraulica31@gmail.com
**Instagram:** [@deborasoshidraulica](https://www.instagram.com/deborasoshidraulica/)

---

## 🌐 Site no ar

- **URL:** [www.soshidraulica.com.br](https://www.soshidraulica.com.br)
- **Backup:** [soshidraulica31-dev.github.io/site](https://soshidraulica31-dev.github.io/site)

---

## 📁 Estrutura do repositório

```
site/
├── index.html                    ← Site completo (único arquivo)
├── CNAME                         ← Domínio personalizado
├── README.md                     ← Este arquivo
└── .github/
    └── workflows/
        └── deploy.yml            ← Deploy automático
```

---

## ✏️ Como atualizar o site

1. Clique em **`index.html`** no repositório
2. Clique no ícone de **lápis ✏️** (Edit)
3. Faça as alterações desejadas
4. Clique em **Commit changes**
5. Aguarde **~2 minutos** — o GitHub Actions atualiza automaticamente

---

## ⚙️ Ativar envio automático via WhatsApp Business API

Após obter o Token e Phone ID na Meta for Developers, edite `index.html` e localize no início do `<script>`:

```js
var WA_TOKEN    = 'SEU_TOKEN_AQUI';
var WA_PHONE_ID = 'SEU_PHONE_ID_AQUI';
```

Substitua pelos seus dados e faça commit. O site atualiza em ~2 minutos.

---

## 🌍 Configuração DNS (registro.br)

| Tipo  | Nome | Valor                           |
|-------|------|---------------------------------|
| A     | @    | 185.199.108.153                 |
| A     | @    | 185.199.109.153                 |
| A     | @    | 185.199.110.153                 |
| A     | @    | 185.199.111.153                 |
| CNAME | www  | soshidraulica31-dev.github.io   |

Em **Settings → Pages → Custom domain**: `www.soshidraulica.com.br`
Marque **Enforce HTTPS** ✅

---

## 📱 Funcionalidades do site

- ✅ Design responsivo (mobile, tablet, desktop)
- ✅ Portfólio com 11 fotos reais dos trabalhos
- ✅ 5 vídeos do YouTube (Shorts) no portfólio
- ✅ Filtros por categoria: Todos / Obras Civis / Hidráulica / Vídeos
- ✅ Modal de orçamento com WhatsApp + E-mail
- ✅ Formulário de contato com validação
- ✅ Animações nos botões e cards
- ✅ Imagens de fundo das obras reais
- ✅ Integração pronta para WhatsApp Business API
- ✅ HTTPS gratuito via Let's Encrypt
- ✅ Deploy automático a cada atualização
