# Site Ricardo Magalhães — Instituto PDK

Site pessoal pronto para publicar no GitHub Pages.

## Arquivos
- `index.html` — o site
- `profile.jpg` — foto de perfil
- `banner.png` — banner Instituto PDK

## Como publicar no GitHub Pages

### 1. Crie um repositório no GitHub
- Acesse https://github.com/new
- Nome sugerido: `ricardomagalhaes`
- Marque como **Public**
- Clique em **Create repository**

### 2. Suba os 3 arquivos
Na página do repositório novo, clique em **"uploading an existing file"** e arraste:
- `index.html`
- `profile.jpg`
- `banner.png`

Depois clique em **Commit changes**.

### 3. Ative o GitHub Pages
- No repositório, clique em **Settings** (no topo)
- No menu lateral, clique em **Pages**
- Em **Source**, selecione branch `main` e pasta `/ (root)`
- Clique em **Save**

### 4. Pronto!
Em 1-2 minutos seu site estará no ar em:
`https://SEU-USUARIO.github.io/ricardomagalhaes/`

## ⚠️ Falta apenas um link

O link do **LinkedIn** está como placeholder (`href="#"`). Quando tiver a URL do seu perfil no LinkedIn, edite a linha do `index.html`:

```html
<a href="#" target="_blank" rel="noopener" class="link-button">
```

E troque o `#` pelo link real, por exemplo:
```html
<a href="https://www.linkedin.com/in/ricardo-magalhaes/" target="_blank" rel="noopener" class="link-button">
```
