# Hi, I'm Nikita 👋

[![Website](https://img.shields.io/badge/Website-ksenus.ru-1a1a2e?style=flat-square&logo=google-chrome&logoColor=white)](https://ksenus.ru/) [![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ktm.softwear@gmail.com)

### AI Fullstack Engineer · Строю агентные системы, которые доходят до продакшена

Строю production LLM-агенты под ключ — React-фронтенды, Node-бэкенды, multi-agent orchestration, tool/MCP integration и *harness engineering*, который делает агентов надёжными, наблюдаемыми и достаточно дешёвыми для масштаба. Не «демо-чатбот», а **автономный воркер с бюджетом.**

Один агент, который я собрал вместе с командой, сам закрывает **~70% месячной нагрузки** premium concierge-команды. Другой читает актуальные цены номеров с *любого* сайта отеля примерно за **3¢ за запрос** — после оптимизации стоимость упала в **26.5×** без потери качества.

- 🔭 Строю агентную автоматизацию для premium concierge-сервиса
- 🌱 Углубляюсь в context engineering, agent evaluation и cost optimization
- ⚡ Ежедневно — AI-driven разработка в 5–10 параллельных agent sessions
- 💬 Спрашивайте про Claude Agent SDK, LangGraph, MCP или как выжать 26× из agent pipeline

---

### 🔬 Исследования и эксперименты

**📊 agent-regression-bench** — *evaluation harness + cost study*

Как понять, что правка промпта тихо не сломала прод? Запускаешь bench. **240 scripted agent tasks** — tool-use, retrieval, multi-step workflows — pass rate, latency и token spend на каждый сценарий. Сократил eval loop с **~45 мин ручных spot-checks** до **6 мин автоматических прогонов**. Один проход context compression срезал среднюю стоимость сессии в **18×** при **97%** task pass rate.
`Node.js` · `TypeScript` · `Claude Agent SDK` · `LangGraph` · `PostgreSQL`

---

### 🧰 Стек

**Frontend** — `JavaScript` · `TypeScript` · `React` · `Next.js`

**Agents / LLM** — Claude Agent SDK · LangGraph · LangChain · MCP servers · RAG · context & prompt engineering · agent evals

**Backend** — Node.js · Express · PostgreSQL · Prisma · Redis · WebSockets

**Infra** — Docker · Kubernetes
