# hidashimora.github.io

## VPN подписка (всё автоматически)

Ничего вручную добавлять не нужно. Достаточно **запушить этот репозиторий на GitHub** — workflow сам подтянет конфиги и заполнит `vpn.txt`. Дальше список обновляется **каждый час** сам.

- **При пуше** на ветку `main` — сразу запускается обновление.
- **По расписанию** — раз в час.
- PHP и JS не нужны: всё делает GitHub Actions.

**Ссылка для VPN (подписка):**  
https://hidashimora.github.io/vpn.txt  

(или raw: `https://raw.githubusercontent.com/hidashimora/hidashimora.github.io/refs/heads/main/vpn.txt`)

В подписке примерно **1/4** конфигов из [исходного списка](https://raw.githubusercontent.com/AvenCores/goida-vpn-configs/refs/heads/main/githubmirror/26.txt).