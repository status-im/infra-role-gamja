# Description

This role builds and deploys [Gamja](https://git.sr.ht/~emersion/gamja), a basic IRC Web UI.

# Configuration

Minimal required configuration consists of just specifying thes server:
```
gamja_config_url: 'wss://{{ ergo_server_name }}:{{ ergo_cont_wss_port }}'
```
