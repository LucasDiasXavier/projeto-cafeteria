# ☕ Manhattan - Coffee House

> Site institucional de uma cafeteria premium, desenvolvido com HTML e CSS puro, com efeito parallax e design elegante inspirado na identidade visual da marca.

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

---

## 📸 Visão Geral

A **Manhattan Coffee House** é uma landing page desenvolvida para uma cafeteria especializada em cafés gourmet e especiais. O projeto apresenta a história da marca, seus diferenciais, informações de contato, localização e horários de funcionamento — tudo em uma experiência visual imersiva com rolagem em parallax.

---

## 🚀 Funcionalidades

- **Navbar fixa** com navegação suave por âncoras para as seções da página
- **Efeito Parallax** em 5 seções distintas com imagens de fundo de alta qualidade
- **Seção de Informações** com textos sobre a identidade e os diferenciais do café
- **Mapa interativo** do Google Maps com o endereço da cafeteria
- **Dados de contato** (telefone, WhatsApp e e-mail)
- **Grade de horários** de funcionamento com layout visual limpo
- **Rodapé** com botão de retorno ao topo da página
- **Responsividade básica** com media query para telas com zoom aplicado

---

## 🗂️ Estrutura do Projeto

```
manhattan-coffee-house/
│
├── index.html               # Estrutura principal da página
├── style.css                # Estilos e layout
│
└── assets/
    ├── logo.png             # Logo da cafeteria
    ├── parallax-imagem1.png # Banner principal
    ├── parallax-imagem2.jpg # Seção 2 de parallax
    ├── parallax-imagem3.jpg # Seção 3 de parallax
    ├── parallax-imagem4.png # Seção de contatos
    ├── cafeteria.jpg        # Seção de horários
    └── seta-para-cima.png   # Botão de voltar ao topo
```

---

## 🎨 Design & Identidade Visual

O projeto utiliza uma paleta sofisticada alinhada à identidade de uma cafeteria premium:

| Cor | Hex | Uso |
|---|---|---|
| Marrom escuro | `#604829` | Header, destaques, fundos |
| Dourado caramelo | `#c4a47c` | Títulos, links, acentos |
| Cinza suave | `#666` | Textos corridos |
| Cinza médio | `#acacac` | Detalhes e horários |
| Preto | `#000000` | Rodapé |

**Tipografias utilizadas:**
- **Fraunces** — Títulos principais (serif elegante)
- **Oswald** — Subtítulos e navegação (sans-serif condensada)
- **Lato** — Textos de leitura e rodapé (sans-serif limpa)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica da página
- **CSS3** — Estilização, parallax com `background-attachment: fixed`, posicionamento e responsividade
- **Google Maps Embed API** — Mapa interativo na seção de contatos
- **Google Fonts** — Tipografias Fraunces, Oswald e Lato

---

## ⚙️ Como Executar o Projeto

Não há dependências ou build necessários. Basta clonar o repositório e abrir o arquivo HTML no navegador.

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/manhattan-coffee-house.git

# Acesse a pasta do projeto
cd manhattan-coffee-house

# Abra no navegador
# Dê duplo clique em index.html, ou use uma extensão como Live Server no VS Code
```

> 💡 **Recomendação:** Use a extensão **Live Server** do VS Code para melhor experiência de desenvolvimento com recarregamento automático.

---

## 📱 Responsividade

O projeto conta com um breakpoint via `@media (max-height: 768px)` que ajusta elementos para telas com zoom aplicado, como:

- Redução do logo no topo
- Ajuste de altura do iframe do mapa
- Reposicionamento da lista de horários

> ⚠️ O layout é otimizado para desktop. Melhorias de responsividade mobile completa podem ser implementadas como evolução futura.

---

## 📌 Seções da Página

| Seção | Descrição |
|---|---|
| `#banner` | Hero com imagem parallax e nome da marca |
| `#informações` | Textos sobre a história e diferenciais do café |
| `#contatos` | Mapa do Google + dados de contato |
| `#horarios` | Grade semanal de funcionamento |

---

## 👨‍💻 Autor

Desenvolvido por **Lucas Dias Xavier**

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para utilizá-lo como referência ou ponto de partida para seus próprios projetos.

---

<p align="center">
  ☕ <em>A vida só começa depois do café!</em>
</p>
