# hidashimora.github.io

## Зачем вообще это нужно

VPN-серверы помогают **обходить блокировки**: открывать сайты, мессенджеры и сервисы, до которых провайдер «не пускает». Конфиги подписок — это списки таких серверов. Проблема в том, что в популярных списках бывает **больше тысячи серверов**. Когда приложение пытается загрузить и обработать столько конфигов, **начинает тупить что угодно** — не из-за «слабого» железа, а просто потому что объём данных огромный. Интерфейс подвисает, список грузится вечность, приложение может вылетать.

Здесь лежат **укороченные подписки**: для каждого из 26 списков [goida-vpn-configs](https://github.com/AvenCores/goida-vpn-configs) свой файл с примерно **четвертью** серверов. Меньше конфигов — меньше нагрузка, всё работает плавно. Списки обновляются **сами** (раз в час и при каждом пуше в репозиторий). Вручную ничего править не нужно.

---

## Наши подписки (1/4 серверов, без лагов)

Для каждого номера 1–26 — свой файл: в нём примерно четверть конфигов из соответствующего списка goida-vpn-configs (берётся каждая 4‑я строка с vless/trojan/vmess/ss/hy2).

- **vpn.txt** — то же, что 26.txt (удобная ссылка для списка «Обход SNI/CIDR»).  
  Сайт: https://hidashimora.github.io/vpn.txt  
  Raw: `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/vpn.txt`

**Все 26 укороченных списков (raw):**

| № | Ссылка (1/4 серверов) |
|---|------------------------|
| 1 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/1.txt` |
| 2 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/2.txt` |
| 3 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/3.txt` |
| 4 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/4.txt` |
| 5 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/5.txt` |
| 6 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/6.txt` |
| 7 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/7.txt` |
| 8 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/8.txt` |
| 9 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/9.txt` |
| 10 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/10.txt` |
| 11 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/11.txt` |
| 12 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/12.txt` |
| 13 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/13.txt` |
| 14 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/14.txt` |
| 15 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/15.txt` |
| 16 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/16.txt` |
| 17 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/17.txt` |
| 18 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/18.txt` |
| 19 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/19.txt` |
| 20 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/20.txt` |
| 21 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/21.txt` |
| 22 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/22.txt` |
| 23 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/23.txt` |
| 24 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/24.txt` |
| 25 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/25.txt` |
| 26 | `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/main/26.txt` |

---

## Быстрый старт

1. Скопируй ссылку на подписку (выше).
2. Открой свой VPN-клиент и добавь подписку по этой ссылке (подписка / subscription / импорт по URL).
3. Дождись обновления списка, при желании проверь пинг по серверам.
4. Выбери сервер и подключайся.

Дальше — короткие гайды по платформам.

---

## Гайды по установке

### Android

- Ставишь **v2rayNG** (или другой клиент вроде NekoRay, Hiddify).
- В приложении: меню → добавить подписку → вставляешь нашу ссылку (или «импорт из буфера», если ссылку скопировал).
- Обнови подписку (кружок со стрелкой в группах), при необходимости запусти проверку пинга и отсортируй по задержке.
- Выбираешь сервер, жмёшь «подключиться». Если не подхватило — попробуй другой сервер из списка или обнови подписку ещё раз.

### Windows / Linux

- Клиент на выбор: **Throne**, **NekoRay**, **v2rayN** и т.п.
- Добавляешь подписку: «Профили» → «Добавить из URL/буфера» → вставляешь ссылку.
- Можно прогнать тест задержки и выбрать сервер с минимальным пингом.
- Включаешь VPN и пользуешься.

### iOS / iPadOS

- Ставишь, например, **V2Box** (V2ray Client).
- Вкладка «Config» → плюс → «Добавить подписку»: любое название и наша ссылка в поле URL.
- После загрузки выбираешь сервер и нажимаешь «Подключиться».

### macOS

- **Hiddify** или другой клиент.
- «Новый профиль» или «Добавить из буфера» → вставляешь ссылку на подписку.
- Дальше — выбор сервера и включение VPN в настройках.

Если что-то не подключается — проверь, что подписка обновилась, и попробуй другой сервер из списка; часть нодов может быть временно недоступна.

---

## Все 26 списков goida-vpn-configs (полные)

Если нужен **полный** список серверов (все тысячи), можно брать ссылки напрямую из [AvenCores/goida-vpn-configs](https://github.com/AvenCores/goida-vpn-configs). Имей в виду: с большим количеством серверов приложение может тормозить — тогда и пригодится наша укороченная подписка выше.

| № | Описание | Ссылка |
|---|----------|--------|
| 1 | OpenRay | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/1.txt |
| 2 | 5ubscrpt10n | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/2.txt |
| 3 | proxy-minging | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/3.txt |
| 4 | AutoVPN | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/4.txt |
| 5 | V2RayCFGDumper | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/5.txt |
| 6 | openproxylist | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/6.txt |
| 7 | v2ray-configs | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/7.txt |
| 8 | cid-vpn-config | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/8.txt |
| 9 | telegram-v2ray-configs-collector | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/9.txt |
| 10 | .proxy | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/10.txt |
| 11 | V2rayCollector | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/11.txt |
| 12 | .proxy | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/12.txt |
| 13 | config | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/13.txt |
| 14 | Mineral | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/14.txt |
| 15 | Config-Collector | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/15.txt |
| 16 | Free-servers | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/16.txt |
| 17 | V2rayCollector_Py | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/17.txt |
| 18 | v2ray | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/18.txt |
| 19 | V2rayCollector | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/19.txt |
| 20 | Proxy-List | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/20.txt |
| 21 | kamaji | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/21.txt |
| 22 | xray-config-toolkit | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/22.txt |
| 23 | Xray | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/23.txt |
| 24 | STRUGOV | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/24.txt |
| 25 | V2RayConfig | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/25.txt |
| 26 | Обход SNI/CIDR | https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/26.txt |

Рекомендуемые в оригинальном репо: 1, 6, 22, 23, 24, 25. Список 26 — под обход SNI/CIDR (белые списки).

---

## Как устроено автообновление

В этом репозитории за всё отвечает **GitHub Actions**: при пуше в `main` и по расписанию раз в час workflow качает исходный список (26.txt), выкидывает всё кроме строк с конфигами (vless, trojan, vmess, ss, hy2), берёт каждую 4‑ю строку и пишет результат в `vpn.txt`. Свой сервер и PHP не нужны — всё на GitHub.
