# SOS Hidráulica — Site Oficial

Site institucional da SOS Hidráulica, publicado via GitHub Pages.

**Endereço:** Estrada Viçoso Jardim, 853 — Cubango, Niterói/RJ — CEP 24140-169  
**WhatsApp:** (21) 98049-8568  
**E-mail:** soshidraulica31@gmail.com  
**Instagram:** [@deborasoshidraulica](https://www.instagram.com/deborasoshidraulica/)

---

## 🌐 Acesso ao site
- GitHub Pages: `https://soshidraulica.github.io/site`
- Domínio personalizado: `https://www.soshidraulica.com.br`

---

## ⚙️ Ativar WhatsApp Business API (envio automático)

Após obter o Token e Phone ID na Meta, edite `index.html` e localize:

```js
var WA_TOKEN    = 'SEU_TOKEN_AQUI';
var WA_PHONE_ID = 'SEU_PHONE_ID_AQUI';
```

Substitua pelos seus dados e faça commit — o site atualiza em 2 minutos.

---

## 🔧 Como atualizar o site

1. Edite o arquivo `index.html` diretamente no GitHub
2. Clique em **Commit changes**
3. O GitHub Actions faz o deploy automaticamente em ~2 minutos

---

## 🌍 Configurar domínio próprio (registro.br)

Adicione estas entradas DNS no painel do **registro.br**:

| Tipo  | Nome | Valor                    |
|-------|------|--------------------------|
| A     | @    | 185.199.108.153          |
| A     | @    | 185.199.109.153          |
| A     | @    | 185.199.110.153          |
| A     | @    | 185.199.111.153          |
| CNAME | www  | soshidraulica.github.io  |

Depois em **Settings → Pages → Custom domain** coloque: `www.soshidraulica.com.br`  
Marque **Enforce HTTPS** para ativar o cadeado de segurança gratuito.
