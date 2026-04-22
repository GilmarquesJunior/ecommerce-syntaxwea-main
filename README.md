# 🎧 SyntaxWear - E-commerce de Tênis e Sneakers

[![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white)](https://www.w3.org/html/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com/)
[![Responsivo](https://img.shields.io/badge/Responsivo-Mobile%20First-success?style=for-the-badge)](https://www.w3.org/Mobile/)

---

## 📋 Descrição

**SyntaxWear** é um e-commerce moderno e responsivo especializado na venda de tênis e sneakers de alta qualidade. O site apresenta um design contemporâneo com interface intuitiva, categorias bem organizadas e uma experiência de compra otimizada para dispositivos móveis e desktops.

> 💡 Projeto desenvolvido durante o curso **Dev em Dobro 2.0** - uma iniciativa educacional completa de desenvolvimento web.

---

## 🎯 Características Principais

✅ **Design Responsivo** - Funciona perfeitamente em todos os tamanhos de tela (mobile, tablet, desktop)
✅ **Navegação Intuitiva** - Menu mobile com hamburger e navegação desktop otimizada
✅ **Seção Hero Impactante** - Banner principal com chamada para ação clara
✅ **Categorias de Produtos** - 4 categorias principais (Casual, Esporte, Moderno, Futurista)
✅ **Grid de Produtos** - Exibição moderna de produtos em layout de cards
✅ **Footer Completo** - Newsletter, redes sociais e links de navegação
✅ **SEO Otimizado** - Meta tags e estrutura semântica HTML5
✅ **Acessibilidade** - Atributos ARIA e labels descritivos
✅ **Componentes Modulares** - CSS organizado e reutilizável
✅ **Tipografia Profissional** - Fonte Ubuntu do Google Fonts

---

## 📁 Estrutura de Pastas

```
ecommerce-syntaxwea/
│
├── 📄 index.html                    # Página principal do site
├── 📄 README.md                     # Este arquivo
│
├── 📂 css/                          # Arquivos de estilos
│   ├── reset.css                    # Reset de estilos padrão do navegador
│   ├── variables.css                # Variáveis CSS globais
│   ├── base.css                     # Estilos base e utilitários
│   │
│   └── 📂 components/               # Componentes CSS
│       ├── header.css               # Estilos do cabeçalho
│       ├── hero.css                 # Estilos da seção hero
│       ├── product-category.css    # Estilos das categorias
│       ├── product-grid.css         # Estilos do grid de produtos
│       ├── products-category.css   # Estilos de categoria
│       ├── products-grid.css        # Estilos do grid geral
│       └── footer.css               # Estilos do rodapé
│
├── 📂 images/                       # Recursos visuais
│   ├── 📂 banners/                  # Imagens de banners promocionais
│   ├── 📂 favicons/                 # Favicon do site
│   ├── 📂 icons/                    # Ícones SVG (menu, user, bag, etc)
│   ├── 📂 logo/                     # Logo da marca
│   └── 📂 products/                 # Imagens dos produtos
│
├── 📂 js/                           # Scripts JavaScript (preparado para expansão)
│
└── 📂 .git/                         # Controle de versão Git

```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição | Versão |
|------------|-----------|--------|
| **HTML5** | Estrutura semântica do site | - |
| **CSS3** | Estilos responsivos e componentes | - |
| **JavaScript** | Interatividade (pronto para implementação) | - |
| **Google Fonts** | Tipografia (fonte Ubuntu) | - |
| **Git** | Controle de versão | - |

---

## 🎨 Componentes CSS

### **Header** (`components/header.css`)
- Navegação principal com menu mobile (checkbox hack)
- Logo e branding
- Ícones de ação (usuário, ajuda, carrinho)
- Totalmente responsiva

### **Hero Section** (`components/hero.css`)
- Banner principal com imagem de fundo
- Overlay e conteúdo centralizado
- Botões de chamada para ação
- Animações suaves

### **Product Grid** (`components/product-grid.css`)
- Layout em grid responsivo
- Cards de produto com hover effects
- Highlight especial para destaque
- Suporte a múltiplos tamanhos de tela

### **Categorias** (`components/product-category.css`)
- 4 categorias: Casual, Esporte, Moderno, Futurista
- Cards com imagens e overlay
- Transições suaves e interatividade

### **Footer** (`components/footer.css`)
- Newsletter subscription form
- Links de redes sociais
- Navegação secundária
- Copyright e informações legais

---

## 🚀 Como Usar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime Text, etc.) - opcional para edição

### Instalação

1. **Clone o repositório** (se estiver usando Git):
   ```bash
   git clone <seu-repositório>
   cd ecommerce-syntaxwea
   ```

2. **Abra o arquivo HTML**:
   - Simplesmente abra o arquivo `index.html` no seu navegador
   - Ou use um servidor local (recomendado):
   
   ```bash
   # Com Python 3
   python -m http.server 8000
   
   # Com Python 2
   python -m SimpleHTTPServer 8000
   
   # Com Node.js (http-server)
   npx http-server
   ```

3. **Acesse no navegador**:
   ```
   http://localhost:8000
   ```

---

## 📱 Responsividade

O site é totalmente responsivo com breakpoints otimizados:

- 📱 **Mobile**: até 480px
- 📱 **Tablet**: 481px a 1024px
- 🖥️ **Desktop**: 1025px e acima

---

## 🔧 Customização

### Mudar Cores
Edite as variáveis em `css/variables.css`:
```css
:root {
    --cor-primaria: #seu-codigo-cor;
    --cor-secundaria: #seu-codigo-cor;
}
```

### Mudar Tipografia
Modifique a fonte em `css/variables.css`:
```css
--fonte-principal: 'Sua Fonte', sans-serif;
```

### Adicionar Novos Produtos
Edite a seção `grid-section` no `index.html` e adicione novos cards.

---

## 📝 Estrutura HTML

### Seções Principais:
1. **Header** - Navegação principal e logo
2. **Hero Section** - Banner de destaque com CTA
3. **Categories Section** - Grid de 4 categorias
4. **Product Grid** - Grid de produtos em destaque
5. **Footer** - Newsletter, redes sociais e links

### Elementos Interativos:
- ✅ Menu mobile (checkbox toggle)
- ✅ Botões de ação (outline e filled)
- ✅ Formulário de newsletter
- ✅ Links de redes sociais

---

## ♿ Acessibilidade

O projeto segue boas práticas de acessibilidade:
- ✅ Labels descritivos em formulários
- ✅ Atributos `aria-label` em botões de ícone
- ✅ Estrutura semântica HTML5 (`<header>`, `<main>`, `<footer>`, `<nav>`)
- ✅ Alt text em todas as imagens
- ✅ Contraste de cores adequado
- ✅ Menu responsivo acessível

---

## 🔍 SEO

O site contém:
- ✅ Meta description clara
- ✅ Título descritivo
- ✅ Estrutura H1 > H2 > H3
- ✅ Alt text em imagens
- ✅ URLs amigáveis
- ✅ Viewport meta tag para mobile

---

## 🎓 Próximos Passos

Possíveis melhorias e implementações:

- [ ] Adicionar JavaScript para funcionalidades interativas
- [ ] Implementar carrinho de compras
- [ ] Adicionar filtros de produtos
- [ ] Integração com API de produtos
- [ ] Sistema de autenticação de usuário
- [ ] Animações com AOS ou Animate.css
- [ ] Dark mode toggle
- [ ] Otimização de imagens (webp, lazy loading)

---

## 📚 Recursos Úteis

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [Web Accessibility](https://www.w3.org/WAI/)
- [Google Fonts](https://fonts.google.com/)

---

## 👨‍💼 Sobre o Projeto

Este é um projeto educacional desenvolvido durante o curso **Dev em Dobro 2.0**, que visa ensinar desenvolvimento web moderno com foco em:

- Estrutura HTML semântica
- CSS responsivo e componentizado
- Boas práticas de desenvolvimento
- Acessibilidade web
- SEO básico

---

## 📄 Licença

Este projeto é fornecido como material educacional. Sinta-se livre para usar, modificar e distribuir conforme necessário para fins de aprendizado.

---

## 📞 Contato e Suporte

Para dúvidas, sugestões ou reportar problemas:

- 📧 Email: [seu-email@exemplo.com]
- 💬 Redes Sociais: Conecte-se através dos links no footer
- 🐛 Issues: Reporte problemas via GitHub Issues (se aplicável)

---

## 🙏 Agradecimentos

Agradecimentos especiais ao **curso Dev em Dobro 2.0** pela excelente estrutura de aprendizado e ao **time de instrutores** por orientar este projeto.

---

**Desenvolvido com ❤️ para a comunidade de desenvolvimento web**

*Última atualização: Abril de 2026*