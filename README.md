<div align="center">

<img src="https://aws-cloud-club-univali.s3.sa-east-1.amazonaws.com/imagens/logo-mascote.png" width="120" alt="AWS Cloud Club Mascote"/>

# Apresentação de Introdução — AWS Cloud Club Univali

Slides interativos em HTML para a apresentação de lançamento e introdução ao **AWS Cloud Club Univali**.

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![UNIVALI](https://img.shields.io/badge/UNIVALI-Itajaí--SC-004B8D?style=for-the-badge)](https://www.univali.br)

</div>

---

## Sobre

Apresentação de slides construída em **HTML + CSS puro**, com tema espacial/galáctico, animações CSS e layout em formato 1280×720px (16:9). Ideal para ser exibida em tela cheia no navegador durante eventos presenciais ou online.

**Design:**
- Fundo galáctico escuro (`#080512`) com campo de estrelas animado
- Efeito glassmorphism nos slides (backdrop blur)
- Paleta: roxo/azul como cor primária e laranja AWS (`#ff9900`) como destaque
- Tipografia: Poppins (títulos) + Inter (corpo)

---

## Conteúdo dos Slides

| # | Tema |
|---|------|
| 1 | Capa — AWS Cloud Club Univali |
| 2 | O que é Cloud Computing? |
| 3 | Serviços AWS (EC2, Lambda, S3, RDS, DynamoDB, SageMaker, Bedrock...) |
| 4 | Sobre o Cloud Club |
| 5 | Time de liderança |
| 6 | Certificações AWS da equipe |
| 7 | Como participar — QR Codes |

---

## Como usar

### Apresentação ao vivo

```bash
# Não precisa instalar nada — abra direto no navegador
open index.html
# ou no Linux:
xdg-open index.html
```

**Navegação pelos slides:**
- `→` / `Space` — próximo slide
- `←` — slide anterior
- `F11` — tela cheia (recomendado para eventos)

### Hospedagem rápida (GitHub Pages)

1. Faça push do repositório para o GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione `main` e pasta `/ (root)`
4. Acesse o link gerado — a apresentação fica disponível online

---

## Estrutura do Projeto

```
apresentacao-introducao-cloud-club/
├── index.html        # Apresentação completa (slides + CSS + JS)
└── imagens/          # Assets: logos, fotos do time, badges AWS, QR codes
    ├── logo-mascote.png
    ├── logo-roxo.png
    ├── perfil-henrique.jpg
    ├── aws-certification-*.png
    └── qrcode-*.png
```

---

## Personalização

Para adaptar a apresentação para um novo evento:

**Atualizar o time:**
```html
<!-- Localize o slide do time e edite nome/cargo/foto -->
<h3 class="member-name">Seu Nome</h3>
<p class="member-role">Seu Cargo</p>
<img src="imagens/sua-foto.jpg" alt="Foto" />
```

**Atualizar QR Codes:**
```html
<!-- Substitua as imagens dos QR codes -->
<img src="imagens/qrcode-inscricao.png" alt="QR Code Inscrição" />
```

**Adicionar novo slide:**
```html
<div class="slide" id="slide-N">
  <div class="slide-content">
    <!-- seu conteúdo aqui -->
  </div>
</div>
```

---

## Tech Stack

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura dos slides |
| CSS3 | Animações, glassmorphism, layout responsivo |
| JavaScript | Navegação entre slides via teclado |
| Google Fonts | Poppins + Inter |
| Font Awesome 6 | Ícones |

---

<div align="center">

Feito com ☁️ pelo **AWS Cloud Club Univali**

</div>
# apresentacao-introducao-cloud-club
