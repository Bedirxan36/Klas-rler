# Innoapweb

![Innoapweb Logo](./assets/logo.png)

## Hakkında

Innoapweb, modern ve hızlı web uygulamaları oluşturmak için geliştirilmiş bir platformdur.  
Kullanıcı dostu arayüzü ve güçlü altyapısı ile projelerinizi kolayca yönetin.

## Özellikler

- Modern ve responsive tasarım
- Kolay yönetici paneli
- Topluluk ve destek sistemleri
- Esnek fiyatlandırma modelleri

## Kurulum

```bash
git clone https://github.com/kullaniciadi/innoapweb.git
cd innoapweb
npm install
npm run dev

---

## 2. GitHub Pages veya Demo Sayfası için Basit HTML + CSS

```html
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Innoapweb</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.3.2/dist/tailwind.min.css" rel="stylesheet" />
</head>
<body class="bg-gray-900 text-white font-sans">
  <nav class="flex items-center justify-between p-6 bg-gray-800 shadow-lg sticky top-0 z-50">
    <div class="text-2xl font-bold text-blue-500">innoapweb</div>
    <div class="hidden md:flex space-x-8">
      <a href="#features" class="hover:text-blue-400 transition">Özellikler</a>
      <a href="#pricing" class="hover:text-blue-400 transition">Fiyatlandırma</a>
      <a href="#panel" class="hover:text-blue-400 transition">Yönetici Paneli</a>
      <a href="#contact" class="hover:text-blue-400 transition">İletişim</a>
    </div>
    <button id="mobile-menu-button" class="md:hidden text-blue-400 focus:outline-none">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24"><path d="M4 6h16M4 12h16M4 18h16"/></svg>
    </button>
  </nav>

  <div id="mobile-menu" class="hidden bg-gray-800 p-4 space-y-4 md:hidden">
    <a href="#features" class="block text-white hover:text-blue-400">Özellikler</a>
    <a href="#pricing" class="block text-white hover:text-blue-400">Fiyatlandırma</a>
    <a href="#panel" class="block text-white hover:text-blue-400">Yönetici Paneli</a>
    <a href="#contact" class="block text-white hover:text-blue-400">İletişim</a>
  </div>

  <script>
    const btn = document.getElementById('mobile-menu-button');
    const menu = document.getElementById('mobile-menu');
    btn.addEventListener('click', () => {
      menu.classList.toggle('hidden');
    });
  </script>

  <header class="text-center py-16">
    <h1 class="text-5xl font-extrabold gradient-text">Innoapweb</h1>
    <p class="mt-4 max-w-xl mx-auto text-gray-300">Modern, hızlı ve güvenilir web uygulaması platformu.</p>
    <a href="#register" class="mt-6 inline-block bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3 rounded-lg transition">Başlayın</a>
  </header>

  <!-- Devam eden içerik: Özellikler, Fiyatlandırma, Panel vs... -->

  <style>
    .gradient-text {
      background: linear-gradient(to right, #3b82f6, #60a5fa);
      -webkit-background-clip: text;
      color: transparent;
    }
  </style>
</body>
</html>
