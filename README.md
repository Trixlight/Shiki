# Установка
1. Скопируйте код ниже
2. На Шики перейдите в Настройки > Внешний вид сайта > Стили сайта
3. Вставте код в поле CSS
4. (Необязательно) Замените ссылки на фоновые изображения

```css
/**
** Фоны для Светлой темы
** Используются по умолчанию
**/
:root {
  --site-bg: url("");
  --profile-head-bg: url("");
}

/**
** Фоны для Тёмной темы
** Используются при выборе Тёмной темы оформления в ОС
** Поддерживаются в ОС: Windows 10 1809+, macOS 10.14+, Android 10+
** Поддерживаются в браузерах: Chrome 76+, Firefox 67+, Opera 62+
** Полный список (внизу страницы):
** https://developer.mozilla.org/ru/docs/Web/CSS/@media/prefers-color-scheme
**/
@media (prefers-color-scheme: dark) {
  :root {
    --site-bg: url("https://i.imgur.com/XEYoTw4.jpg");
    --profile-head-bg: url("https://i.imgur.com/KTN16kQ.jpg");
  }
}

/**
** Импорт файлов стиля с GitHub
** Обновление кеша @import-стилей:
** https://shikimori.one/tests/reset_styles_cache
**/

@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/global.css");
```
