# Dash Hero — firmware

Versões do firmware do painel Dash Hero (ESP32-S3), lidas pela atualização por
Wi-Fi do aparelho. Cada release tem `manifest.json` (versão, tamanho, SHA-256)
e `obd_dash.bin`; o painel lê sempre o release mais recente:

    https://github.com/gvn182/dash-hero-firmware/releases/latest/download/manifest.json

Publicado por `tools/release.py --github` no projeto do painel. Não edite os
arquivos de um release à mão: o SHA-256 do manifesto deixaria de bater.
