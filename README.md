# AIUIOG v4.0

**Owner:** Коваль Дмитрий Николаевич  
**Co-owner:** Коваль Елизавета Валерьевна  
**GitHub:** https://github.com/Lovexan369/AIUIOG-v4.0

Мультиагентная AI-система на базе Claude Managed Agents, OpenClaw и XOS.

---

## Агенты

| Агент | Тариф | Скилы |
|-------|-------|-------|
| Coordinator | Free | — |
| Engineer | Free | xlsx, skill_ci_pipelines, ECC, turbo-console-log |
| Content | Free | — |
| Research | Pro | — |
| QA/DevOps | Pro | skill_ci_pipelines |
| Julio | Family | — |

---

## Быстрый старт

### Replit
1. Clone: `git clone https://github.com/Lovexan369/AIUIOG-v4.0.git`
2. Secrets: `ANTHROPIC_API_KEY`, `TELEGRAM_BOT_TOKEN`
3. Run

### Docker
```bash
git clone https://github.com/Lovexan369/AIUIOG-v4.0.git
cd AIUIOG-v4.0
docker-compose up -d
```

### Локально
```bash
pip install -r requirements.txt
python deploy.py
python main.py
```

---

## Деплой агентов
```bash
python deploy.py
```

---

## OpenClaw каналы
- TELEGRAM_BOT_TOKEN (включён)
- WHATSAPP_TOKEN
- SLACK_BOT_TOKEN
- DISCORD_BOT_TOKEN

---

## Тарифы
- **Free** — Coordinator, Engineer, Content
- **Pro** — + Research, QA/DevOps
- **Family/Team** — все агенты включая Julio
- **Enterprise** — кастомные агенты, XOS, SLA

См. также `CHAT_SUMMARY.md` — полное резюме проекта.
