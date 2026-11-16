# PDA-темы BandaStation

Коллекция тем PDA для [Primera](https://github.com/SpaceStation220/Primera), работающих через стандартную систему TGUI/Themeify без дополнительной игровой логики.

## Доступные темы

| Тема                  | Идентификатор      | Оформление                                                     |
| --------------------- | ------------------ | -------------------------------------------------------------- |
| ТСФ                   | `TSF`              | Синий и жёлтый, объёмные кнопки, CRT-фактура                   |
| КССП                  | `KSSP`             | Графит, бордовые акценты, металлические элементы               |
| Скреллианская Империя | `SKRELLIAN_EMPIRE` | Тёмная бирюза, мягкие блики, закруглённые элементы             |
| Республика Элизиум    | `ELYSIUM`          | Зелёная и золотая палитра, неоготический ретрофутуризм         |
| Вольные секторы       | `FREEDOM`          | Тёплый индустриальный ретрофутуризм, медь, механические детали |

## Структура репозитория

- `tgui/packages/tgui/styles/themes/` — стили SCSS.
- `tgui/packages/tgui/styles/assets/` — эмблемы SVG.
- `tgui/packages/tgui/index.tsx` — подключения стилей в TGUI.
- `code/__DEFINES/modular_computer.dm` — идентификаторы, отображаемые названия и списки тем.
- `screanshots/` — скриншоты интерфейса для каждой темы.

## Установка

Для добавления тем в BandaStation перенесите необходимые SCSS и SVG в соответствующие каталоги TGUI, затем добавьте импорты стилей и определения тем в актуальные `index.tsx` и `modular_computer.dm`. Не заменяйте эти файлы целиком без сверки с текущей версией BandaStation.

## Скриншоты

Скриншоты сделаны в игре 16 ноября 2026 года. Нажмите на название темы, чтобы раскрыть галерею.

<details>
<summary><strong>ТСФ</strong></summary>

### Главное меню

<img src="screanshots/%D0%A2%D0%A1%D0%A4/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121609.png" alt="ТСФ — Главное меню" width="420">

### Chat Client — первый снимок

<img src="screanshots/%D0%A2%D0%A1%D0%A4/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121615.png" alt="ТСФ — Chat Client — первый снимок" width="420">

### Notepad

<img src="screanshots/%D0%A2%D0%A1%D0%A4/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121642.png" alt="ТСФ — Notepad" width="420">

### Chat Client — второй снимок

<img src="screanshots/%D0%A2%D0%A1%D0%A4/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121651.png" alt="ТСФ — Chat Client — второй снимок" width="420">

### BotKeeper

<img src="screanshots/%D0%A2%D0%A1%D0%A4/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121702.png" alt="ТСФ — BotKeeper" width="420">

</details>

<details>
<summary><strong>КССП</strong></summary>

### Themeify

<img src="screanshots/%D0%9A%D0%A1%D0%A1%D0%9F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121520.png" alt="КССП — Themeify" width="420">

### Direct Messenger

<img src="screanshots/%D0%9A%D0%A1%D0%A1%D0%9F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121526.png" alt="КССП — Direct Messenger" width="420">

### Software Hub

<img src="screanshots/%D0%9A%D0%A1%D0%A1%D0%9F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121539.png" alt="КССП — Software Hub" width="420">

### Chat Client

<img src="screanshots/%D0%9A%D0%A1%D0%A1%D0%9F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121558.png" alt="КССП — Chat Client" width="420">

</details>

<details>
<summary><strong>Скреллианская Империя</strong></summary>

### Themeify

<img src="screanshots/%D0%A1%D0%BA%D1%80%D0%B5%D0%BB%D0%BB%D0%B8%D0%B0%D0%BD%D1%81%D0%BA%D0%B0%D1%8F%20%D0%98%D0%BC%D0%BF%D0%B5%D1%80%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121413.png" alt="Скреллианская Империя — Themeify" width="420">

### Direct Messenger

<img src="screanshots/%D0%A1%D0%BA%D1%80%D0%B5%D0%BB%D0%BB%D0%B8%D0%B0%D0%BD%D1%81%D0%BA%D0%B0%D1%8F%20%D0%98%D0%BC%D0%BF%D0%B5%D1%80%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121426.png" alt="Скреллианская Империя — Direct Messenger" width="420">

### Software Hub

<img src="screanshots/%D0%A1%D0%BA%D1%80%D0%B5%D0%BB%D0%BB%D0%B8%D0%B0%D0%BD%D1%81%D0%BA%D0%B0%D1%8F%20%D0%98%D0%BC%D0%BF%D0%B5%D1%80%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121442.png" alt="Скреллианская Империя — Software Hub" width="420">

### Lifeline

<img src="screanshots/%D0%A1%D0%BA%D1%80%D0%B5%D0%BB%D0%BB%D0%B8%D0%B0%D0%BD%D1%81%D0%BA%D0%B0%D1%8F%20%D0%98%D0%BC%D0%BF%D0%B5%D1%80%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121450.png" alt="Скреллианская Империя — Lifeline" width="420">

### Shopping Network

<img src="screanshots/%D0%A1%D0%BA%D1%80%D0%B5%D0%BB%D0%BB%D0%B8%D0%B0%D0%BD%D1%81%D0%BA%D0%B0%D1%8F%20%D0%98%D0%BC%D0%BF%D0%B5%D1%80%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121505.png" alt="Скреллианская Империя — Shopping Network" width="420">

</details>

<details>
<summary><strong>Республика Элизиум</strong></summary>

### Главное меню

<img src="screanshots/%D0%A0%D0%B5%D1%81%D0%BF%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%20%D0%AD%D0%BB%D0%BB%D0%B8%D0%B7%D0%B8%D1%83%D0%BC/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121320.png" alt="Республика Элизиум — Главное меню" width="420">

### Software Hub — до загрузки

<img src="screanshots/%D0%A0%D0%B5%D1%81%D0%BF%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%20%D0%AD%D0%BB%D0%BB%D0%B8%D0%B7%D0%B8%D1%83%D0%BC/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121327.png" alt="Республика Элизиум — Software Hub — до загрузки" width="420">

### Software Hub — загрузка

<img src="screanshots/%D0%A0%D0%B5%D1%81%D0%BF%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%20%D0%AD%D0%BB%D0%BB%D0%B8%D0%B7%D0%B8%D1%83%D0%BC/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121334.png" alt="Республика Элизиум — Software Hub — загрузка" width="420">

### Security Records

<img src="screanshots/%D0%A0%D0%B5%D1%81%D0%BF%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%20%D0%AD%D0%BB%D0%BB%D0%B8%D0%B7%D0%B8%D1%83%D0%BC/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121343.png" alt="Республика Элизиум — Security Records" width="420">

### Themeify

<img src="screanshots/%D0%A0%D0%B5%D1%81%D0%BF%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%20%D0%AD%D0%BB%D0%BB%D0%B8%D0%B7%D0%B8%D1%83%D0%BC/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121417.png" alt="Республика Элизиум — Themeify" width="420">

</details>

<details>
<summary><strong>Вольные секторы</strong></summary>

### Themeify

<img src="screanshots/%D0%92%D0%BE%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D1%81%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121208.png" alt="Вольные секторы — Themeify" width="420">

### Главное меню

<img src="screanshots/%D0%92%D0%BE%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D1%81%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121215.png" alt="Вольные секторы — Главное меню" width="420">

### Software Hub

<img src="screanshots/%D0%92%D0%BE%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D1%81%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121225.png" alt="Вольные секторы — Software Hub" width="420">

### Lifeline

<img src="screanshots/%D0%92%D0%BE%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D1%81%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121235.png" alt="Вольные секторы — Lifeline" width="420">

### Shopping Network

<img src="screanshots/%D0%92%D0%BE%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D1%81%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-16%20121250.png" alt="Вольные секторы — Shopping Network" width="420">

</details>
