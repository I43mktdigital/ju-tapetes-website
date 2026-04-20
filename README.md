# JÚ Tapetes - Website

Site de vitrine desenvolvido para JÚ Tapetes, marca de tapetes artesanais de Guabiruba/SC.

## 🎨 Características

- **Design minimalista e elegante** com tons terrosos (bege, marrom, dourado)
- **Totalmente responsivo** - funciona em mobile, tablet e desktop
- **15 produtos com fotos reais** organizados por categoria
- **Integração WhatsApp** - botão flutuante e pedido direto por produto
- **Lazy loading** nas imagens para carregamento rápido
- **Animações suaves** para melhor experiência do usuário

## 📁 Estrutura

```
ju-tapetes-website/
├── index.html          # Arquivo principal do site
├── img/                # Imagens organizadas por categoria
│   ├── cozinha/       # Jogos de cozinha
│   ├── sala/          # Tapetes de sala
│   ├── porta/         # Tapetes de porta
│   ├── passadeira/    # Passadeiras
│   └── tapetes/       # Tapetes 1,45x1,00m
├── images/            # Fotos originais do cliente (backup)
└── README.md
```

## 🚀 Como usar

1. **Abrir localmente**: Dê um duplo clique no `index.html`
2. **Hospedar online**: Faça upload dos arquivos para qualquer serviço de hospedagem
   - Recomendado: Netlify, Vercel, GitHub Pages

## 📱 Configurar WhatsApp

No arquivo `index.html`, procure por:

```javascript
const WHATSAPP_NUMBER = "5547999999999";
```

Substitua `5547999999999` pelo número real da JÚ Tapetes (com código do país 55 + DDD + número, sem espaços ou traços).

## 🖼️ Adicionar mais fotos

Para adicionar novos produtos:

1. Coloque a imagem na pasta `img/` da categoria correspondente
2. Adicione o produto no array `products` no `index.html`

Exemplo:
```javascript
{
    id: 16,
    name: "Novo Produto",
    category: "sala",
    categoryName: "Tapete de Sala",
    specs: "2,00 x 1,45 metros",
    price: "Consultar",
    image: "img/sala/nova-foto.jpg"
}
```

## 🎨 Cores da Marca

- Bege claro: #F5F0E8
- Bege escuro: #E8DDD0
- Marrom: #8B7355
- Marrom escuro: #5C4A3A
- Dourado: #C9A96E
- WhatsApp: #25D366

## 📞 Contato do Cliente

**JÚ Tapetes**
- Instagram: [@jutapetes](https://instagram.com/jutapetes)
- Local: Guabiruba/SC
- 🏷️ Feito com amor

---

Desenvolvido com ❤️ para JÚ Tapetes