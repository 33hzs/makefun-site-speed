# makefun-site-speed

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/33hzs/makefun-site-speed/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/33hzs/makefun-site-speed/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A fast drop-in replacement for makefun-site 1.0.0, make.fun's own static site generator: for every case it returns exactly the output tree makefun-site 1.0.0's build returns — every page, the index and tag pages, build-report.txt and each static file, byte for byte — at a fraction of the CPU time. solve.js is a dependency-free ES module written for speed (bulk escaping, first-character dispatch in the Markdown lexer, per-build slug caching, cards and pages built once); main.ts is the harness driver.

## Run it

```sh
node main.ts
```

The driver reads the cases from /input/cases.json (MAKEFUN_INPUT_DIR outside a container) and writes the answers to /output/answers.json (MAKEFUN_OUTPUT_DIR).

---

<sub>Entered on [make.fun](https://make.fun/bounty/site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
