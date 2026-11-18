# Yueqian (Richard) Yang

Full-stack engineer for long-running LLM agents: tool design, resumable sessions, and streaming UIs on web and mobile.

Original author of [ChatVirtualizer](https://github.com/meta/astryx/pull/5461) (Lab) in Meta's Astryx design system; 4 more fixes merged into Astryx and Zed.

**Open to full-stack / AI product engineering roles** · [LinkedIn](https://www.linkedin.com/in/yangyq/) · yangyueqian1025@gmail.com

## Building

- **[Thinkite](https://github.com/thinkite/thinkite)** ([thinkite.dev](https://thinkite.dev)) — desktop & mobile GUI for OpenCode with P2P remote control. Electron + Expo. Sessions live on OpenCode's server, so desktop, iOS, and other OpenCode clients sync across reconnects; the phone reaches the desktop over iroh (QUIC); MCP tools let agents run dev servers the phone can preview on localhost.

- **[cc-mem](https://github.com/yyq1025/cc-mem)** — one memory for every coding agent: plugins for pi, OpenCode and DeepSeek Harness that read and write Claude Code's auto memory, so a note saved in one agent shows up in the others. Published on npm as `@cc-mem/*`; tool descriptions are tuned against scripted behavior runs of each agent in isolated sandboxes.

- **[ballast](https://github.com/yyq1025/ballast)** — paint-level benchmark harness and reference virtualizer for AI chat transcripts. Measures TanStack Virtual, Legend List, and others on scripted scrolling and real-device touch; every design decision in the repo traces to a number. The reference virtualizer became ChatVirtualizer in Astryx.

- **[react-native-iroh-ffi](https://github.com/yyq1025/react-native-iroh-ffi)** — React Native bindings for the official iroh-ffi: full p2p API surface, prebuilt, no Rust toolchain required.

## Upstream

15 PRs merged across 7 repos, all under human maintainer review:

- **meta/astryx** — 4: experimental [ChatVirtualizer](https://github.com/meta/astryx/pull/5461), following the transcript-scaling [RFC](https://github.com/meta/astryx/issues/4102) I authored; ChatLayout instant first-fill + instant scroll-to-bottom; reduced-motion scroll-follow; auto-follow released only by the reader

- **denoland/deno** — 4 (Rust): tray icon, hardlink write-through, `--exclude-unused-npm`, hoisted lifecycle bins

- **zed-industries/zed** — 1 (Rust): markdown preview keeps the first rendered block at the top

- **sigmaSd/deno-pty** — 3: split UTF-8 reads + raw bytes API, initial pty size, CI

- **electron-userland/electron-builder** — ULMO/lzma DMG format

- **software-mansion/enriched-markdown**, **littledivy/laufey**

## Stack

TypeScript · React · React Native (Expo) · Electron · Node.js · TanStack Router/Query/Store · OpenCode · MCP · PostgreSQL · Redis · iroh (QUIC) · Rust FFI (UniFFI) · Python
