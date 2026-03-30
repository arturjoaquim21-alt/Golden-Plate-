# 🍽️ Golden Plate — Restaurant Website Template

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)

> **⚠️ AVISO / DISCLAIMER**
> O **Golden Plate** é um restaurante **fictício**. Não existe na realidade. Todo o conteúdo — nome, morada, número de telefone, história, equipa, pratos e preços — foi criado exclusivamente para fins de demonstração. Este projecto é um **template open-source** para websites de restaurantes.

---

## 📸 Pré-visualização

Um website elegante e sofisticado para restaurante, com tema escuro e dourado, inspirado na gastronomia moçambicana.

**Secções incluídas:**
- Hero com animações de entrada
- História / Sobre Nós
- Menu com 3 categorias e 21 pratos
- Galeria de fotografias
- Depoimentos de clientes
- Formulário de contacto e reservas
- Rodapé completo

---

## 🚀 Como usar como Template

Este projecto foi pensado para ser reutilizado. Siga os passos:

### 1. Faça Fork ou Clone do repositório

```bash
git clone https://github.com/SEU-USERNAME/golden-plate.git
cd golden-plate
```

### 2. Abra o ficheiro principal

```
golden_plate.html
```

Pode abrir directamente no browser — não requer servidor nem dependências.

### 3. Personalize o conteúdo

Substitua os seguintes elementos pelo seu negócio real:

| O que alterar | Onde encontrar no código |
|---|---|
| Nome do restaurante | `Golden Plate` → o seu nome |
| Cidade / País | `Maputo, Moçambique` |
| Número de telefone | `+258 800 000 000` |
| E-mail | `reservas@goldenplate.co.mz` |
| Morada | `Avenida Julius Nyerere, 1234` |
| Pratos e preços | Secção `#menu` |
| História | Secção `#story` |
| Fotos da galeria | URLs `src=""` nas `<img>` da galeria |
| Cores principais | Variáveis CSS no `:root {}` |

### 4. Personalize as cores

No topo do ficheiro CSS, dentro de `:root`, altere as variáveis:

```css
:root {
  --gold: #c9a84c;       /* Cor principal dourada */
  --gold-light: #e8c97a; /* Dourado claro (hover) */
  --noir: #080704;       /* Fundo principal */
  --cream: #f5ede0;      /* Texto principal */
}
```

---

## 🛠️ Tecnologias

- **HTML5** puro — sem frameworks
- **CSS3** — variáveis, grid, animações, scroll reveal
- **JavaScript** vanilla — tabs, scroll effects, form feedback
- **Google Fonts** — Cormorant Garamond + Tenor Sans
- **Unsplash** — fotografias de demonstração (livres para uso)

---

## 📁 Estrutura do Projecto

```
golden-plate/
│
├── golden_plate.html    # Ficheiro principal (tudo num único ficheiro)
├── README.md            # Este ficheiro
└── LICENSE              # Licença MIT
```

---

## ⚡ Funcionalidades

- ✅ Design responsivo (mobile, tablet, desktop)
- ✅ Navegação fixa com efeito scroll
- ✅ Animações de entrada (scroll reveal)
- ✅ Menu com tabs interactivos
- ✅ Galeria com hover effects
- ✅ Formulário de reserva com feedback visual
- ✅ Zero dependências externas (excepto Google Fonts)
- ✅ Código limpo e bem comentado
- ✅ Fácil de personalizar

---

## 📄 Licença

Distribuído sob a licença **MIT**. Consulte o ficheiro [LICENSE](./LICENSE) para mais detalhes.

Resumindo: **pode usar, copiar, modificar e distribuir livremente**, inclusive para projectos comerciais, desde que mantenha o aviso de copyright.

---

## 🙏 Créditos

- Fotografias: [Unsplash](https://unsplash.com) (licença livre)
- Tipografia: [Google Fonts](https://fonts.google.com)
- Desenvolvido com [Claude](https://claude.ai) by Anthropic

---

*Este é um projecto de demonstração. Qualquer semelhança com estabelecimentos reais é mera coincidência.*
