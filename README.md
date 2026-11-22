# AI Reader — тестові збірки

Тут лише тестові APK застосунку AI Reader (debug-збірки з гілки `main`). Код застосунку — у приватному репозиторії.

- Свіжа збірка завжди одна: пререліз [`dev-build`](../../releases/tag/dev-build).
- Її сам кладе CI основного репозиторію після кожного злиття в `main`. Руками сюди нічого не комітити.
- Тестова збірка вміє сама оновлюватися звідси (кнопка «Оновлення»). Версія з Google Play оновлюється лише через Play.
- Не для Play Market.
- Папка `docs/` — публічні сторінки для Google Play: [політика конфіденційності](https://takate20.github.io/aiReader-builds/privacy.html) і [видалення акаунта](https://takate20.github.io/aiReader-builds/delete-account.html) (GitHub Pages з `main` /docs). Їх генерує скрипт `scripts/legal/build-pages.mjs` основного репозиторію; зміни — через PR.
