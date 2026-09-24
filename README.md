# Chess 3D Experience

A small Three.js monorepo containing two independent chess experiences.

## Apps

### Nocturne Chess

An interactive 3D chessboard with tournament-standard move rules.

- Source: `apps/nocturne-chess/dist/index.html`
- Live site: https://nocturne-chess-3d.huyhaoanh6.chatgpt.site

### Bilbao Masters Replay

An animated 3D replay of Magnus Carlsen vs Hikaru Nakamura at the 2016 Bilbao Masters Final.

- Source: `apps/bilbao-masters-replay/dist/index.html`
- Live site: https://bilbao-masters-replay-2016.huyhaoanh6.chatgpt.site

## Run locally

Serve either app's `dist` directory with a static HTTP server. For example:

```bash
python -m http.server 4186 --directory apps/bilbao-masters-replay/dist
```

Each app keeps its own `.openai/hosting.json`, so they remain separate Sites deployments even though their source is stored in one repository.
