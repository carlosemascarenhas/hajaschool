# 📚 Editor Mestre Platform

**Plataforma educacional criativa com foco em edição, IA e conteúdo para criadores digitais. Inspirada no modelo da Unhide School, construída com tecnologias gratuitas e acessíveis.**

---

## 🚀 Visão Geral

O Editor Mestre Platform oferece:

- 🎬 Tutoriais e treinamentos gratuitos
- 📦 Packs de edição exclusivos
- ✨ Ferramentas de IA (texto, imagem, vídeo)
- 📨 Newsletter (gratuita e paga)
- 🧠 Sala de aula com enquetes, artigos, vídeos e materiais
- 💳 Checkout via Mercado Pago
- ✉️ Email marketing via MailerSend
- 🤖 Integração com OpenRouter AI e Supabase

---

## ⚙️ Tecnologias Utilizadas

- Laravel + Blade
- Supabase (Auth, DB, Storage)
- TailwindCSS + Alpine.js
- Mercado Pago API (checkout custom)
- MailerSend (envio de email gratuito)
- OpenRouter AI (modelos Mistral, Claude, etc.)
- Node.js + Baileys (automação WhatsApp)
- Notion (gestão de conteúdo e marketing)

---

## 📦 Instalação Local (Laravel)

```bash
git clone https://github.com/seu-usuario/editor-mestre-platform.git
cd editor-mestre-platform
cp .env.example .env
composer install
npm install && npm run dev
php artisan migrate
php artisan key:generate
php artisan serve
```

⚠️ Configure suas variáveis de ambiente com Supabase, Mercado Pago e MailerSend no `.env`.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

Todo conteúdo educacional (vídeos, textos, imagens e downloads) está licenciado sob [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

---

> Criado com ❤️ por Carlos Mascarenhas — @carlosmascarenhas
