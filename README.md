# 🛍️ Nata Store BSB — Site de Roupas

Site vitrine desenvolvido para a **Nata Store BSB**, loja de roupas de grife em Brasília-DF. Projeto em front-end puro com foco em identidade visual premium e responsividade.

---

## 🖥️ Tecnologias utilizadas

- **HTML5** — estrutura semântica
- **CSS3** — estilização customizada
- **Bootstrap 5.3.3** — grid responsivo e componentes
- **Bootstrap Icons 1.11.3** — ícones de redes sociais
- **Google Fonts (Montserrat)** — tipografia

---

## 📁 Estrutura de arquivos

```
nata-store-bsb/
├── index.html        # Página principal
├── style.css         # Estilos customizados
└── img/
    ├── logo.jpg
    ├── imagem1.png   # Foto hero (banner principal)
    ├── kit_lacoste.jpg
    ├── camisa-time.png
    ├── kit-nike.jpg
    └── bone.png
```

---

## 📄 Seções do site

### 1. Navbar
Barra fixa no topo com efeito de vidro (`backdrop-filter: blur`). Contém o nome da loja e botão de atalho para a seção de Redes Sociais (visível apenas em desktop).

### 2. Hero Section
Banner fullscreen com foto de fundo, gradiente escuro e chamada principal da marca. Botão de scroll suave para o catálogo.

### 3. Catálogo
Grid de produtos com 4 categorias:

| Categoria | Link Drive | Preço |
|---|---|---|
| Kit's Lacoste | [Ver pasta](https://drive.google.com/drive/folders/1qoO3E0u3q1m1KLA16nlcmftBxd_rkslX) | A partir de R$ 159,90 |
| Camisetas de Time | [Ver pasta](https://drive.google.com/drive/folders/14SCbGZJLczjyaTwkcxawit3IyxwozkBv) | A partir de R$ 59,90 |
| Kit's Nike | [Ver pasta](https://drive.google.com/drive/folders/1LKLerCvkHOl7IJXp2_mZx3jPgbU81svm) | A partir de R$ 99,90 |
| Boné's | [Ver pasta](https://drive.google.com/drive/folders/1HrcgcdADMhhzRecdSLBWVzDwCPzjMXD-) | A partir de R$ 49,90 |

- **Desktop:** botão "Ver mais" aparece no hover com overlay escuro
- **Mobile:** botão "Ver mais" sempre visível abaixo do preço

### 4. Redes Sociais
Seção com botões para Instagram, WhatsApp e voltar ao início.

---

## 📱 Responsividade

| Dispositivo | Comportamento |
|---|---|
| Desktop (lg+) | Grid 3 colunas, hover com overlay |
| Tablet (md) | Grid 2 colunas |
| Mobile (sm) | Grid 1 coluna, botão Ver mais sempre visível |

---

## ⚙️ Como atualizar

### Adicionar WhatsApp
Quando disponível, substitua o `href="#"` do botão WhatsApp pelo link:
```
href="https://wa.me/5561NXXXXXXXX"
```
Exemplo com número fictício: `https://wa.me/556199999999`

### Adicionar novo produto ao catálogo
Copie um bloco `col-12 col-md-6 col-lg-4` dentro da `.row` do catálogo e altere:
- `src` da imagem
- `alt` da imagem
- `href` do Drive nos dois links (desktop e mobile)
- Nome e preço nos textos

### Atualizar preços
Edite o texto dentro da tag `<p class="card-price fw-bold">` de cada card.

---

## 🔗 Redes sociais

- Instagram: [@nata_storebsb](https://www.instagram.com/nata_storebsb/)
- WhatsApp: *a definir*

---

## 👨‍💻 Desenvolvimento

Desenvolvido por **Tiago de Aquino Nunes** — front-end puro, sem frameworks JavaScript.
