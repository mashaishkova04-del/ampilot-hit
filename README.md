# A&M — Astro + Decap CMS Starter (Clean)
Готовый проект для GitHub + Netlify. Админка — `/admin`.
## Локально
```bash
npm i
npm run dev
```
## Деплой на Netlify (из GitHub)
1. Репозиторий должен содержать в корне:
```
package.json
astro.config.mjs
netlify.toml
tsconfig.json
public/
src/
.node-version
```
2. На Netlify: **Add new site → Import from Git** → выбери репо  
   Build command: `npm run build` · Publish dir: `dist`
3. Включи **Identity** и **Git Gateway** (для входа в `/admin`).
## Контент
- Кейсы: `src/pages/cases/*.md`
- Команда: `src/pages/team/*.md`
- Настройки: `src/data/settings.json`
- Медиа: `public/uploads`
