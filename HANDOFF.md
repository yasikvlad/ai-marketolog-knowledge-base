# 🤝 HANDOFF — Если ты только что распаковал этот архив

Это база знаний продукта **AI-Маркетолог** Влада Яско. Передаётся для совместной работы.

**Версия архива:** 2026-05-18

---

## ⚠️ Сначала важное

**AI-Маркетолог ≠ AI-Ковчег.** Не путать. Это два разных продукта Влада:
- **AI-Маркетолог** — флагман, Влад делает один, ЦА: эксперты/маркетологи/предприниматели/новички. Эта база — про него.
- **AI-Ковчег** — отдельный партнёрский продукт Влада для предпринимателей и наёмных топов, где Влад соэксперт/сопродюсер. Материалы по Ковчегу — отдельно, **в этой базе их нет**.

---

## 📂 Что внутри (5-минутная экскурсия)

База устроена в **два слоя**:

### 1. Оперативные документы (корень)
Это «рабочий слой» — то, что используешь каждый день.

- [`README.md`](README.md) — карта базы, описание продукта
- [`00_overview.md`](00_overview.md) — общий контекст за 5 минут
- [`product/`](product/) — оффер, пакеты, программа курса
- [`content/`](content/) — воронка, Tone of Voice Влада
- [`landing/`](landing/) — концепция веба
- [`research/`](research/) — кейсы Потока 1: воркшопы, Q&A, стратсессии
- [`team/`](team/) — команда и процессы
- [`resources/`](resources/) — Поток 2: цены, ссылки на оплату

⚠️ Некоторые seed-документы помечены **УСТАРЕЛО** в заголовке — там старая ценовая сетка (апрель). Актуальные цены и программа — в `university/sources/src-20260518-aimarketolog-site-current/`.

### 2. База знаний (`university/`)
Это «исследовательский слой» — Zettelkasten по методологии [kkarpushin/university-template](https://github.com/kkarpushin/university-template). Сюда складываются первоисточники, проверяемые утверждения и синтезы.

- [`university/README.md`](university/README.md) — описание методологии
- [`university/INDEX.md`](university/INDEX.md) — **главный каталог** всех источников, заметок, claims
- [`university/METHODOLOGY.md`](university/METHODOLOGY.md) — правила работы (как добавлять новый источник, как писать заметки)
- [`university/TAXONOMY.md`](university/TAXONOMY.md) — дерево тем для синтезов
- [`university/sources/`](university/sources/) — первоисточники «как есть» (HTML/транскрипты + meta.yaml + conspect.md)
- [`university/notes/`](university/notes/) — атомарные заметки (одна идея = один файл)
- [`university/claims/`](university/claims/) — проверяемые утверждения с implication для продукта
- [`university/syntheses/`](university/syntheses/) — сводные документы по темам (главное для чтения)
- [`university/contradictions/`](university/contradictions/) — зафиксированные противоречия между источниками
- [`university/queue/`](university/queue/) — куда кидать новые ссылки на обработку

---

## 🎯 С чего начать чтение (20 минут)

1. **[README.md](README.md)** — карта базы (5 мин)
2. **[00_overview.md](00_overview.md)** — продукт за 5 мин
3. **[`university/syntheses/syn-offer-and-positioning.md`](university/syntheses/syn-offer-and-positioning.md)** — главные выводы по продукту и позиционированию
4. **[`university/syntheses/syn-funnel-strategy.md`](university/syntheses/syn-funnel-strategy.md)** — воронка
5. **[`university/syntheses/syn-methodology-and-content-assets.md`](university/syntheses/syn-methodology-and-content-assets.md)** — методологии + IP-активы Влада

После этого у тебя есть рабочая картина продукта.

---

## ✏️ Как продолжать работу

### Если у тебя есть Claude Code (рекомендуется)

1. Установи [Claude Code](https://claude.com/claude-code) и зайди в эту папку.
2. Скажи Claude: «прочти университетскую методологию (`university/METHODOLOGY.md`) и помоги добавить новый источник».
3. Просто кидай ему ссылки/файлы → Claude сам обработает по пайплайну (см. METHODOLOGY §4: fetch → classify → score → conspect → atomize).
4. Просматривай результаты, корректируй атомарные заметки.

### Если ты работаешь руками

1. Прочитай **[`university/METHODOLOGY.md`](university/METHODOLOGY.md)** целиком — там правила.
2. Шаблоны в **[`university/_templates/`](university/_templates/)** — копируй и заполняй.
3. После добавления источника обновляй **[`university/INDEX.md`](university/INDEX.md)** — это мастер-каталог.
4. Если нашёл противоречие — оформляй как `contradictions/contr-XXX.md`, не правь тихо.

### Что НЕ делать

- ❌ Не удалять файлы с пометкой **УСТАРЕЛО** — они нужны для tracking-а эволюции продукта
- ❌ Не путать AI-Маркетолог и AI-Ковчег (см. начало этого файла)
- ❌ Не вписывать новое знание в README напрямую — сначала источник + заметка, потом синтез
- ❌ Не игнорировать `superseded_by` — старые заметки оставлены как история, но не должны цитироваться как актуальные

---

## 📌 Главные факты о продукте (по состоянию на 2026-05-18)

- **Программа:** 9 недель × 8 модулей × 8 продуктов
- **Старт Потока II:** 18.04.26
- **Лендинг:** https://new.aimarketolog.site/
- **Пакеты:**
  - Наблюдатель $397
  - Участник $647 (SOLD OUT для Потока II)
  - Стратсессия $1 499 (9 мест)
  - Фокус-группа $2 999 (4 места)
  - Спецбронь $25
- **Гарантия:** 14 дней 100% возврат
- **Контакт:** [@vlad_yasko_ai](https://t.me/vlad_yasko_ai) (Telegram)

**Источник истины** — `university/sources/src-20260518-aimarketolog-site-current/conspect.md`.

---

## 🆕 Что нового в этом архиве (последняя сессия 2026-05-18)

Добавлены источники:
- Транскрипт вебинара-запуска Потока 2 (1 апреля, 3.5 ч)
- Конференц-преза «AI-сотрудники для личного бренда» (30 мин, [conference-deck.vercel.app](https://conference-deck.vercel.app/))
- Актуальный лендинг (snapshot 18 мая)

Добавлены заметки про формулу выступлений Влада:
- 14-блочная структура вебинара
- Live-демо на случайном зрителе как продающий механизм
- Дофаминовый ритм 30-40 мин
- Канал «Золотой дождь» для платежей
- 8-этапный каноничный пайплайн (новое vs ad-hoc)
- Конференц vs вебинар (разница механик)
- Ratcheting pricing (паттерн поднятия цен)

Помечены устаревшими: старые ценовые ноты, seed-документы с апрельской сеткой.

Зафиксировано противоречие: [`contradictions/contr-005.md`](university/contradictions/contr-005.md) — эволюция цен за 5 дней.

---

## ❓ Если что-то непонятно

- Структурные вопросы — пиши Владу в [@vlad_yasko_ai](https://t.me/vlad_yasko_ai)
- Методологические — читай [`university/METHODOLOGY.md`](university/METHODOLOGY.md)
- «А где X?» — ищи через grep по `university/INDEX.md`

---

> «Я не обучаю. Я ДЕЛАЮ в прямом эфире, а ты повторяешь.» — Влад Ясько
