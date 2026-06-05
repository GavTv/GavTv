<div align="center">

# AI Fullstack Engineer

**Строю агентные системы, которые доходят до продакшена.**

*Production LLM-агенты под ключ — React-фронтенды, Node-бэкенды, multi-agent orchestration, tool/MCP integration и harness engineering, который делает агентов надёжными, наблюдаемыми и достаточно дешёвыми для масштаба.*

Не «демо-чатбот», а **автономный воркер с бюджетом.**

</div>

---

### Результаты

| | |
|:---|:---|
| 🤖 **Concierge agent** | Совместно собрал агента, который сам закрывает **~70%** месячной нагрузки premium concierge-команды |
| 🏨 **Hotel price reader** | Читает актуальные цены номеров с любого сайта отеля за **~3¢** за запрос — после оптимизации стоимость упала в **26.5×** без потери качества |

---

### Сейчас

| | |
|:---|:---|
| 🔭 | Строю агентную автоматизацию для premium concierge-сервиса |
| 🌱 | Углубляюсь в context engineering, agent evaluation и cost optimization |
| ⚡ | Ежедневно — AI-driven разработка в **5–10** параллельных agent sessions |
| 💬 | Спрашивайте про **Claude Agent SDK**, **LangGraph**, **MCP** или как выжать **26×** из agent pipeline |

---

## 🔬 Исследования и эксперименты

### 📊 agent-regression-bench

*Evaluation harness + cost study*

> Как понять, что правка промпта тихо не сломала прод? Запускаешь bench. **240 scripted agent tasks** — tool-use, retrieval, multi-step workflows — pass rate, latency и token spend на каждый сценарий.

Сократил eval loop с **~45 мин ручных spot-checks** до **6 мин автоматических прогонов** — каждый эксперимент честный: меняешь одну переменную, перезапускаешь, сравниваешь дельты. Один проход context compression срезал среднюю стоимость сессии в **18×** при **97%** task pass rate.

`Node.js` · `TypeScript` · `Claude Agent SDK` · `LangGraph` · `PostgreSQL`

---

## 🧰 Стек

<table>
<tr>
<td valign="top" width="33%">

**Frontend**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

</td>
<td valign="top" width="33%">

**Agents / LLM**

Claude Agent SDK · LangGraph · LangChain · MCP servers · RAG · context & prompt engineering · agent evals

</td>
<td valign="top" width="33%">

**Backend & Infra**

Node.js · Express · PostgreSQL · Prisma · Redis · WebSockets · Docker · Kubernetes

</td>
</tr>
</table>

---

<div align="center">

<sub>Fullstack-приложения. Агентное ядро. Продакшен-бюджеты.</sub>

</div>
