# ReVC Web — GitHub Pages

Веб-версия ReVC, подготовленная для размещения на GitHub Pages.

## Структура

- `index.html` — интерфейс и запуск движка
- `reVC.js` — JavaScript/WebAssembly loader
- `reVC.wasm` — движок
- `serve.py` — локальный сервер (можно не загружать в GitHub Pages)

## GitHub Pages

1. Создайте репозиторий.
2. Загрузите `index.html`, `reVC.js` и `reVC.wasm` в корень репозитория.
3. Откройте **Settings → Pages**.
4. Выберите **Deploy from a branch → main → / (root)**.
5. Откройте выданный GitHub Pages адрес.

GitHub Pages должен отдавать страницу по HTTPS. `serve.py` для GitHub Pages не требуется.
