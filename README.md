# 🍔 Casa Da Fome 

Landing page para lanchonete artesanal, com cardápio, seção sobre, depoimentos e formulário de contato.

---

## 📁 Estrutura do projeto

```
gordao-lanches/
├── index.html   ← estrutura e conteúdo da página
├── style.css    ← toda a estilização visual
└── README.md    ← este arquivo
```

> ⚠️ Os arquivos `index.html` e `style.css` precisam estar **na mesma pasta** para o site funcionar corretamente.

---

## 🚀 Como usar

1. Baixe ou clone este repositório
2. Abra o arquivo `index.html` no navegador — sem necessidade de servidor ou instalação

Para publicar online, basta fazer o upload dos dois arquivos (`index.html` e `style.css`) para qualquer serviço de hospedagem estática, como [GitHub Pages](https://pages.github.com/), [Netlify](https://netlify.com/) ou [Vercel](https://vercel.com/).

---

## ✏️ Como editar o conteúdo

### Texto e informações
Tudo está no `index.html`. Cada seção tem um comentário indicando onde começa:

| Comentário no HTML | O que editar |
|---|---|
| `<!-- HEADER -->` | Nome e links do menu |
| `<!-- HERO -->` | Título, descrição e estatísticas |
| `<!-- CARDÁPIO -->` | Itens, preços e fotos do cardápio |
| `<!-- SOBRE -->` | História e valores da lanchonete |
| `<!-- DEPOIMENTOS -->` | Textos e nomes dos clientes |
| `<!-- CONTATO -->` | WhatsApp, endereço e horário |
| `<!-- FOOTER -->` | Links do rodapé |

### Cores
As cores estão centralizadas no início do `style.css` como variáveis CSS — basta alterar lá e o site inteiro atualiza:

```css
:root {
  --red: #E8291C;       /* cor principal */
  --red-dark: #C01F14;  /* hover dos botões */
  --yellow: #FFB800;    /* estrelas dos depoimentos */
  --bg: #0D0D0D;        /* fundo da página */
  --text: #F2EDE4;      /* cor do texto */
}
```

### Fotos
As imagens vêm do Unsplash via URL. Para trocar por fotos próprias, substitua o atributo `src` de cada `<img>` pelo caminho da sua imagem local ou por outra URL.

### WhatsApp
Procure por `wa.me/5511999999999` no `index.html` e substitua pelo número real (somente dígitos, com código do país).

---

## 🛠️ Tecnologias

- HTML5 e CSS3 puros — sem frameworks, sem dependências
- JavaScript vanilla para interações (menu mobile, abas do cardápio, animações de scroll)
- Fontes via Google Fonts: **Bebas Neue**, **Fraunces** e **DM Sans**
- Imagens via [Unsplash](https://unsplash.com/)

---

## 📄 Licença

Projeto de uso livre. Adapte à vontade para o seu negócio.
