# Película iPhone 11 Pro Max - TikTok Shop

Página de produto premium do TikTok Shop para película de proteção de celular.

## ✨ Recursos

### 🎯 Funcionalidades
- ✅ Seleção de cores (Preto, Branco, Vermelho)
- ✅ Quantidade variável (1-99)
- ✅ Timer de oferta relâmpago (conta regressiva)
- ✅ Adicionar ao carrinho com confirmação
- ✅ Modal de resumo do pedido
- ✅ Integração TikTok Pixel (ID: D8ISH6BC77UAEKHUNIB0)
- ✅ Rastreamento de eventos (Page View, Add to Cart, Initiate Checkout, Purchase)
- ✅ Redirect para checkout (https://checkout.paradisepag.shop/VCCL1O8SCWVL)

### 🎨 Design
- Design idêntico ao TikTok Shop oficial
- Gradiente rosa/vermelho (TikTok brand colors)
- Badges de verificação e proteção
- Avaliações de clientes (5 estrelas)
- Responsivo para mobile (principal)
- Animações suaves e transições

### 💰 Preço
- **Preço final**: R$ 9,90
- **Preço original**: R$ 33,00
- **Desconto**: 70%

## 🚀 Deploy na Vercel

### Opção 1: Automatizado
1. Push do código para GitHub/GitLab
2. Conecte o repo na Vercel
3. Vercel detectará Vite e fará deploy automático

### Opção 2: Manual via CLI
```bash
npm install -g vercel
vercel
```

## 📝 Para Editar o Produto

Edite o `index.html`:

```html
<!-- Título do produto -->
<h1 class="product-title">Película Para iPhone 11 Transformação Pro Max</h1>

<!-- Preço -->
<span class="price-old">R$ 33,00</span>  <!-- preço original -->
<strong>R$ 9,90</strong>                  <!-- preço final -->

<!-- Imagem do produto -->
<img src="/br-11134207-7r98o-m36lz57rvlqz68.webp" alt="Película iPhone 11 Pro Max">

<!-- Cores -->
<div class="color-option selected" data-color="preto">Preto</div>
<div class="color-option" data-color="branco">Branco</div>
<div class="color-option" data-color="vermelho">Vermelho</div>

<!-- URL do checkout -->
window.location.href = 'https://checkout.paradisepag.shop/VCCL1O8SCWVL';
```

## 📊 TikTok Pixel Integration

Pixel ID: `D8ISH6BC77UAEKHUNIB0`

Eventos rastreados:
- `Page` - Visualização de página
- `AddToCart` - Adição ao carrinho
- `InitiateCheckout` - Início do checkout
- `Purchase` - Compra realizada

## 📁 Estrutura do Projeto

```
project/
├── index.html              # Página principal
├── public/
│   ├── br-11134207...      # Imagem do produto
│   └── js/
│       └── pixel-tiktok.js # Pixel do TikTok
├── package.json
├── vite.config.js
├── vercel.json
└── dist/                   # Build para produção
```

## 🛠️ Desenvolvimento Local

```bash
npm install
npm run dev        # Servidor local (http://localhost:5173)
npm run build      # Build de produção
npm run preview    # Visualizar build
```

## 📞 Suporte ao Checkout

Checkout URL: `https://checkout.paradisepag.shop/VCCL1O8SCWVL`

Integração automática com:
- Passa quantidade do produto
- Registra cor selecionada
- Envia UTMs do TikTok Pixel
- Rastreia valor total

---

**Versão**: 1.0.0  
**Última atualização**: 2026-06-08
