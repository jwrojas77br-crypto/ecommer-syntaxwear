# 👟 SyntaxWear - E-commerce de Tênis e Sneakers

## 📋 Descrição do Projeto

SyntaxWear é uma loja online moderna e elegante especializada na venda de tênis e sneakers. O site oferece uma experiência de usuário fluida e atraente, com um design responsivo que se adapta perfeitamente a dispositivos móveis, tablets e desktop.

O projeto apresenta uma landing page completa com categorias de produtos, galeria de imagens, banner hero principal e um sistema de navegação intuitivo.

## ✨ Características Principais

- **Design Responsivo**: Adaptado para celulares, tablets e desktop
- **Navegação Intuitiva**: Header fixo com menu hambúrguer em dispositivos móveis
- **Hero Banner**: Seção destacada com chamadas para ação
- **Categorias de Produtos**: Casual, Esporte, Moderno e Futurista
- **Grid de Produtos**: Design em mosaico com imagens destacadas
- **Footer Completo**: Newsletter, redes sociais e navegação por categorias
- **Otimização SEO**: Meta tags e estrutura semântica HTML5

## 🎨 Paleta de Cores

- **Principal**: `#6329A2` (Roxo/Violeta)
- **Fundo**: `#FFFFFF` (Branco)
- **Texto**: `#333333` (Cinza Escuro)
- **Footer**: `#333333` (Cinza Escuro)
- **Secundário**: `#EDEDED` (Cinza Claro)
- **Overlays**: `rgba(0, 0, 0, 0.25)`

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilos modernos com Flexbox e Grid Layout
- **Google Fonts**: Ubuntu (fonte principal)
- **SVG Icons**: Ícones vetoriais otimizados
- **Responsive Design**: Media queries para adaptabilidade

## 📁 Estrutura do Projeto

```
ecommer-syntaxwear/
├── index.html                      # Página principal
├── README.md                       # Documentación del proyecto
├── css/
│   ├── reset.css                   # Reset de estilos del navegador
│   ├── variables.css               # Variables CSS y fuentes
│   ├── base.css                    # Estilos base y botones
│   └── components/
│       ├── header.css              # Estilos del header (72px altura)
│       ├── hero.css                # Banner hero principal
│       ├── product-category.css    # Tarjetas de categorías
│       ├── product-grid.css        # Grid de productos
│       └── footer.css              # Footer con newsletter
└── images/
    ├── banners/
    │   ├── hero.jpg                # Banner desktop
    │   └── hero-mobile.jpg         # Banner móvil
    ├── favicons/                   # Iconos del sitio
    ├── icons/
    │   ├── bag.svg                 # Carrito de compras
    │   ├── user.svg                # Cuenta de usuario
    │   ├── help.svg                # Ayuda
    │   ├── hamburguer.svg          # Menú móvil
    │   ├── instagram.svg           # Redes sociales
    │   ├── whatsapp.svg
    │   ├── tiktok.svg
    │   └── facebook.svg
    ├── logo/
    │   └── logo.svg                # Logo SyntaxWear
    └── products/
        ├── casual.jpg              # Categoría Casual
        ├── esporte.jpg             # Categoría Esporte
        ├── moderno.jpg             # Categoría Moderno
        ├── futurista.jpg           # Categoría Futurista
        ├── card_imagem.jpg         # Producto destacado
        ├── modelo-femenino.jpg     # Modelo femenino
        ├── roxo-verde-grid.jpg     # Sneaker morado/verde
        ├── futurista-grid.jpg      # Sneaker futurista
        ├── preto.jpg.jpg           # Sneaker negro
        └── moderno-grid.jpg        # Sneaker moderno
```

## 🚀 Como Executar o Projeto

### Opção 1: Abrir Diretamente

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` no seu navegador preferido

### Opção 2: Com Live Server (Recomendado)

1. Instale a extensão **Live Server** no VS Code
2. Abra a pasta do projeto no VS Code
3. Clique com o botão direito em `index.html` e selecione "Open with Live Server"
4. O site abrirá automaticamente em `http://127.0.0.1:5500`

### Opção 3: Com Python Server

```bash
# Python 3
python -m http.server 8000

# Depois abra http://localhost:8000 no seu navegador
```

## 📱 Breakpoints Responsivos

- **Desktop**: > 1280px
- **Tablet**: 768px - 1280px
- **Mobile**: < 768px
- **Small Mobile**: < 500px

## 🧩 Componentes do Site

### Header (72px de altura)
- Logo SyntaxWear
- Navegação principal: Masculino, Feminino, Outlet
- Links rápidos: Nossas lojas, Sobre
- Ícones: Conta, Ajuda, Carrinho
- Menu hambúrguer em dispositivos móveis

### Hero Section
- Banner principal com imagem de fundo
- Título destacado: "Krypton One"
- Subtítulo promocional
- Botões CTA: "Ver modelos" e "Comprar"
- Versão diferente para dispositivos móveis

### Seção de Categorias
- 4 cards grandes com imagens:
  - Casual
  - Esporte
  - Moderno
  - Futurista
- Overlay escuro com efeito hover
- Design responsivo com wrap

### Grid de Produtos
- Layout tipo mosaico com CSS Grid
- 6 áreas de produtos:
  - Produto destacado (2x2)
  - Modelo feminino (1x2)
  - 4 sneakers adicionais
- Design adaptado para dispositivos móveis (2 colunas)

### Footer
- Newsletter com campo de email
- Redes sociais (Instagram, WhatsApp, TikTok, Facebook)
- Navegação por categorias
- Copyright

## 🎯 Funcionalidades Implementadas

✅ Design responsivo completo
✅ Header fixo com navegação
✅ Banner hero atrativo
✅ Categorias de produtos
✅ Grid de produtos com CSS Grid
✅ Footer com newsletter e redes sociais
✅ Efeitos hover em botões e imagens
✅ Menu móvel com checkbox toggle
✅ Otimização de imagens
✅ Estrutura semântica HTML5

## 🔮 Melhorias Futuras

- [ ] Implementar carrinho de compras funcional
- [ ] Adicionar sistema de busca
- [ ] Integrar gateway de pagamentos
- [ ] Criar páginas de produto individual
- [ ] Adicionar filtros de produtos
- [ ] Implementar sistema de lista de desejos
- [ ] Adicionar avaliações e notas
- [ ] Integração com API de estoque
- [ ] Sistema de autenticação de usuários
- [ ] Painel de administração

## 👥 Autor

**jwrojas77br-crypto**

## 📄 Licença

Copyright. All Rights Reserved

---

**Nota**: Este é um projeto educacional/portfólio para demonstração de habilidades em desenvolvimento web frontend.