# CoreForge Collector 2

Auto-updated subscription of **speed-ranked, live-tested** proxy configs, limited to the three transport families that stay reachable under heavy filtering:

- **CDN-fronted** — WebSocket / XHTTP behind Cloudflare or Fastly edge IPs
- **Shadowsocks** — plain, no SNI to fingerprint
- **Reality** — VLESS / Trojan with real-TLS camouflage

Every config is name-tagged `<flag> CoreForge Collector 2 NNN`, where the flag is the exit country and `NNN` is the speed rank (`001` = fastest).

## Subscribe

| Format | File |
|--------|------|
| Base64 (v2rayNG / Xray / Hiddify / sing-box) | [`subscription_base64.txt`](subscription_base64.txt) |
| Plaintext | [`subscription_raw.txt`](subscription_raw.txt) |

Subscription URL:

```
https://raw.githubusercontent.com/paranoideveloper/CoreForge-Collector2/main/subscription_base64.txt
```

Rebuilt automatically every 2 hours. Configs are aggregated from public sources and each is verified with a live download test and ranked by throughput before publishing.
