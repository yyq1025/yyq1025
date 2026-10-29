# Yueqian (Richard) Yang



Full-stack engineer building LLM agents from React UIs down to Node services, queues, and wire protocols.

Designs by hand, builds with agents, verifies by benchmark.



**Open to full-stack / AI product engineering roles** · [LinkedIn](https://www.linkedin.com/in/yangyq/) · yangyueqian1025@gmail.com



## Building



- **[Thinkite](https://github.com/thinkite/thinkite)** — desktop & mobile GUI for Claude Code with P2P remote control. Electron + Expo, resumable streaming protocol over the Claude Agent SDK, phone ↔ daemon transport on iroh (QUIC).

- **[cc-mem](https://github.com/yyq1025/cc-mem)** — one memory for every coding agent: plugins for pi, OpenCode and DeepSeek Harness that read and write Claude Code's auto memory, so a note saved in one agent shows up in the others. Published on npm as `@cc-mem/*`; tool descriptions are tuned against scripted behavior runs of each agent in isolated sandboxes.

- **[ballast](https://github.com/yyq1025/ballast)** — paint-level benchmark harness and reference virtualizer for AI chat transcripts. Measures TanStack Virtual, Legend List, and others on scripted scrolling and real-device touch; every design decision in the repo traces to a number.

- **[react-native-iroh-ffi](https://github.com/yyq1025/react-native-iroh-ffi)** — React Native bindings for the official iroh-ffi: full p2p API surface, prebuilt, no Rust toolchain required.



## Upstream



12 PRs merged across 6 repos, all under human maintainer review:



- **denoland/deno** — 4 (Rust): tray icon, hardlink write-through, `--exclude-unused-npm`, hoisted lifecycle bins

- **meta/astryx** — 2: ChatLayout instant first-fill + instant scroll-to-bottom, reduced-motion follow-up; open: transcript-scaling [RFC](https://github.com/meta/astryx/issues/4102) and touch-first [ChatVirtualizer](https://github.com/meta/astryx/pull/5461)

- **electron-userland/electron-builder** — ULMO/lzma DMG format

- **software-mansion/enriched-markdown**, **littledivy/laufey**, **sigmaSd/deno-pty**



## Stack



TypeScript · React · React Native (Expo) · Electron · Node.js · TanStack Router/Query/DB · PostgreSQL · Redis · iroh (QUIC) · Rust FFI (UniFFI) · Python
