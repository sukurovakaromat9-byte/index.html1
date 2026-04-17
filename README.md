<!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Гастроном - Доставка еды</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-primary-fixed": "#2f1500",
                        "outline-variant": "#ddc1ae",
                        "surface": "#f9f9f9",
                        "on-error-container": "#93000a",
                        "on-tertiary-fixed-variant": "#005312",
                        "on-tertiary-container": "#00490e",
                        "outline": "#8a7362",
                        "secondary-container": "#91f78e",
                        "on-secondary": "#ffffff",
                        "surface-container-high": "#e8e8e8",
                        "on-primary-fixed-variant": "#6f3900",
                        "on-surface": "#1a1c1c",
                        "on-secondary-fixed-variant": "#005313",
                        "primary-fixed": "#ffdcc4",
                        "secondary": "#006e1c",
                        "on-tertiary": "#ffffff",
                        "tertiary-fixed-dim": "#88d982",
                        "error-container": "#ffdad6",
                        "surface-tint": "#914c00",
                        "on-primary": "#ffffff",
                        "inverse-on-surface": "#f1f1f1",
                        "secondary-fixed": "#94f990",
                        "background": "#f9f9f9",
                        "tertiary-container": "#6bbb68",
                        "surface-container-lowest": "#ffffff",
                        "inverse-primary": "#ffb77f",
                        "surface-bright": "#f9f9f9",
                        "surface-dim": "#dadada",
                        "secondary-fixed-dim": "#78dc77",
                        "tertiary": "#1b6d24",
                        "error": "#ba1a1a",
                        "primary-container": "#ff8a00",
                        "on-background": "#1a1c1c",
                        "on-error": "#ffffff",
                        "on-tertiary-fixed": "#002204",
                        "on-secondary-fixed": "#002204",
                        "on-surface-variant": "#564334",
                        "inverse-surface": "#2f3131",
                        "primary-fixed-dim": "#ffb77f",
                        "primary": "#914c00",
                        "tertiary-fixed": "#a3f69c",
                        "on-secondary-container": "#00731e",
                        "surface-container-highest": "#e2e2e2",
                        "surface-container": "#eeeeee",
                        "surface-container-low": "#f3f3f3",
                        "on-primary-container": "#613100",
                        "surface-variant": "#e2e2e2"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "2xl": "1rem",
                        "3xl": "1.5rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Inter"],
                        "label": ["Inter"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Inter', sans-serif; }
        h1, h2, h3 { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface text-on-surface">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-white/80 dark:bg-stone-900/80 backdrop-blur-xl shadow-[0px_12px_32px_rgba(86,67,52,0.08)]">
<div class="flex items-center justify-between px-6 py-4 max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 hover:bg-stone-100 dark:hover:bg-stone-800 transition-colors active:scale-95 duration-200 rounded-full">
<span class="material-symbols-outlined text-orange-600">menu</span>
</button>
<span class="text-2xl font-bold tracking-tight text-orange-600">Гастроном</span>
</div>
<div class="hidden md:flex items-center gap-8">
<nav class="flex gap-6">
<a class="text-orange-600 font-semibold" href="#">Главная</a>
<a class="text-stone-500 dark:text-stone-400 hover:text-orange-500 transition-all" href="#">Меню</a>
<a class="text-stone-500 dark:text-stone-400 hover:text-orange-500 transition-all" href="#">Корзина</a>
</nav>
</div>
<div class="flex items-center gap-3">
<button class="p-2 hover:bg-stone-100 dark:hover:bg-stone-800 transition-colors rounded-full">
<span class="material-symbols-outlined text-stone-600">search</span>
</button>
<div class="w-10 h-10 rounded-full bg-stone-200 overflow-hidden">
<img class="w-full h-full object-cover" data-alt="profile avatar of a smiling man in a clean studio setting with soft lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC4BPS0YkMQ7Q5ovu47JW0ByjAVUH71ivdcLhmL0iwL0ZpiHdA0oSJqMlVUcqkS98t2OFRgphNTvB16NQy_e0-SqXmx3ZpQc2lsZBQB9SgF8shTjZykvxlTIeFDu2KOFt9Sgs1nAHdPQeEXusotOp3izkA0bg1bBCoOO6oH6gW1xtg1Ru0Q9hGE0Uok-HG2nOW_ny72YpsuYNR_ZRplNiSsCCsavJcdS2iTxdVlZot1HD18ifouBu-7-aHUcJjy5zWXx3r4CHmqHCI"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-4 max-w-7xl mx-auto">
<!-- Hero Promo Banner -->
<section class="relative overflow-hidden rounded-3xl mb-12 bg-on-primary-fixed group">
<div class="flex flex-col md:flex-row items-center">
<div class="p-8 md:p-12 md:w-1/2 z-10">
<span class="inline-block px-4 py-1.5 rounded-full bg-secondary text-on-secondary font-bold text-xs mb-4 uppercase tracking-wider">Первый заказ</span>
<h1 class="text-4xl md:text-6xl font-extrabold text-white mb-4 leading-tight">Пицца в подарок!</h1>
<p class="text-stone-300 text-lg mb-8 max-w-md">Сделайте свой первый заказ через приложение и получите ароматную «Маргариту» в подарок.</p>
<button class="bg-gradient-to-r from-primary to-primary-container text-white px-8 py-4 rounded-3xl font-bold text-lg hover:shadow-xl hover:shadow-orange-500/20 active:scale-95 transition-all duration-200">
                        <a href="AlmazZz.html">Заказать сейчас</a>
                    </button>
</div>
<div class="relative md:w-1/2 h-64 md:h-[400px] w-full">
<img class="absolute inset-0 w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-700" data-alt="large hot pepperoni pizza with melting cheese and steam on a dark rustic wooden background with editorial lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAmZEKLbUNKDpvNhdelrtX2HREC-8D0RckHA6XUokI-OfFNXrrYNGbY9DonQWE3Q7vswTogwKjw2j2fNoZ1k3kf6o4St-OEBMqHjDULxoJl6XiRzb8ptkfi3j2GswN_9XlVvcdEmp-IqF1wLIGMl7d5ibNmjnIbxc4S1Xm44EFRd70AUtdPK3_xaV0nBCm9g_NkOHp5lMKfn8lezfKweuOMy6AtMv7v1PkKocFYb1n12XCHboW_dOH4ttzGVlGCcv4XroshRjOzErk"/>
<div class="absolute inset-0 bg-gradient-to-r from-on-primary-fixed via-transparent to-transparent"></div>
</div>
</div>
</section>
<!-- Quick Categories -->
<section class="mb-12">
<div class="flex gap-4 overflow-x-auto pb-4 scrollbar-hide">
<button class="flex-shrink-0 flex items-center gap-3 bg-white px-6 py-4 rounded-3xl shadow-[0px_4px_16px_rgba(0,0,0,0.04)] hover:shadow-lg transition-shadow">
<span class="text-2xl">🍕</span>
<span class="font-bold">Пицца</span>
</button>
<button class="flex-shrink-0 flex items-center gap-3 bg-white px-6 py-4 rounded-3xl shadow-[0px_4px_16px_rgba(0,0,0,0.04)] hover:shadow-lg transition-shadow border-2 border-primary-container">
<span class="text-2xl">🍣</span>
<span class="font-bold text-primary-container">Суши</span>
</button>
<button class="flex-shrink-0 flex items-center gap-3 bg-white px-6 py-4 rounded-3xl shadow-[0px_4px_16px_rgba(0,0,0,0.04)] hover:shadow-lg transition-shadow">
<span class="text-2xl">🍔</span>
<span class="font-bold">Бургеры</span>
</button>
<button class="flex-shrink-0 flex items-center gap-3 bg-white px-6 py-4 rounded-3xl shadow-[0px_4px_16px_rgba(0,0,0,0.04)] hover:shadow-lg transition-shadow">
<span class="text-2xl">🥗</span>
<span class="font-bold">Салаты</span>
</button>
<button class="flex-shrink-0 flex items-center gap-3 bg-white px-6 py-4 rounded-3xl shadow-[0px_4px_16px_rgba(0,0,0,0.04)] hover:shadow-lg transition-shadow">
<span class="text-2xl">🍰</span>
<span class="font-bold">Десерты</span>
</button>
</div>
</section>
<!-- Popular Section -->
<section class="mb-16">
<div class="flex items-center justify-between mb-8">
<h2 class="text-3xl font-extrabold tracking-tight">Популярное сейчас</h2>
<button class="text-primary font-bold hover:underline"><a href="AlmazZz.html">смотреть все</a></button>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
<!-- Product Card 1 -->
<div class="bg-surface-container-lowest rounded-3xl overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group">
<div class="relative h-56 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="premium sushi set roll with salmon and cream cheese on black stone plate with soft overhead light" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBROj3sB5gFjtlLdvw80E49zf7r8Y8EzNMd-OSWI1Ix3jkgMr6FIyow7RHGtIgiheyh3Ahb3Ue3FTvfV6CIrDkGYDtBrbTBbl-0-7o0qpLDsntuvbI6XB8Vpd3nuikzcUMf8UHD1xhh0iuOzI8nn9WZ64MAZOnLmPCKQWEKXN2YW05m6mTOrp6d2Yr652rIUJ9-_1HT-qlwelmac1QDSHM-fXkgtGMi98IfVv9ZcuDMQ8zJR_dDUvCbDO54LugmCRrwPmf2P1rb-00"/>
<div class="absolute top-4 right-4 bg-white/90 backdrop-blur px-2 py-1 rounded-xl flex items-center gap-1 shadow-sm">
<span class="material-symbols-outlined text-yellow-400 text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="text-xs font-bold">4.9</span>
</div>
</div>
<div class="p-6 flex flex-col flex-grow">
<h3 class="text-lg font-bold mb-2">Филадельфия Люкс</h3>
<p class="text-stone-500 text-sm mb-6 flex-grow">Свежий лосось, сливочный сыр, огурец и авокадо.</p>
<div class="flex items-center justify-between mt-auto">
<span class="text-xl font-extrabold text-on-surface">890 ₽</span>
<button class="bg-primary-container text-white p-3 rounded-2xl hover:scale-105 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Product Card 2 -->
<div class="bg-surface-container-lowest rounded-3xl overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group">
<div class="relative h-56 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="gourmet double cheeseburger with melting cheddar and fresh lettuce on a toasted bun in professional studio lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCGIX2LUwyVfhblw2Wa7On1wDv5LDjsy9fpruiU6q3_AMQbMFekCIhyqJKOfd7uYieLHC0mRWB4PlJQk-hx03eaz_zRmiYw7HltWkiDhB_hKlEkajbNAC5xz9v9U9cQgwWbBw6zEjOuaw4rOCaU1SPfDs7OflqjySAocQGUH4uAIg15YDmrBH64blgoNwK7cz4t1D3W4ZpMCz8QRvcLUQgY6KpZPIhRtjbtUGJemNlNhcYE84wDm1iqMRHDvGH8N7Ka6MAs25g_4Es"/>
<div class="absolute top-4 left-4 bg-secondary text-white px-3 py-1 rounded-xl text-[10px] font-bold uppercase tracking-widest">Fresh</div>
</div>
<div class="p-6 flex flex-col flex-grow">
<h3 class="text-lg font-bold mb-2">Трюфельный Бургер</h3>
<p class="text-stone-500 text-sm mb-6 flex-grow">Мраморная говядина, трюфельный соус, карамелизованный лук.</p>
<div class="flex items-center justify-between mt-auto">
<span class="text-xl font-extrabold text-on-surface">650 ₽</span>
<button class="bg-primary-container text-white p-3 rounded-2xl hover:scale-105 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Product Card 3 -->
<div class="bg-surface-container-lowest rounded-3xl overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group">
<div class="relative h-56 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="classic italian pizza marguerita with fresh basil leaves and buffalo mozzarella on artisanal crust" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBE1pY1_p2jkcQRZvJ0OCLSz8kX1fpWAuONJChngqqwIIBH_U8HDAK5BfoZvQXCb18eXQ7-PhXIFPac4mxjq5IThq07VqWgK_0P8VUsqs2BiLcZQ6KliNbu9Wu6_PVRyXg-rYyRJDqRIFD3hgYOiXnstlgHQrDXWh_-YQmiKW7C81N8cHDmAYdubaC7GKZbQWbgSlIKrauIKTmjpjsG6gQxYBkaz-bFQvwIsgncr4goCQ3Bn7sPRSz8SF1SkRwT6_zzI-lZ_piWDBg"/>
</div>
<div class="p-6 flex flex-col flex-grow">
<h3 class="text-lg font-bold mb-2">Пицца Маргарита</h3>
<p class="text-stone-500 text-sm mb-6 flex-grow">Классика с томатным соусом, моцареллой и базиликом.</p>
<div class="flex items-center justify-between mt-auto">
<span class="text-xl font-extrabold text-on-surface">540 ₽</span>
<button class="bg-primary-container text-white p-3 rounded-2xl hover:scale-105 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Product Card 4 -->
<div class="bg-surface-container-lowest rounded-3xl overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group">
<div class="relative h-56 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="healthy poke bowl with avocado, edamame, and fresh vegetables in a white ceramic bowl on a bright table" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA_-Sz-H7s1MdYZQAU5pb1Hs-nckE4_4f5J4AJDhQkp8GWXPler9gsOnkAZU-dh1yMhZ9CaLSlEtBESbfT3Mes4tDKPooUYocxPHvU7XI9CSAPSp46csgo8UQn2HMKDdtjmXr-uQZfEHqWueaRMKU1g75ic-nAsuwqgq6Tjh1KjCd4MM6AgU-Gy74n6MHBBtzJmVCIgm_aI1_o4F8YwvtYJFvsFPpmVBvqnEokvkbFcYEENPn4pGjE3g1_RIQvX5cnqadr70b_I5c0"/>
</div>
<div class="p-6 flex flex-col flex-grow">
<h3 class="text-lg font-bold mb-2">Боул с Тунцом</h3>
<p class="text-stone-500 text-sm mb-6 flex-grow">Киноа, свежий тунец, чука, бобы эдамаме и соус никкей.</p>
<div class="flex items-center justify-between mt-auto">
<span class="text-xl font-extrabold text-on-surface">720 ₽</span>
<button class="bg-primary-container text-white p-3 rounded-2xl hover:scale-105 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
</div>
</section>
<!-- Features Bento Grid -->
<section class="mb-20">
<h2 class="text-3xl font-extrabold tracking-tight mb-8">Почему выбирают нас</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
<div class="md:col-span-2 bg-secondary-container rounded-3xl p-8 flex flex-col justify-between">
<div>
<h3 class="text-2xl font-bold text-on-secondary-container mb-2">Свежесть – наш приоритет</h3>
<p class="text-on-secondary-container/80 max-w-sm">Мы работаем только с локальными фермерами и проверенными поставщиками.</p>
</div>
<div class="flex gap-4 mt-8">
<span class="bg-white/40 p-3 rounded-2xl backdrop-blur">
<span class="material-symbols-outlined text-secondary">eco</span>
</span>
<span class="bg-white/40 p-3 rounded-2xl backdrop-blur">
<span class="material-symbols-outlined text-secondary">verified</span>
</span>
</div>
</div>
<div class="bg-white rounded-3xl p-8 shadow-sm flex flex-col items-center text-center">
<div class="w-16 h-16 bg-orange-50 rounded-full flex items-center justify-center mb-4">
<span class="material-symbols-outlined text-orange-600 text-3xl">timer</span>
</div>
<h3 class="font-bold mb-2">Доставка за 30 мин</h3>
<p class="text-stone-500 text-sm">Или вы получите купон на бесплатную пиццу.</p>
</div>
<div class="bg-white rounded-3xl p-8 shadow-sm flex flex-col items-center text-center">
<div class="w-16 h-16 bg-green-50 rounded-full flex items-center justify-center mb-4">
<span class="material-symbols-outlined text-green-600 text-3xl">restaurant</span>
</div>
<h3 class="font-bold mb-2">Шеф-повара</h3>
<p class="text-stone-500 text-sm">Каждое блюдо готовится с любовью профессионалами.</p>
</div>
<div class="md:col-span-2 bg-on-surface rounded-3xl p-8 flex items-center justify-between overflow-hidden">
<div class="text-white">
<h3 class="text-2xl font-bold mb-2">Скачайте приложение</h3>
<p class="text-stone-400 mb-6">Бонусы и история заказов всегда под рукой.</p>
<div class="flex gap-4">
<div class="w-32 h-10 bg-stone-800 rounded-lg flex items-center justify-center border border-stone-700">App Store</div>
<div class="w-32 h-10 bg-stone-800 rounded-lg flex items-center justify-center border border-stone-700">Google Play</div>
</div>
</div>
<div class="hidden md:block transform rotate-12 -mr-10">
<div class="w-40 h-64 bg-stone-800 rounded-[32px] border-4 border-stone-700"></div>
</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full flex justify-around items-center px-4 pb-6 pt-3 bg-white/70 dark:bg-stone-950/70 backdrop-blur-2xl rounded-t-[24px] z-50 shadow-[0_-8px_24px_rgba(0,0,0,0.05)] md:hidden">
<a class="flex flex-col items-center justify-center text-orange-600 bg-orange-50 dark:bg-orange-950/30 rounded-2xl px-4 py-2 active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">home</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Главная</span>
</a>
<a class="flex flex-col items-center justify-center text-stone-400 dark:text-stone-500 px-4 py-2 hover:text-orange-500 transition-all active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined">restaurant_menu</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Меню</span>
</a>
<a class="flex flex-col items-center justify-center text-stone-400 dark:text-stone-500 px-4 py-2 hover:text-orange-500 transition-all active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined">shopping_cart</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Корзина</span>
</a>
<a class="flex flex-col items-center justify-center text-stone-400 dark:text-stone-500 px-4 py-2 hover:text-orange-500 transition-all active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined">person</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Профиль</span>
</a>
</nav>
<!-- Floating Action Button for Contact/Support (Contextual) -->
<button class="fixed right-6 bottom-32 md:bottom-10 bg-primary-container text-white w-14 h-14 rounded-full shadow-2xl flex items-center justify-center hover:scale-110 active:scale-90 transition-all z-40">
<span class="material-symbols-outlined text-2xl">chat_bubble</span>
</button>
</body></html><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-primary-fixed": "#2f1500",
                    "outline-variant": "#ddc1ae",
                    "surface": "#f9f9f9",
                    "on-error-container": "#93000a",
                    "on-tertiary-fixed-variant": "#005312",
                    "on-tertiary-container": "#00490e",
                    "outline": "#8a7362",
                    "secondary-container": "#91f78e",
                    "on-secondary": "#ffffff",
                    "surface-container-high": "#e8e8e8",
                    "on-primary-fixed-variant": "#6f3900",
                    "on-surface": "#1a1c1c",
                    "on-secondary-fixed-variant": "#005313",
                    "primary-fixed": "#ffdcc4",
                    "secondary": "#006e1c",
                    "on-tertiary": "#ffffff",
                    "tertiary-fixed-dim": "#88d982",
                    "error-container": "#ffdad6",
                    "surface-tint": "#914c00",
                    "on-primary": "#ffffff",
                    "inverse-on-surface": "#f1f1f1",
                    "secondary-fixed": "#94f990",
                    "background": "#f9f9f9",
                    "tertiary-container": "#6bbb68",
                    "surface-container-lowest": "#ffffff",
                    "inverse-primary": "#ffb77f",
                    "surface-bright": "#f9f9f9",
                    "surface-dim": "#dadada",
                    "secondary-fixed-dim": "#78dc77",
                    "tertiary": "#1b6d24",
                    "error": "#ba1a1a",
                    "primary-container": "#ff8a00",
                    "on-background": "#1a1c1c",
                    "on-error": "#ffffff",
                    "on-tertiary-fixed": "#002204",
                    "on-secondary-fixed": "#002204",
                    "on-surface-variant": "#564334",
                    "inverse-surface": "#2f3131",
                    "primary-fixed-dim": "#ffb77f",
                    "primary": "#914c00",
                    "tertiary-fixed": "#a3f69c",
                    "on-secondary-container": "#00731e",
                    "surface-container-highest": "#e2e2e2",
                    "surface-container": "#eeeeee",
                    "surface-container-low": "#f3f3f3",
                    "on-primary-container": "#613100",
                    "surface-variant": "#e2e2e2"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "full": "9999px"
            },
            "spacing": {},
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Inter"],
                    "label": ["Inter"]
            }
          },
        }
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface font-body text-on-surface">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-white/80 dark:bg-stone-900/80 backdrop-blur-xl shadow-[0px_12px_32px_rgba(86,67,52,0.08)]">
<div class="flex items-center justify-between px-6 py-4 max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-orange-600 hover:bg-stone-100 p-2 rounded-full transition-colors active:scale-95 duration-200">menu</button>
<h1 class="text-2xl font-bold tracking-tight text-orange-600 font-headline">Гастроном</h1>
</div>
<div class="hidden md:flex flex-1 max-w-md mx-8">
<div class="relative w-full">
<span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-on-surface-variant">search</span>
<input class="w-full bg-surface-container-high border-none rounded-full py-2.5 pl-10 pr-4 focus:ring-2 focus:ring-primary-container text-body-md transition-all" placeholder="Поиск блюд..." type="text"/>
</div>
</div>
<div class="flex items-center gap-2">
<div class="hidden md:flex gap-6 mr-6">
<span class="text-orange-600 font-semibold cursor-pointer">Меню</span>
<span class="text-stone-500 hover:text-orange-600 transition-colors cursor-pointer">Акции</span>
<span class="text-stone-500 hover:text-orange-600 transition-colors cursor-pointer">Доставка</span>
</div>
<div class="w-10 h-10 rounded-full bg-primary-fixed flex items-center justify-center overflow-hidden border-2 border-white">
<img class="w-full h-full object-cover" data-alt="professional portrait of a smiling user in warm soft lighting with a neutral blurred background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB1mep-Hz7pHuR5ggqgM2mWaDsHeijKkfsMye4ouMYzzbYRrVPFa3Hrk6f9z-5_Jo-EZzNvMl1RgoY9KYr_V_N2kWdvfBru5mOMUqwYypVXfhyo-xyNcF_JS_A7pvA4UI6QcqhoLDqBMLxFP-UNLSP1ClbbisFKMlR531Gk1SlvfIm9yIC0qp3CBifS_UQSoc6yIhKldW8R_cKo-wJDgqpDCSN_cj0XogRk317H-zjqgpFq5r5K00t1fFArkOZUjFArMtHVP0wfelg"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-4 max-w-7xl mx-auto">
<!-- Search Mobile -->
<div class="md:hidden mb-6">
<div class="relative w-full">
<span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-on-surface-variant">search</span>
<input class="w-full bg-surface-container-low border-none rounded-2xl py-4 pl-12 pr-4 focus:ring-2 focus:ring-primary-container shadow-sm" placeholder="Что вы хотите съесть?" type="text"/>
</div>
</div>
<!-- Categories & Filters -->
<section class="mb-8 overflow-hidden">
<div class="flex items-center justify-between mb-4">
<h2 class="font-headline font-bold text-2xl text-on-surface tracking-tight">Категории</h2>
<div class="flex gap-2">
<button class="flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-lowest border border-outline-variant/20 text-label-sm font-bold text-on-surface-variant">
<span class="material-symbols-outlined text-sm text-error" style="font-variation-settings: 'FILL' 1;">local_fire_department</span>
                        <a href="index2.html">Острое</a>
                    </button>
<button class="flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-secondary-container/30 border border-secondary/10 text-label-sm font-bold text-on-secondary-container">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">eco</span>
                        <a href="index2.html">Вегатарианские блюда</a>
                    </button>
</div>
</div>
<div class="flex gap-4 overflow-x-auto hide-scrollbar pb-2">
<!-- Category Cards -->
<div class="flex-shrink-0 flex flex-col items-center gap-2 group cursor-pointer">
<div class="w-20 h-20 rounded-3xl bg-primary-container flex items-center justify-center shadow-lg shadow-orange-200 transition-transform group-active:scale-90">
<span class="material-symbols-outlined text-white text-3xl">local_pizza</span>
</div>
<span class="font-headline font-semibold text-sm text-orange-600">Пицца</span>
</div>
<div class="flex-shrink-0 flex flex-col items-center gap-2 group cursor-pointer">
<div class="w-20 h-20 rounded-3xl bg-white flex items-center justify-center shadow-sm hover:shadow-md transition-all group-active:scale-90">
<span class="material-symbols-outlined text-stone-600 text-3xl">set_meal</span>
</div>
<span class="font-headline font-semibold text-sm text-on-surface-variant">Роллы</span>
</div>
<div class="flex-shrink-0 flex flex-col items-center gap-2 group cursor-pointer">
<div class="w-20 h-20 rounded-3xl bg-white flex items-center justify-center shadow-sm hover:shadow-md transition-all group-active:scale-90">
<span class="material-symbols-outlined text-stone-600 text-3xl">restaurant</span>
</div>
<span class="font-headline font-semibold text-sm text-on-surface-variant">Закуски</span>
</div>
<div class="flex-shrink-0 flex flex-col items-center gap-2 group cursor-pointer">
<div class="w-20 h-20 rounded-3xl bg-white flex items-center justify-center shadow-sm hover:shadow-md transition-all group-active:scale-90">
<span class="material-symbols-outlined text-stone-600 text-3xl">local_drink</span>
</div>
<span class="font-headline font-semibold text-sm text-on-surface-variant">Напитки</span>
</div>
<div class="flex-shrink-0 flex flex-col items-center gap-2 group cursor-pointer">
<div class="w-20 h-20 rounded-3xl bg-white flex items-center justify-center shadow-sm hover:shadow-md transition-all group-active:scale-90">
<span class="material-symbols-outlined text-stone-600 text-3xl">cake</span>
</div>
<span class="font-headline font-semibold text-sm text-on-surface-variant">Десерты</span>
</div>
</div>
</section>
<!-- Product Grid -->
<section>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Card 1 -->
<div class="bg-surface-container-lowest rounded-[2rem] overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group hover:shadow-xl transition-shadow duration-300">
<div class="relative h-64 overflow-hidden">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="close-up of gourmet pepperoni pizza with melted mozzarella and fresh basil on a dark stone background with warm overhead lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCdirDu-6uwyO3by-5e3NuGre4DrJIN59g9oKQRBcoyB_SgVk9GMYCu0r3VmZkOJ5MiNoxxZXZ-wXb43hzns3kILCECJWBgpe2q1Pb6xC3nq12w3G68oZvaSluH56XgaW8LG3GHbJ0bpHzZ7pu8Lv9tGpOy2Vmww93Kj8ErJZ_yXX59ee2Hq6HXxmsYIzZ0FgSbe-22ZGRhAG84LrqURriTnf5Dgn4Z3L7emuFgUWVezUrmQYsu6Ecw_n_z2VxRQmSQCaXAj_6wKKg"/>
<div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-on-surface shadow-sm">
                            480 г
                        </div>
</div>
<div class="p-6 flex-1 flex flex-col">
<div class="flex justify-between items-start mb-2">
<h3 class="font-headline font-bold text-lg leading-tight text-on-surface">Пицца Пепперони</h3>
<div class="flex items-center gap-1 text-secondary font-bold text-label-sm">
<span class="material-symbols-outlined text-xs" style="font-variation-settings: 'FILL' 1;">eco</span>
                                Fresh
                            </div>
</div>
<p class="text-body-md text-on-surface-variant line-clamp-2 mb-6">Острая колбаса пепперони, моцарелла, фирменный томатный соус и орегано на тонком тесте.</p>
<div class="mt-auto flex items-center justify-between">
<div class="flex flex-col">
<span class="text-label-sm text-stone-400 uppercase tracking-wider">Цена</span>
<span class="text-xl font-bold text-on-surface">650 ₽</span>
</div>
<button class="w-14 h-14 bg-gradient-to-br from-primary to-primary-container rounded-2xl flex items-center justify-center text-white shadow-lg shadow-orange-200 active:scale-95 transition-transform">
<span class="material-symbols-outlined text-3xl">add</span>
</button>
</div>
</div>
</div>
<!-- Card 2 -->
<div class="bg-surface-container-lowest rounded-[2rem] overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group hover:shadow-xl transition-shadow duration-300">
<div class="relative h-64 overflow-hidden">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="vibrant platter of assorted premium sushi rolls and nigiri on a black ceramic plate with ginger and wasabi in soft focus" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDja1u3BHt77C1XHs-MjzE2WxPUtfYPfg-CmMzg3vV218fxcU_tNP8t5wVoxooYNmVSJEHqiy-sRZmyA6uDaTCkBZLhm86jhI0o_kboGud38cYQG4vE_njXO8vazdqPvTj-0rkb8flqTed9Fm7B7exY0egg-W0H_9bEQHPSbF-l1EvwJQaDTvyGV2VDP5O_pN7z6o8wQba4tz9BPIQxnAQpvy_rkHJrE5ZIRcsVC3jHJ3Bi2GnbqL9n3uxmWjgz6nbmqh2Em0cd-kA"/>
<div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-on-surface shadow-sm">
                            320 г
                        </div>
<div class="absolute top-4 right-4 bg-error/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-white shadow-sm flex items-center gap-1">
<span class="material-symbols-outlined text-xs">local_fire_department</span>
                            Hot
                        </div>
</div>
<div class="p-6 flex-1 flex flex-col">
<div class="flex justify-between items-start mb-2">
<h3 class="font-headline font-bold text-lg leading-tight text-on-surface">Ролл Дракон</h3>
<div class="flex items-center gap-1 text-on-surface-variant font-bold text-label-sm">
<span class="material-symbols-outlined text-xs text-orange-500" style="font-variation-settings: 'FILL' 1;">star</span>
                                4.9
                            </div>
</div>
<p class="text-body-md text-on-surface-variant line-clamp-2 mb-6">Угорь, авокадо, сливочный сыр, икра тобико и соус унаги. Сбалансированный вкус морепродуктов.</p>
<div class="mt-auto flex items-center justify-between">
<div class="flex flex-col">
<span class="text-label-sm text-stone-400 uppercase tracking-wider">Цена</span>
<span class="text-xl font-bold text-on-surface">890 ₽</span>
</div>
<button class="w-14 h-14 bg-gradient-to-br from-primary to-primary-container rounded-2xl flex items-center justify-center text-white shadow-lg shadow-orange-200 active:scale-95 transition-transform">
<span class="material-symbols-outlined text-3xl">add</span>
</button>
</div>
</div>
</div>
<!-- Card 3 -->
<div class="bg-surface-container-lowest rounded-[2rem] overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group hover:shadow-xl transition-shadow duration-300">
<div class="relative h-64 overflow-hidden">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="massive gourmet beef burger with melting cheese, crispy bacon, and fresh lettuce on a toasted brioche bun with cinematic lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDjKfGmpUS5tb3jZ-HbmYu5Z4YmgEPF5C5w0rgxKSfBmrXl5NqvAxLgwIhJCdAdODqL6-fTKFH953KIKEpNaBGfpGlBdtQ3lkqydK1pDF-iV6SU-IoR-UWY80RzEGettsjvihjdDRm1l8E2W4A1-DFRDIpr1TISXeAJhIqX0qkdVQZip7c4qBYRXUEc1bONoAs66LLq7VMAYh5DmJcz_9AmMD-ARm66AFuEL63PVk3LOTcV6zRc7jAh0nucRKh4Ms0kQPOmHvg7EcQ"/>
<div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-on-surface shadow-sm">
                            450 г
                        </div>
</div>
<div class="p-6 flex-1 flex flex-col">
<div class="flex justify-between items-start mb-2">
<h3 class="font-headline font-bold text-lg leading-tight text-on-surface">Бургер Гранд Техас</h3>
</div>
<p class="text-body-md text-on-surface-variant line-clamp-2 mb-6">Двойная котлета из говядины, бекон, луковые кольца и соус барбекю. Настоящий вкус дикого запада.</p>
<div class="mt-auto flex items-center justify-between">
<div class="flex flex-col">
<span class="text-label-sm text-stone-400 uppercase tracking-wider">Цена</span>
<span class="text-xl font-bold text-on-surface">720 ₽</span>
</div>
<button class="w-14 h-14 bg-gradient-to-br from-primary to-primary-container rounded-2xl flex items-center justify-center text-white shadow-lg shadow-orange-200 active:scale-95 transition-transform">
<span class="material-symbols-outlined text-3xl">add</span>
</button>
</div>
</div>
</div>
<!-- Card 4 -->
<div class="bg-surface-container-lowest rounded-[2rem] overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group hover:shadow-xl transition-shadow duration-300">
<div class="relative h-64 overflow-hidden">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="close-up of crispy golden fried chicken wings with honey glaze and sesame seeds on a white minimal background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDjHBbaJRpPRNGXHbPkSuYMqiT6GMM-GvkbMxqcv3OAwnpPebwFuaCbOBooKL4NIIB6g_o0Iqu7TyjQ2cIedTzCMzu3JPjKXUt8Zuqbk3Awt5hV27WfLg09DQ0Uob4f2QjAKNpsUzWCESdbBMtBQyEQLHRc8JcWTkcayYwSb9C-4t070tJzc0M1rVZncNa93CpY_9i0e4y7gklDkMzlbUVevlcpHNoTDwfKojhvNDfPKjsja9VMowRB8kEcdnXMMX3TJXI3uHn7E00"/>
<div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-on-surface shadow-sm">
                            250 г
                        </div>
</div>
<div class="p-6 flex-1 flex flex-col">
<div class="flex justify-between items-start mb-2">
<h3 class="font-headline font-bold text-lg leading-tight text-on-surface">Крылышки Баффало</h3>
</div>
<p class="text-body-md text-on-surface-variant line-clamp-2 mb-6">Хрустящие куриные крылышки в остро-сладком соусе. Идеально для большой компании.</p>
<div class="mt-auto flex items-center justify-between">
<div class="flex flex-col">
<span class="text-label-sm text-stone-400 uppercase tracking-wider">Цена</span>
<span class="text-xl font-bold text-on-surface">450 ₽</span>
</div>
<button class="w-14 h-14 bg-gradient-to-br from-primary to-primary-container rounded-2xl flex items-center justify-center text-white shadow-lg shadow-orange-200 active:scale-95 transition-transform">
<span class="material-symbols-outlined text-3xl">add</span>
</button>
</div>
</div>
</div>
<!-- Card 5 -->
<div class="bg-surface-container-lowest rounded-[2rem] overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group hover:shadow-xl transition-shadow duration-300">
<div class="relative h-64 overflow-hidden">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="vibrant mediterranean salad with chickpeas, avocado, kale and sesame dressing in a ceramic bowl with bright natural daylight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBF1OxdpGlyB0L2jOKYxrb1yqM9Y0iYNHcz_dqZ4pR3ELPuU0mCKBFBATj1jIzCPN5iYc097pgCE9A1ki6iPKP_wdPhpwFGIqByw-yhnhhfTHFbjAAD3xhSRur19lSJi3OKkoIs_YUUuV_FFfUo9exi9Ybd3M4UQGI5eJ-MPNTCF44GrssR12r8GCJqsTMKk2bypWGpv5K0n1inFEmF9u6WdPHL9g8vWdPnKrRfa1fMDDh6Z6W8iVvePBVY6cTC3isU11G6IVbjRek"/>
<div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-on-surface shadow-sm">
                            300 г
                        </div>
<div class="absolute top-4 right-4 bg-secondary-container/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-on-secondary-container shadow-sm flex items-center gap-1">
<span class="material-symbols-outlined text-xs">eco</span>
                            Vegan
                        </div>
</div>
<div class="p-6 flex-1 flex flex-col">
<div class="flex justify-between items-start mb-2">
<h3 class="font-headline font-bold text-lg leading-tight text-on-surface">Боул с Нутом</h3>
</div>
<p class="text-body-md text-on-surface-variant line-clamp-2 mb-6">Свежий микс из авокадо, нута, шпината и киноа. С легкой заправкой из лимона и оливкового масла.</p>
<div class="mt-auto flex items-center justify-between">
<div class="flex flex-col">
<span class="text-label-sm text-stone-400 uppercase tracking-wider">Цена</span>
<span class="text-xl font-bold text-on-surface">540 ₽</span>
</div>
<button class="w-14 h-14 bg-gradient-to-br from-primary to-primary-container rounded-2xl flex items-center justify-center text-white shadow-lg shadow-orange-200 active:scale-95 transition-transform">
<span class="material-symbols-outlined text-3xl">add</span>
</button>
</div>
</div>
</div>
<!-- Card 6 -->
<div class="bg-surface-container-lowest rounded-[2rem] overflow-hidden shadow-[0px_12px_32px_rgba(86,67,52,0.05)] flex flex-col group hover:shadow-xl transition-shadow duration-300">
<div class="relative h-64 overflow-hidden">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="decadent chocolate lava cake with a molten center and dusting of powdered sugar on a minimal white plate with warm soft lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA6CsmtohEbBHBWSvgndmZ9Hf57K5E4yGvh8v1HYLpp7_We6Df8xP9abwszIwNIhh56LkX0r7KiWbtEwpy_Zcw79dkwFQGam2HvZtNlg9Vztd5f8T53fevXC6VK8Lx6eD3lJ4zPNAgrZqU0zOxqSVtGy1QWoFl1G_qFha-0a8VNPLuJbhOPS-TV-3eyU9lqJI0TPRvfsOp9OUIzMsnifNM00k9pLwc1N0lgv_Fl2Z7rHLvSR-nk-7LOqFLV2yzwLiW1eYzltFPkRGs"/>
<div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-label-sm font-bold text-on-surface shadow-sm">
                            180 г
                        </div>
</div>
<div class="p-6 flex-1 flex flex-col">
<div class="flex justify-between items-start mb-2">
<h3 class="font-headline font-bold text-lg leading-tight text-on-surface">Шоколадный Фондан</h3>
</div>
<p class="text-body-md text-on-surface-variant line-clamp-2 mb-6">Теплый десерт с жидким шоколадным центром. Подается с шариком ванильного мороженого.</p>
<div class="mt-auto flex items-center justify-between">
<div class="flex flex-col">
<span class="text-label-sm text-stone-400 uppercase tracking-wider">Цена</span>
<span class="text-xl font-bold text-on-surface">380 ₽</span>
</div>
<button class="w-14 h-14 bg-gradient-to-br from-primary to-primary-container rounded-2xl flex items-center justify-center text-white shadow-lg shadow-orange-200 active:scale-95 transition-transform">
<span class="material-symbols-outlined text-3xl">add</span>
</button>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full flex justify-around items-center px-4 pb-6 pt-3 bg-white/70 dark:bg-stone-950/70 backdrop-blur-2xl rounded-t-[24px] z-50 shadow-[0_-8px_24px_rgba(0,0,0,0.05)]">
<a class="flex flex-col items-center justify-center text-stone-400 dark:text-stone-500 px-4 py-2 hover:text-orange-500 transition-all active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined text-2xl">home</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Главная</span>
</a>
<a class="flex flex-col items-center justify-center text-orange-600 bg-orange-50 dark:bg-orange-950/30 rounded-2xl px-4 py-2 transition-all active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined text-2xl" style="font-variation-settings: 'FILL' 1;">restaurant_menu</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Меню</span>
</a>
<a class="flex flex-col items-center justify-center text-stone-400 dark:text-stone-500 px-4 py-2 hover:text-orange-500 transition-all active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined text-2xl">shopping_cart</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Корзина</span>
</a>
<a class="flex flex-col items-center justify-center text-stone-400 dark:text-stone-500 px-4 py-2 hover:text-orange-500 transition-all active:scale-90 duration-150" href="#">
<span class="material-symbols-outlined text-2xl">person</span>
<span class="font-['Inter'] text-[11px] font-medium leading-tight">Профиль</span>
</a>
</nav>
</body></html><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Детали товара - Гастроном</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-primary-fixed": "#2f1500",
                    "outline-variant": "#ddc1ae",
                    "surface": "#f9f9f9",
                    "on-error-container": "#93000a",
                    "on-tertiary-fixed-variant": "#005312",
                    "on-tertiary-container": "#00490e",
                    "outline": "#8a7362",
                    "secondary-container": "#91f78e",
                    "on-secondary": "#ffffff",
                    "surface-container-high": "#e8e8e8",
                    "on-primary-fixed-variant": "#6f3900",
                    "on-surface": "#1a1c1c",
                    "on-secondary-fixed-variant": "#005313",
                    "primary-fixed": "#ffdcc4",
                    "secondary": "#006e1c",
                    "on-tertiary": "#ffffff",
                    "tertiary-fixed-dim": "#88d982",
                    "error-container": "#ffdad6",
                    "surface-tint": "#914c00",
                    "on-primary": "#ffffff",
                    "inverse-on-surface": "#f1f1f1",
                    "secondary-fixed": "#94f990",
                    "background": "#f9f9f9",
                    "tertiary-container": "#6bbb68",
                    "surface-container-lowest": "#ffffff",
                    "inverse-primary": "#ffb77f",
                    "surface-bright": "#f9f9f9",
                    "surface-dim": "#dadada",
                    "secondary-fixed-dim": "#78dc77",
                    "tertiary": "#1b6d24",
                    "error": "#ba1a1a",
                    "primary-container": "#ff8a00",
                    "on-background": "#1a1c1c",
                    "on-error": "#ffffff",
                    "on-tertiary-fixed": "#002204",
                    "on-secondary-fixed": "#002204",
                    "on-surface-variant": "#564334",
                    "inverse-surface": "#2f3131",
                    "primary-fixed-dim": "#ffb77f",
                    "primary": "#914c00",
                    "tertiary-fixed": "#a3f69c",
                    "on-secondary-container": "#00731e",
                    "surface-container-highest": "#e2e2e2",
                    "surface-container": "#eeeeee",
                    "surface-container-low": "#f3f3f3",
                    "on-primary-container": "#613100",
                    "surface-variant": "#e2e2e2"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "1.5rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Inter"],
                    "label": ["Inter"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .tonal-shift-bg {
            background: linear-gradient(180deg, rgba(255,255,255,0.8) 0%, rgba(249,249,249,0.9) 100%);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface font-body text-on-surface antialiased">
<!-- Header Navigation Shell (Suppressed as per Task-Focused instruction, using custom header) -->
<header class="fixed top-0 w-full z-50 px-6 py-4 flex items-center justify-between bg-white/80 backdrop-blur-xl transition-all duration-200">
<button class="w-12 h-12 flex items-center justify-center rounded-xl bg-surface-container-lowest shadow-[0px_4px_12px_rgba(0,0,0,0.05)] active:scale-95 duration-200">
<span class="material-symbols-outlined text-on-surface-variant">arrow_back</span>
</button>
<div class="flex items-center gap-2">
<span class="w-2 h-2 rounded-full bg-secondary"></span>
<span class="font-label text-label-sm font-bold text-on-surface-variant uppercase tracking-wider">Доступно к заказу</span>
</div>
<button class="w-12 h-12 flex items-center justify-center rounded-xl bg-surface-container-lowest shadow-[0px_4px_12px_rgba(0,0,0,0.05)] active:scale-95 duration-200">
<span class="material-symbols-outlined text-on-surface-variant">favorite</span>
</button>
</header>
<main class="max-w-7xl mx-auto pb-32">
<div class="relative lg:flex lg:gap-12 lg:items-start lg:pt-24 lg:px-6">
<!-- Hero Image Section: Editorial Scale -->
<div class="relative w-full lg:w-3/5 overflow-hidden lg:rounded-xl">
<img class="w-full h-[442px] lg:h-[618px] object-cover lg:rounded-xl shadow-2xl" data-alt="Gourmet wagyu beef burger with melting cheddar, caramelized onions, crispy bacon and fresh arugula on a toasted brioche bun, professional food photography, dramatic lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBjIiK0IQZAHEn98WIMEfHyBqA5X3J7KUfjaiNep-9VlAP7pDV9oA4A7mr6Lzn7S6-wg-29bj5TbRf6Au_cxWnI8QiNxWR1WkqXfRlNqyGQ2kkBYp8bjwMu3W_Zrz1ZdcWajEHXY9V3uYfhOJbBiBgFhRBQy_Ay7KTpv_avxWnM3rgMqNe2O_4rH4hk92-BPRagihUmi7r1UQDbjd-E0kr7xTQbmexlDBYRjftZhNxVYOPbernFq4TZKJYYrRwGCuewS2IysYLMsAI"/>
<!-- Overlapping Badge -->
<div class="absolute bottom-6 left-6 bg-secondary-container/90 backdrop-blur-md px-4 py-2 rounded-xl">
<span class="font-label text-label-sm font-bold text-on-secondary-container">100% Натуральная говядина</span>
</div>
</div>
<!-- Content Area: The Curated Table -->
<div class="px-6 pt-8 lg:pt-0 lg:w-2/5">
<div class="flex justify-between items-start mb-2">
<h1 class="font-headline text-3xl font-bold tracking-tight text-on-surface leading-tight">Бургер Шеф-спешл</h1>
<span class="font-headline text-2xl font-extrabold text-primary">850 ₽</span>
</div>
<div class="flex items-center gap-4 mb-8">
<div class="flex items-center gap-1 text-on-surface-variant bg-surface-container-low px-3 py-1 rounded-full">
<span class="material-symbols-outlined text-sm">balance</span>
<span class="font-label text-xs font-bold">420 г</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant bg-surface-container-low px-3 py-1 rounded-full">
<span class="material-symbols-outlined text-sm text-primary-container">timer</span>
<span class="font-label text-xs font-bold">15-20 мин</span>
</div>
</div>
<div class="mb-10">
<h3 class="font-headline text-headline-sm text-on-surface mb-3">Состав ингредиентов</h3>
<p class="text-body-md text-on-surface-variant leading-relaxed">
                        Мраморная говядина Black Angus, карамелизированный лук в винном соусе, выдержанный чеддер, хрустящий бекон, авторский трюфельный соус и свежая руккола на фирменной булочке бриошь.
                    </p>
</div>
<!-- Bento Style KBJU Stats -->
<div class="grid grid-cols-4 gap-3 mb-10">
<div class="bg-surface-container-low p-4 rounded-xl flex flex-col items-center">
<span class="text-xs text-on-surface-variant font-medium mb-1">Ккал</span>
<span class="font-headline text-lg font-bold">742</span>
</div>
<div class="bg-surface-container-low p-4 rounded-xl flex flex-col items-center">
<span class="text-xs text-on-surface-variant font-medium mb-1">Белки</span>
<span class="font-headline text-lg font-bold">38г</span>
</div>
<div class="bg-surface-container-low p-4 rounded-xl flex flex-col items-center">
<span class="text-xs text-on-surface-variant font-medium mb-1">Жиры</span>
<span class="font-headline text-lg font-bold">46г</span>
</div>
<div class="bg-surface-container-low p-4 rounded-xl flex flex-col items-center">
<span class="text-xs text-on-surface-variant font-medium mb-1">Угл.</span>
<span class="font-headline text-lg font-bold">52г</span>
</div>
</div>
<!-- Add-ons Section: Modern List -->
<div class="space-y-6">
<h3 class="font-headline text-headline-sm text-on-surface">Добавить к заказу</h3>
<div class="space-y-3">
<!-- Add-on Item -->
<div class="flex items-center justify-between p-4 rounded-xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-shadow cursor-pointer">
<div class="flex items-center gap-4">
<div class="w-12 h-12 rounded-lg bg-surface-container overflow-hidden">
<img class="w-full h-full object-cover" data-alt="close up of melting cheddar cheese slice" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDCuzHhkVgS-CAZM_XH7rBF1RBfBnuhCq1IrYfi_I1fzC8s5-j0cOda8kkXaW7tynfmg8sTltQBEekRXIfTef3hYE34jhfgp0lCbUyjNfjroQRygKqyFsdqevEE61SKcMWthnA4yF_BUIDb3qvgqn_8w_qUKeNzkZY_aMMtPd3FmiPvoTUiLkyltktvOWN5sE2z63zLbKww8XThtXfePOatY-bNwyuW6j1E6lGo50c79Ti9uil0VW94eb1iUaOZp5khzkv-NOOb_as"/>
</div>
<div>
<p class="font-label text-sm font-semibold">Экстра сыр Чеддер</p>
<p class="text-xs text-on-surface-variant">+30 г</p>
</div>
</div>
<div class="flex items-center gap-3">
<span class="font-label text-sm font-bold text-on-surface-variant">+90 ₽</span>
<div class="w-8 h-8 rounded-full border-2 border-outline-variant flex items-center justify-center">
<span class="material-symbols-outlined text-lg text-primary">add</span>
</div>
</div>
</div>
<!-- Add-on Item Active -->
<div class="flex items-center justify-between p-4 rounded-xl bg-primary-container/10 border-2 border-primary-container cursor-pointer">
<div class="flex items-center gap-4">
<div class="w-12 h-12 rounded-lg bg-surface-container overflow-hidden">
<img class="w-full h-full object-cover" data-alt="crispy fried bacon strips on paper" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCL0-0R_5f3rCgIT4JyT-JQ5Iy58dwvXMHXyz5uIAib66mMlwnLqXnMaG0e0JPcYagc1iWQoYSg7CjBcWUMDng7qaYTyGOUx0FmOP9B2r9jtyVI_b9eE_yn0tl_VeeQ0zClx4Sh5KIscd0ziPClgpZ3qtlxVl-pAlxnjK6TCGsv7yV89WvgfMRFHw6cb71OJdefM_AWNLYwwKh8VcRP9OKpWRz3w0IZhwIOi8m68VDWfCZDWsgtNXzfRe7tZLP25BCuYRwN7aP5XQA"/>
</div>
<div>
<p class="font-label text-sm font-semibold">Хрустящий бекон</p>
<p class="text-xs text-on-surface-variant">+2 ломтика</p>
</div>
</div>
<div class="flex items-center gap-3">
<span class="font-label text-sm font-bold text-primary-container">+120 ₽</span>
<div class="w-8 h-8 rounded-full bg-primary-container flex items-center justify-center">
<span class="material-symbols-outlined text-lg text-white" style="font-variation-settings: 'FILL' 1;">check</span>
</div>
</div>
</div>
<!-- Add-on Item -->
<div class="flex items-center justify-between p-4 rounded-xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-shadow cursor-pointer">
<div class="flex items-center gap-4">
<div class="w-12 h-12 rounded-lg bg-surface-container overflow-hidden">
<img class="w-full h-full object-cover" data-alt="sliced green jalapeno peppers bowl" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC4QtjvlHa0y4FjZZU-2k80zz_45otwxC4u7qybuRJpsc70K0nbl8Kbm2lGRorPrKKsEW26AtdgphNKiGvjsw5SgdL8ZZOwtLTF-65W-0VWhxKq02BWHSbaz8Gpl_YSWLWSRGjPt3BwexBCYUmFygAb3PeO7hv6BqgTZh9Qe3f9zMD8foF-yVtvLujg9Fcj1siPJuKWfi5rNw_dNzdp1Mbmg_YL8UtZRZ5podCi2BekVkNEy5YL5fqMR4GrKErkuV4zhV0n1_-dgfU"/>
</div>
<div>
<p class="font-label text-sm font-semibold">Халапеньо</p>
<p class="text-xs text-on-surface-variant">+15 г</p>
</div>
</div>
<div class="flex items-center gap-3">
<span class="font-label text-sm font-bold text-on-surface-variant">+60 ₽</span>
<div class="w-8 h-8 rounded-full border-2 border-outline-variant flex items-center justify-center">
<span class="material-symbols-outlined text-lg text-primary">add</span>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</main>
<!-- Bottom Action Bar -->
<div class="fixed bottom-0 left-0 w-full p-6 bg-white/80 backdrop-blur-2xl z-50 lg:max-w-md lg:left-auto lg:right-6 lg:bottom-6 lg:rounded-3xl lg:shadow-2xl">
<div class="flex items-center gap-4">
<!-- Counter -->
<div class="flex items-center bg-surface-container-high rounded-xl px-2 py-1">
<button class="w-10 h-10 flex items-center justify-center text-on-surface-variant active:scale-90 transition-all">
<span class="material-symbols-outlined">remove</span>
</button>
<span class="w-8 text-center font-headline font-bold text-lg">1</span>
<button class="w-10 h-10 flex items-center justify-center text-on-surface-variant active:scale-90 transition-all">
<span class="material-symbols-outlined">add</span>
</button>
</div>
<!-- Primary CTA: Signature Heat Gradient -->
<button class="flex-1 bg-gradient-to-br from-primary to-primary-container text-white py-4 px-6 rounded-xl font-headline font-bold text-lg shadow-[0_8px_20px_rgba(145,76,0,0.3)] active:scale-95 duration-200">
                <a href="index3.html">В корзину за 970 ₽</a>
            </button>
</div>
</div>
</body></html><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Оформление заказа | Гастроном</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-primary-fixed": "#2f1500",
                    "outline-variant": "#ddc1ae",
                    "surface": "#f9f9f9",
                    "on-error-container": "#93000a",
                    "on-tertiary-fixed-variant": "#005312",
                    "on-tertiary-container": "#00490e",
                    "outline": "#8a7362",
                    "secondary-container": "#91f78e",
                    "on-secondary": "#ffffff",
                    "surface-container-high": "#e8e8e8",
                    "on-primary-fixed-variant": "#6f3900",
                    "on-surface": "#1a1c1c",
                    "on-secondary-fixed-variant": "#005313",
                    "primary-fixed": "#ffdcc4",
                    "secondary": "#006e1c",
                    "on-tertiary": "#ffffff",
                    "tertiary-fixed-dim": "#88d982",
                    "error-container": "#ffdad6",
                    "surface-tint": "#914c00",
                    "on-primary": "#ffffff",
                    "inverse-on-surface": "#f1f1f1",
                    "secondary-fixed": "#94f990",
                    "background": "#f9f9f9",
                    "tertiary-container": "#6bbb68",
                    "surface-container-lowest": "#ffffff",
                    "inverse-primary": "#ffb77f",
                    "surface-bright": "#f9f9f9",
                    "surface-dim": "#dadada",
                    "secondary-fixed-dim": "#78dc77",
                    "tertiary": "#1b6d24",
                    "error": "#ba1a1a",
                    "primary-container": "#ff8a00",
                    "on-background": "#1a1c1c",
                    "on-error": "#ffffff",
                    "on-tertiary-fixed": "#002204",
                    "on-secondary-fixed": "#002204",
                    "on-surface-variant": "#564334",
                    "inverse-surface": "#2f3131",
                    "primary-fixed-dim": "#ffb77f",
                    "primary": "#914c00",
                    "tertiary-fixed": "#a3f69c",
                    "on-secondary-container": "#00731e",
                    "surface-container-highest": "#e2e2e2",
                    "surface-container": "#eeeeee",
                    "surface-container-low": "#f3f3f3",
                    "on-primary-container": "#613100",
                    "surface-variant": "#e2e2e2"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "2xl": "1rem",
                    "3xl": "1.5rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Inter"],
                    "label": ["Inter"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Inter', sans-serif; }
        h1, h2, .brand-font { font-family: 'Plus Jakarta Sans', sans-serif; }
        .no-scrollbar::-webkit-scrollbar { display: none; }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface text-on-surface antialiased min-h-screen pb-32">
<header class="fixed top-0 w-full z-50 bg-white/80 dark:bg-stone-900/80 backdrop-blur-xl shadow-[0px_12px_32px_rgba(86,67,52,0.08)]">
<div class="flex items-center justify-between px-6 py-4 max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="w-10 h-10 flex items-center justify-center rounded-full hover:bg-stone-100 transition-colors active:scale-95 duration-200">
<span class="material-symbols-outlined text-stone-900" data-icon="arrow_back">arrow_back</span>
</button>
<span class="text-2xl font-bold tracking-tight text-orange-600 brand-font">Гастроном</span>
</div>
<div class="hidden md:flex items-center gap-8">
<span class="text-stone-500 font-medium">Главная</span>
<span class="text-stone-500 font-medium">Меню</span>
<span class="text-orange-600 font-semibold">Оформление</span>
</div>
<div class="w-10 h-10 rounded-full bg-surface-container-high overflow-hidden">
<img class="w-full h-full object-cover" data-alt="Professional portrait of a user for profile avatar, soft studio lighting, clean background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB1T-dJ4TbDsmd-9YrGjwSuoXM7Atw5cm83Wj5QusC5AteelyjJ0pNOrrAELWjYzglqSDAgcvDg_L96eZOyZVJVMfODIuK4GJXEVnSRA9_OKk09_lKRf6awnibmKS4FDHZE8Z_oPdKYqUiUAzRd1k_YA4hCfdjamdScKOC0lAJ22N4HObaUfU7EQSH1Yvm-pfix_4NxMFoAdk0n-0O7-yRvyAx961OfHLc71BsPWtEhsCvCGTz1Ktsm2Tv3AFbOyKQcXC6cC2_Dm5Q"/>
</div>
</div>
</header>
<main class="pt-24 px-4 max-w-3xl mx-auto">
<h1 class="text-3xl font-extrabold text-on-surface mb-8 tracking-tight">Оформление заказа</h1>
<div class="space-y-6">
<!-- Method Toggle -->
<section class="bg-surface-container-lowest p-2 rounded-3xl flex gap-2 shadow-sm">
<button class="flex-1 py-3 px-6 rounded-2xl bg-primary-container text-white font-semibold transition-all active:scale-95">
                    Доставка
                </button>
<button class="flex-1 py-3 px-6 rounded-2xl text-stone-500 font-medium hover:bg-stone-50 transition-all active:scale-95">
                    Самовывоз
                </button>
</section>
<!-- Address Form -->
<section class="bg-surface-container-lowest p-6 rounded-3xl space-y-6">
<div class="flex items-center gap-3 mb-2">
<span class="material-symbols-outlined text-primary" data-icon="location_on">location_on</span>
<h2 class="text-xl font-bold">Адрес доставки</h2>
</div>
<div class="space-y-4">
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Улица и дом</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="пр. Мира, д. 12" type="text"/>
</div>
<div class="grid grid-cols-2 md:grid-cols-4 gap-4">
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Кв/Офис</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="102" type="text"/>
</div>
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Подъезд</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="3" type="text"/>
</div>
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Этаж</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="5" type="text"/>
</div>
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Домофон</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="102#" type="text"/>
</div>
</div>
</div>
</section>
<!-- Time Selection -->
<section class="bg-surface-container-lowest p-6 rounded-3xl">
<div class="flex items-center gap-3 mb-6">
<span class="material-symbols-outlined text-primary" data-icon="schedule">schedule</span>
<h2 class="text-xl font-bold">Время доставки</h2>
</div>
<div class="flex flex-wrap gap-3">
<button class="bg-primary-fixed text-on-primary-fixed px-6 py-3 rounded-2xl font-semibold flex items-center gap-2 border-2 border-primary-container">
<span class="w-2 h-2 rounded-full bg-primary-container"></span>
                        Как можно скорее
                    </button>
<button class="bg-surface-container-low text-on-surface-variant px-6 py-3 rounded-2xl font-medium hover:bg-surface-container-high transition-colors">
                        Ко времени
                    </button>
</div>
</section>
<!-- Payment Methods -->
<section class="bg-surface-container-lowest p-6 rounded-3xl">
<div class="flex items-center gap-3 mb-6">
<span class="material-symbols-outlined text-primary" data-icon="payments">payments</span>
<h2 class="text-xl font-bold">Способ оплаты</h2>
</div>
<div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
<button class="flex flex-col items-center justify-center p-4 rounded-2xl border-2 border-primary-container bg-primary-fixed/30 text-on-primary-container transition-all">
<span class="material-symbols-outlined mb-2 text-3xl" data-icon="credit_card">credit_card</span>
<span class="text-sm font-bold">Картой онлайн</span>
</button>
<button class="flex flex-col items-center justify-center p-4 rounded-2xl border-2 border-transparent bg-surface-container-low text-on-surface-variant hover:bg-surface-container-high transition-all">
<span class="material-symbols-outlined mb-2 text-3xl" data-icon="payments">payments</span>
<span class="text-sm font-bold">Наличными</span>
</button>
<button class="flex flex-col items-center justify-center p-4 rounded-2xl border-2 border-transparent bg-surface-container-low text-on-surface-variant hover:bg-surface-container-high transition-all">
<span class="material-symbols-outlined mb-2 text-3xl" data-icon="account_balance_wallet">account_balance_wallet</span>
<span class="text-sm font-bold">Apple / Google Pay</span>
</button>
</div>
</section>
<!-- Comments -->
<section class="bg-surface-container-lowest p-6 rounded-3xl">
<div class="flex items-center gap-3 mb-4">
<span class="material-symbols-outlined text-primary" data-icon="chat_bubble">chat_bubble</span>
<h2 class="text-xl font-bold">Комментарий</h2>
</div>
<textarea class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium resize-none" placeholder="Напишите курьеру, как вас найти или оставьте пожелания..." rows="3"></textarea>
</section>
<!-- Order Summary for Web -->
<section class="bg-surface-container-low p-8 rounded-3xl border-dashed border-2 border-outline-variant/30">
<div class="flex justify-between items-center mb-4">
<span class="text-stone-500 font-medium">Стоимость блюд</span>
<span class="text-on-surface font-bold">2 450 ₽</span>
</div>
<div class="flex justify-between items-center mb-4">
<span class="text-stone-500 font-medium">Доставка</span>
<span class="text-secondary font-bold">Бесплатно</span>
</div>
<div class="h-px bg-outline-variant/20 my-6"></div>
<div class="flex justify-between items-end">
<div>
<p class="text-xs font-bold text-stone-400 uppercase tracking-widest mb-1">Итого к оплате</p>
<p class="text-4xl font-extrabold text-on-surface brand-font">2 450 ₽</p>
</div>
</div>
</section>
</div>
</main>
<!-- Bottom Action Bar (Fixed Mobile & Web Sticky) -->
<footer class="fixed bottom-0 left-0 w-full bg-white/70 backdrop-blur-2xl z-50 px-6 py-6 border-t-0 shadow-[0_-8px_24px_rgba(0,0,0,0.05)]">
<div class="max-w-3xl mx-auto flex items-center justify-between gap-6">
<div class="hidden sm:block">
<p class="text-xs font-bold text-stone-400 uppercase">Итого</p>
<p class="text-2xl font-bold text-on-surface">2 450 ₽</p>
</div>
<button class="flex-1 bg-gradient-to-br from-primary to-primary-container text-white py-5 px-8 rounded-3xl font-bold text-lg shadow-lg shadow-primary-container/20 active:scale-95 duration-200 transition-all">
                <a href="index4.html">Подтвердить заказ</a>
            </button>
</div>
</footer>
<!-- Bottom Nav for Navigation (Mobile Context) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full bg-white/70 backdrop-blur-2xl flex justify-around items-center px-4 pb-4 pt-2 z-50 pointer-events-none opacity-0">
<!-- Hidden as per Checkout Task Priority to focus on Action -->
</nav>
</body></html><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Оформление заказа | Гастроном</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-primary-fixed": "#2f1500",
                    "outline-variant": "#ddc1ae",
                    "surface": "#f9f9f9",
                    "on-error-container": "#93000a",
                    "on-tertiary-fixed-variant": "#005312",
                    "on-tertiary-container": "#00490e",
                    "outline": "#8a7362",
                    "secondary-container": "#91f78e",
                    "on-secondary": "#ffffff",
                    "surface-container-high": "#e8e8e8",
                    "on-primary-fixed-variant": "#6f3900",
                    "on-surface": "#1a1c1c",
                    "on-secondary-fixed-variant": "#005313",
                    "primary-fixed": "#ffdcc4",
                    "secondary": "#006e1c",
                    "on-tertiary": "#ffffff",
                    "tertiary-fixed-dim": "#88d982",
                    "error-container": "#ffdad6",
                    "surface-tint": "#914c00",
                    "on-primary": "#ffffff",
                    "inverse-on-surface": "#f1f1f1",
                    "secondary-fixed": "#94f990",
                    "background": "#f9f9f9",
                    "tertiary-container": "#6bbb68",
                    "surface-container-lowest": "#ffffff",
                    "inverse-primary": "#ffb77f",
                    "surface-bright": "#f9f9f9",
                    "surface-dim": "#dadada",
                    "secondary-fixed-dim": "#78dc77",
                    "tertiary": "#1b6d24",
                    "error": "#ba1a1a",
                    "primary-container": "#ff8a00",
                    "on-background": "#1a1c1c",
                    "on-error": "#ffffff",
                    "on-tertiary-fixed": "#002204",
                    "on-secondary-fixed": "#002204",
                    "on-surface-variant": "#564334",
                    "inverse-surface": "#2f3131",
                    "primary-fixed-dim": "#ffb77f",
                    "primary": "#914c00",
                    "tertiary-fixed": "#a3f69c",
                    "on-secondary-container": "#00731e",
                    "surface-container-highest": "#e2e2e2",
                    "surface-container": "#eeeeee",
                    "surface-container-low": "#f3f3f3",
                    "on-primary-container": "#613100",
                    "surface-variant": "#e2e2e2"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "2xl": "1rem",
                    "3xl": "1.5rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Inter"],
                    "label": ["Inter"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Inter', sans-serif; }
        h1, h2, .brand-font { font-family: 'Plus Jakarta Sans', sans-serif; }
        .no-scrollbar::-webkit-scrollbar { display: none; }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface text-on-surface antialiased min-h-screen pb-32">
<header class="fixed top-0 w-full z-50 bg-white/80 dark:bg-stone-900/80 backdrop-blur-xl shadow-[0px_12px_32px_rgba(86,67,52,0.08)]">
<div class="flex items-center justify-between px-6 py-4 max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="w-10 h-10 flex items-center justify-center rounded-full hover:bg-stone-100 transition-colors active:scale-95 duration-200">
<span class="material-symbols-outlined text-stone-900" data-icon="arrow_back">arrow_back</span>
</button>
<span class="text-2xl font-bold tracking-tight text-orange-600 brand-font">Гастроном</span>
</div>
<div class="hidden md:flex items-center gap-8">
<span class="text-stone-500 font-medium">Главная</span>
<span class="text-stone-500 font-medium">Меню</span>
<span class="text-orange-600 font-semibold">Оформление</span>
</div>
<div class="w-10 h-10 rounded-full bg-surface-container-high overflow-hidden">
<img class="w-full h-full object-cover" data-alt="Professional portrait of a user for profile avatar, soft studio lighting, clean background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB1T-dJ4TbDsmd-9YrGjwSuoXM7Atw5cm83Wj5QusC5AteelyjJ0pNOrrAELWjYzglqSDAgcvDg_L96eZOyZVJVMfODIuK4GJXEVnSRA9_OKk09_lKRf6awnibmKS4FDHZE8Z_oPdKYqUiUAzRd1k_YA4hCfdjamdScKOC0lAJ22N4HObaUfU7EQSH1Yvm-pfix_4NxMFoAdk0n-0O7-yRvyAx961OfHLc71BsPWtEhsCvCGTz1Ktsm2Tv3AFbOyKQcXC6cC2_Dm5Q"/>
</div>
</div>
</header>
<main class="pt-24 px-4 max-w-3xl mx-auto">
<h1 class="text-3xl font-extrabold text-on-surface mb-8 tracking-tight">Оформление заказа</h1>
<div class="space-y-6">
<!-- Method Toggle -->
<section class="bg-surface-container-lowest p-2 rounded-3xl flex gap-2 shadow-sm">
<button class="flex-1 py-3 px-6 rounded-2xl bg-primary-container text-white font-semibold transition-all active:scale-95">
                    <a href="index5.html">Доставка</a>
                </button>
<button class="flex-1 py-3 px-6 rounded-2xl text-stone-500 font-medium hover:bg-stone-50 transition-all active:scale-95">
                    <a href="index5.html">отмена заказа</a>
                </button>
</section>
<!-- Address Form -->
<section class="bg-surface-container-lowest p-6 rounded-3xl space-y-6">
<div class="flex items-center gap-3 mb-2">
<span class="material-symbols-outlined text-primary" data-icon="location_on">location_on</span>
<h2 class="text-xl font-bold">Адрес доставки</h2>
</div>
<div class="space-y-4">
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Улица и дом</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="пр. Мира, д. 12" type="text"/>
</div>
<div class="grid grid-cols-2 md:grid-cols-4 gap-4">
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Кв/Офис</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="102" type="text"/>
</div>
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Подъезд</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="3" type="text"/>
</div>
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Этаж</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="5" type="text"/>
</div>
<div class="relative">
<label class="text-xs font-bold text-stone-400 uppercase tracking-wider mb-1 ml-4 block">Домофон</label>
<input class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium" placeholder="102#" type="text"/>
</div>
</div>
</div>
</section>
<!-- Time Selection -->
<section class="bg-surface-container-lowest p-6 rounded-3xl">
<div class="flex items-center gap-3 mb-6">
<span class="material-symbols-outlined text-primary" data-icon="schedule">schedule</span>
<h2 class="text-xl font-bold">Время доставки</h2>
</div>
<div class="flex flex-wrap gap-3">
<button class="bg-primary-fixed text-on-primary-fixed px-6 py-3 rounded-2xl font-semibold flex items-center gap-2 border-2 border-primary-container">
<span class="w-2 h-2 rounded-full bg-primary-container"></span>
                        <a href="index5.html">как можно скорее</a>
                    </button>
<button class="bg-surface-container-low text-on-surface-variant px-6 py-3 rounded-2xl font-medium hover:bg-surface-container-high transition-colors">
                        <a href="index5.html">Ко времени</a>
                    </button>
</div>
</section>
<!-- Payment Methods -->
<section class="bg-surface-container-lowest p-6 rounded-3xl">
<div class="flex items-center gap-3 mb-6">
<span class="material-symbols-outlined text-primary" data-icon="payments">payments</span>
<h2 class="text-xl font-bold">Способ оплаты</h2>
</div>
<div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
<button class="flex flex-col items-center justify-center p-4 rounded-2xl border-2 border-primary-container bg-primary-fixed/30 text-on-primary-container transition-all">
<span class="material-symbols-outlined mb-2 text-3xl" data-icon="credit_card">credit_card</span>
<span class="text-sm font-bold"><a href="index5.html">Картой онлайн</a></span>
</button>
<button class="flex flex-col items-center justify-center p-4 rounded-2xl border-2 border-transparent bg-surface-container-low text-on-surface-variant hover:bg-surface-container-high transition-all">
<span class="material-symbols-outlined mb-2 text-3xl" data-icon="payments">payments</span>
<span class="text-sm font-bold">Наличными</span>
</button>
<button class="flex flex-col items-center justify-center p-4 rounded-2xl border-2 border-transparent bg-surface-container-low text-on-surface-variant hover:bg-surface-container-high transition-all">
<span class="material-symbols-outlined mb-2 text-3xl" data-icon="account_balance_wallet">account_balance_wallet</span>
<span class="text-sm font-bold">Apple / Google Pay</span>
</button>
</div>
</section>
<!-- Comments -->
<section class="bg-surface-container-lowest p-6 rounded-3xl">
<div class="flex items-center gap-3 mb-4">
<span class="material-symbols-outlined text-primary" data-icon="chat_bubble">chat_bubble</span>
<h2 class="text-xl font-bold">Комментарий</h2>
</div>
<textarea class="w-full bg-surface-container-low border-none rounded-2xl px-4 py-4 focus:ring-2 focus:ring-primary-container/20 focus:bg-white transition-all text-on-surface font-medium resize-none" placeholder="Напишите курьеру, как вас найти или оставьте пожелания..." rows="3"></textarea>
</section>
<!-- Order Summary for Web -->
<section class="bg-surface-container-low p-8 rounded-3xl border-dashed border-2 border-outline-variant/30">
<div class="flex justify-between items-center mb-4">
<span class="text-stone-500 font-medium">Стоимость блюд</span>
<span class="text-on-surface font-bold">2 450 ₽</span>
</div>
<div class="flex justify-between items-center mb-4">
<span class="text-stone-500 font-medium">Доставка</span>
<span class="text-secondary font-bold">Бесплатно</span>
</div>
<div class="h-px bg-outline-variant/20 my-6"></div>
<div class="flex justify-between items-end">
<div>
<p class="text-xs font-bold text-stone-400 uppercase tracking-widest mb-1">Итого к оплате</p>
<p class="text-4xl font-extrabold text-on-surface brand-font">2 450 ₽</p>
</div>
</div>
</section>
</div>
</main>
<!-- Bottom Action Bar (Fixed Mobile & Web Sticky) -->
<footer class="fixed bottom-0 left-0 w-full bg-white/70 backdrop-blur-2xl z-50 px-6 py-6 border-t-0 shadow-[0_-8px_24px_rgba(0,0,0,0.05)]">
<div class="max-w-3xl mx-auto flex items-center justify-between gap-6">
<div class="hidden sm:block">
<p class="text-xs font-bold text-stone-400 uppercase">Итого</p>
<p class="text-2xl font-bold text-on-surface">2 450 ₽</p>
</div>
<button class="flex-1 bg-gradient-to-br from-primary to-primary-container text-white py-5 px-8 rounded-3xl font-bold text-lg shadow-lg shadow-primary-container/20 active:scale-95 duration-200 transition-all">
                <a href="index5.html">Подтвердить заказ</a>
            </button>
</div>
</footer>
<!-- Bottom Nav for Navigation (Mobile Context) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full bg-white/70 backdrop-blur-2xl flex justify-around items-center px-4 pb-4 pt-2 z-50 pointer-events-none opacity-0">
<!-- Hidden as per Checkout Task Priority to focus on Action -->
</nav>
</body></html><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&amp;family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface-container-high": "#e8e8e8",
                        "on-error-container": "#93000a",
                        "on-secondary-fixed": "#002204",
                        "primary-fixed": "#ffdcc4",
                        "tertiary-fixed": "#a3f69c",
                        "surface-dim": "#dadada",
                        "on-tertiary-fixed-variant": "#005312",
                        "on-primary-container": "#613100",
                        "on-primary-fixed": "#2f1500",
                        "tertiary": "#1b6d24",
                        "surface-tint": "#914c00",
                        "primary-container": "#ff8a00",
                        "on-error": "#ffffff",
                        "on-background": "#1a1c1c",
                        "tertiary-fixed-dim": "#88d982",
                        "inverse-primary": "#ffb77f",
                        "primary-fixed-dim": "#ffb77f",
                        "surface-container": "#eeeeee",
                        "outline-variant": "#ddc1ae",
                        "on-secondary-fixed-variant": "#005313",
                        "secondary-fixed-dim": "#78dc77",
                        "surface-container-lowest": "#ffffff",
                        "inverse-on-surface": "#f1f1f1",
                        "surface-container-highest": "#e2e2e2",
                        "surface": "#f9f9f9",
                        "error": "#ba1a1a",
                        "background": "#f9f9f9",
                        "on-surface": "#1a1c1c",
                        "secondary-fixed": "#94f990",
                        "on-secondary": "#ffffff",
                        "outline": "#8a7362",
                        "on-tertiary-container": "#00490e",
                        "secondary": "#006e1c",
                        "on-primary": "#ffffff",
                        "inverse-surface": "#2f3131",
                        "surface-container-low": "#f3f3f3",
                        "on-surface-variant": "#564334",
                        "error-container": "#ffdad6",
                        "primary": "#914c00",
                        "on-tertiary": "#ffffff",
                        "surface-bright": "#f9f9f9",
                        "on-primary-fixed-variant": "#6f3900",
                        "surface-variant": "#e2e2e2",
                        "tertiary-container": "#6bbb68",
                        "secondary-container": "#91f78e",
                        "on-tertiary-fixed": "#002204",
                        "on-secondary-container": "#00731e"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Inter"],
                        "label": ["Inter"]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f9f9f9;
            color: #1a1c1c;
        }
        h1, h2, h3 {
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        .tonal-shift {
            background-color: rgba(255, 138, 0, 0.04);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background text-on-background min-h-screen pb-32">
<!-- TopAppBar from JSON -->
<header class="bg-white/80 dark:bg-zinc-900/80 backdrop-blur-md fixed top-0 w-full z-50 shadow-[0px_12px_32px_rgba(86,67,52,0.08)]">
<div class="flex justify-between items-center px-4 h-16 w-full max-w-md mx-auto">
<button class="material-symbols-outlined text-orange-600 dark:text-orange-400 hover:bg-zinc-100 dark:hover:bg-zinc-800 transition-colors active:scale-95 transition-transform p-2 rounded-full" data-icon="arrow_back">arrow_back</button>
<h1 class="font-['Plus_Jakarta_Sans'] font-semibold text-lg font-bold text-zinc-900 dark:text-zinc-50">Status</h1>
<button class="material-symbols-outlined text-orange-600 dark:text-orange-400 hover:bg-zinc-100 dark:hover:bg-zinc-800 transition-colors active:scale-95 transition-transform p-2 rounded-full" data-icon="more_vert">more_vert</button>
</div>
</header>
<main class="max-w-md mx-auto pt-24 px-6 space-y-8">
<!-- Hero Illustration & Main Status -->
<section class="text-center space-y-6">
<div class="relative w-full aspect-square max-w-[280px] mx-auto rounded-[2.5rem] overflow-hidden bg-surface-container-low shadow-inner">
<img class="w-full h-full object-cover" data-alt="vibrant 3D illustration of a friendly food delivery courier on a bright orange scooter navigating through a clean stylized city street" src="https://lens.usercontent.google.com/banana?agsi=CmdnbG9iYWw6OjAwMDA1NWNmZWM3MDAyNmQ6MDAwMDAwZWI6MTo3NWVjNDdlY2FhZGNiYTkxOjAwMDA1NWNmZWM3MDAyNmQ6MDAwMDAxN2RlMTgwMzM2ODowMDA2NGY5MzQ1MTU0NTdmEAIYAQ=="/>
</div>
<div class="space-y-2">
<h2 class="text-[1.75rem] font-extrabold tracking-tight leading-tight text-on-surface">Заказ уже в пути!</h2>
<div class="inline-flex items-center gap-2 bg-primary-container/10 px-4 py-2 rounded-full">
<span class="material-symbols-outlined text-primary text-xl" data-icon="schedule">schedule</span>
<span class="text-primary font-bold font-label text-sm uppercase tracking-wider">Приедет через 15-20 минут</span>
</div>
</div>
</section>
<!-- Tracker Section (The Curated Table Logic: No Lines) -->
<section class="bg-surface-container-lowest rounded-3xl p-6 shadow-[0px_12px_32px_rgba(86,67,52,0.05)]">
<div class="flex justify-between relative">
<!-- Tracker Line (Tonal Layering) -->
<div class="absolute top-5 left-8 right-8 h-[2px] bg-surface-container-high z-0">
<div class="h-full bg-primary-container w-[75%] rounded-full"></div>
</div>
<!-- Stages -->
<div class="flex flex-col items-center gap-2 z-10 relative">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-on-primary ring-4 ring-surface-container-lowest">
<span class="material-symbols-outlined text-lg" data-icon="check" data-weight="fill">check</span>
</div>
<span class="text-[10px] font-bold uppercase tracking-tight text-on-surface-variant text-center leading-none">Заказ принят</span>
</div>
<div class="flex flex-col items-center gap-2 z-10 relative">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-on-primary ring-4 ring-surface-container-lowest">
<span class="material-symbols-outlined text-lg" data-icon="restaurant" data-weight="fill">restaurant</span>
</div>
<span class="text-[10px] font-bold uppercase tracking-tight text-on-surface-variant text-center leading-none">Готовится</span>
</div>
<div class="flex flex-col items-center gap-2 z-10 relative">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-on-primary ring-4 ring-surface-container-lowest ring-offset-2 ring-primary-container/20">
<span class="material-symbols-outlined text-lg" data-icon="delivery_dining" data-weight="fill">delivery_dining</span>
</div>
<span class="text-[10px] font-extrabold uppercase tracking-tight text-primary text-center leading-none">В пути</span>
</div>
<div class="flex flex-col items-center gap-2 z-10 relative opacity-40">
<div class="w-10 h-10 rounded-full bg-surface-container-high flex items-center justify-center text-on-surface-variant ring-4 ring-surface-container-lowest">
<span class="material-symbols-outlined text-lg" data-icon="home" data-weight="fill">home</span>
</div>
<span class="text-[10px] font-bold uppercase tracking-tight text-on-surface-variant text-center leading-none">Доставлен</span>
</div>
</div>
</section>
<!-- Courier Card (Editorial Scale) -->
<section class="bg-surface-container-low rounded-[2rem] p-5 flex items-center gap-4 relative overflow-hidden">
<!-- Decorative Gradient Blob -->
<div class="absolute -right-10 -bottom-10 w-32 h-32 bg-primary-container/10 rounded-full blur-3xl"></div>
<div class="w-20 h-20 rounded-2xl overflow-hidden shrink-0 border-4 border-surface-container-lowest shadow-sm">
<img class="w-full h-full object-cover" data-alt="professional portrait of a friendly male delivery courier in a clean orange uniform smiling at the camera outdoors" src="https://photobooth.cdn.sports.ru/preset/news/4/2a/7a56d7c1c4751abc3da9b19f4be0e.png"/>
</div>
<div class="flex-1 space-y-1">
<p class="text-[10px] font-extrabold uppercase tracking-[0.1em] text-primary">Ваш курьер</p>
<h3 class="text-xl font-bold text-on-surface">Леонель Месси</h3>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-primary-container text-base" data-icon="star" data-weight="fill">star</span>
<span class="text-sm font-bold text-on-surface-variant">4.9</span>
<span class="text-xs text-on-surface-variant/60 ml-1">• 1.2k заказов</span>
</div>
</div>
<button class="w-12 h-12 rounded-full bg-surface-container-lowest flex items-center justify-center text-primary shadow-sm active:scale-90 transition-transform">
<span class="material-symbols-outlined" data-icon="chat">chat</span>
</button>
</section>
<!-- Action Button (Signature Texture) -->
<button class="w-full h-16 rounded-xl bg-gradient-to-br from-primary to-primary-container text-on-primary font-bold text-lg flex items-center justify-center gap-3 shadow-[0px_12px_24px_rgba(145,76,0,0.25)] active:scale-[0.98] transition-transform">
</button>
</main>
<!-- BottomNavBar from JSON -->
<nav class="fixed bottom-0 left-0 w-full flex justify-around items-center px-6 pb-6 pt-3 bg-white/70 dark:bg-zinc-900/70 backdrop-blur-xl z-50 rounded-t-[1.5rem] shadow-[0px_-4px_20px_rgba(0,0,0,0.05)]">
<div class="flex flex-col items-center justify-center text-zinc-400 dark:text-zinc-500 px-3 py-1 hover:text-orange-500 transition-colors active:scale-90 transition-transform">
<span class="material-symbols-outlined mb-1" data-icon="restaurant">restaurant</span>
<span class="font-['Inter'] text-[10px] font-bold uppercase tracking-wider">Explore</span>
</div>
<div class="flex flex-col items-center justify-center bg-orange-100 dark:bg-orange-900/30 text-orange-700 dark:text-orange-300 rounded-2xl px-3 py-1 active:scale-90 transition-transform">
<span class="material-symbols-outlined mb-1" data-icon="receipt_long">receipt_long</span>
<span class="font-['Inter'] text-[10px] font-bold uppercase tracking-wider">Orders</span>
</div>
<div class="flex flex-col items-center justify-center text-zinc-400 dark:text-zinc-500 px-3 py-1 hover:text-orange-500 transition-colors active:scale-90 transition-transform">
<span class="material-symbols-outlined mb-1" data-icon="search">search</span>
<span class="font-['Inter'] text-[10px] font-bold uppercase tracking-wider">Search</span>
</div>
<div class="flex flex-col items-center justify-center text-zinc-400 dark:text-zinc-500 px-3 py-1 hover:text-orange-500 transition-colors active:scale-90 transition-transform">
<span class="material-symbols-outlined mb-1" data-icon="person">person</span>
<span class="font-['Inter'] text-[10px] font-bold uppercase tracking-wider">Profile</span>
</div>
</nav>
</body></html>
