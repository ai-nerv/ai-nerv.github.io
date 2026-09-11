# ai-nerv.com

The site for [nerv](https://github.com/ai-nerv) — a coding agent for Linux, in four programs that
share no code.

The repository root is what is served. It is **generated**: edit `site/content.mjs`, then

```sh
node site/build.mjs
```

The output is committed, so GitHub Pages needs no build step. See [site/README.md](site/README.md)
for why there is a generator at all, and where the drawings come from.

| | |
|---|---|
| [magi](https://github.com/ai-nerv/magi) | the harness — UI, host, turns, tools |
| [casper](https://github.com/ai-nerv/casper) | the tools, and the screen they draw on |
| [melchior](https://github.com/ai-nerv/melchior) | the model, and the other agents |
| [balthasar](https://github.com/ai-nerv/balthasar) | memory, in its own process |
