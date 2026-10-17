# Cześć, tu Zbigniew 👋

Buduję **automatyzacje i aplikacje z AI**, które zdejmują z ludzi powtarzalną pracę —
od workflow w n8n i botów na Telegramie, po aplikacje SaaS w Django z integracją Claude i OpenAI.

🌐 **Portfolio:** [nexuslab.pl](https://nexuslab.pl) · ✉️ **Kontakt:** [kontakt@nexuslab.pl](mailto:kontakt@nexuslab.pl)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bots-26A5E4?logo=telegram&logoColor=white)

---

## 🚀 Projekty

### [Flowmail](https://panelgw.com) — asystent AI i CRM dla doradców sprzedaży
Z krótkiej notatki (także głosowej) generuje spersonalizowany mail w ~30 sekund — na podstawie
historii klienta i bazy 3 700+ materiałów branżowych. Drugi model AI weryfikuje treść, doradca
zatwierdza i wysyła. SaaS z planami i limitami dla wielu doradców.
`Django` `Claude API` `RAG / Qdrant` `OpenAI Embeddings` `Whisper` `Docker`
<sub>Kod prywatny — projekt komercyjny.</sub>

### [Gratka Alerts](https://gratka.nexuslab.pl) — monitoring ofert nieruchomości · [kod](https://github.com/zbigniew-szafranski/NexusLab)
Wielodostępowy system: użytkownik ustawia kryteria, scraper w n8n co godzinę przeszukuje
Gratka.pl, deduplikuje oferty i wysyła powiadomienia email. Trial 7 dni i plany subskrypcyjne.
`Django` `PostgreSQL` `n8n` `Celery` `HTMX` `Tailwind CSS`

### [sprzedajm.pl](https://sprzedajm.pl) — lejek sprzedażowy dla firmy nieruchomościowej
Jednostronicowy landing z routingiem intencji (skup / pośrednictwo), 3-krokowym quizem wyceny,
danymi strukturalnymi JSON-LD i agentem AI generującym plan postów na FB i IG.
`HTML/CSS/JS` `PHP` `Python` `Claude API`
<sub>Kod prywatny — projekt dla klienta.</sub>

## ⚙️ Automatyzacje n8n

| Automatyzacja | Co robi | Stack |
|---|---|---|
| **Asystent wydatków** | Bot na Telegramie: głosówka, zdjęcie paragonu albo tekst → AI wyciąga kwotę i kategorię → wpis w Google Sheets | n8n, Whisper, GPT-4o-mini (vision), Google Sheets |
| **Lista zakupów** | Wspólna lista dla domowników sterowana tekstem i głosem, z autoryzacją i cotygodniowym przypomnieniem | n8n, Telegram, Whisper, Google Tasks |
| **Sekretarka farmaceuty** | Asystent głosowy AI odbiera telefon, workflow loguje rozmowę i wysyła SMS, gdy trzeba oddzwonić | n8n, Twilio, Google Sheets |

Więcej — ze zrzutami ekranu i opiniami użytkowników — na **[nexuslab.pl](https://nexuslab.pl)**.
