# Retiro Espiritual 2025 - Landing Page

Landing page para o Retiro Espiritual da Igreja Redime.

## 🚀 Deploy na Vercel

### Opção 1: Deploy Simples (Recomendado)

1. Faça commit e push dos arquivos:
```bash
git add index.html public/ vercel.json
git commit -m "Deploy landing page"
git push
```

2. Na Vercel:
   - Importe o repositório `RetiroRedime`
   - Deixe as configurações padrão
   - Clique em "Deploy"

### Opção 2: Deploy via CLI

```bash
npm install -g vercel
vercel
```

## 📁 Estrutura

```
RetiroRedime/
├── index.html          # Landing page principal
├── public/             # Imagens e assets
├── vercel.json         # Configuração Vercel
└── retiroredime/       # Projeto Vue (não usado no deploy)
```

## ✨ Recursos

- ✅ Design responsivo com Tailwind CSS
- ✅ Checklist interativo
- ✅ Carrossel de imagens
- ✅ Mapa integrado do Google Maps
- ✅ Animações suaves

## 📝 Nota

O projeto Vue na pasta `retiroredime/` **não é necessário** para o deploy. 
O arquivo `index.html` na raiz é standalone e funciona perfeitamente sozinho!
