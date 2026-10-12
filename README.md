# Awesome Turkish MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated [Model Context Protocol](https://modelcontextprotocol.io) servers for Turkish data and domains — so an AI agent can reach Turkish legal, financial, government, academic and business sources through typed, auditable tools.

🇹🇷 Türkçesi: [README.tr.md](README.tr.md)

Most of the world's MCP servers wrap English-language, global sources. Turkish institutions — the courts, `mevzuat.gov.tr`, Borsa İstanbul, EKAP, TÜRKPATENT, YÖK — publish data an agent can genuinely use, but only if someone maps it to tools. This list collects the servers that do, so you can find them in one place instead of rediscovering them one search at a time.

All entries are open source and, unless noted, run locally (stdio). Contributions welcome — see [Contributing](#contributing).

## Contents

- [Legal & Legislation](#legal--legislation)
- [Government & Public Records](#government--public-records)
- [Finance & Markets](#finance--markets)
- [Academic & Research](#academic--research)
- [Business & ERP](#business--erp)
- [Weather](#weather)
- [Related Tools & Libraries](#related-tools--libraries)
- [Contributing](#contributing)

## Legal & Legislation

- [yargi-mcp](https://github.com/saidsurucu/yargi-mcp) - Search Turkish courts and legal databases — Yargıtay, Danıştay, Anayasa Mahkemesi, Sayıştay, KVKK and more — as structured tools.
- [mevzuat-mcp](https://github.com/saidsurucu/mevzuat-mcp) - Search and read current Turkish legislation from `mevzuat.gov.tr`.

## Government & Public Records

- [ihale-mcp](https://github.com/saidsurucu/ihale-mcp) - Query Turkish public procurement tenders from the EKAP portal.
- [markapatent-mcp](https://github.com/saidsurucu/markapatent-mcp) - Search TÜRKPATENT trademarks, patents and industrial designs.

## Finance & Markets

- [borsa-mcp](https://github.com/saidsurucu/borsa-mcp) - Borsa İstanbul (BIST) equities, mutual funds, FX and macro data, alongside US markets and crypto.
- [ekonomikosesi-mcp](https://ekonomikosesi.com/api/mcp) (remote Streamable HTTP) — Free, read-only MCP server providing access to Turkish news, front-page newspaper archives, Borsa İstanbul (BIST), and TEFAS fund data.

## Academic & Research

- [yokatlas-mcp](https://github.com/saidsurucu/yokatlas-mcp) - Query YÖK Atlas — Turkish university programs, placement scores and quotas.
- [yoktez-mcp](https://github.com/saidsurucu/yoktez-mcp) - Search the Turkish national thesis center (YÖK Tez).
- [literatur-mcp](https://github.com/saidsurucu/literatur-mcp) - Search and analyze Turkish academic journal articles from DergiPark.

## Business & ERP

- [erp-report-engine](https://github.com/gulmezeren2-byte/erp-report-engine) - Read-only access to the SQL database behind an ERP (Logo Tiger, Netsis, Mikro): the agent queries canonical entities through a statement-checking guard, measured against a public 28-attack benchmark.

## Weather

- [MCP-Turkey-Weather](https://github.com/emredeveloper/MCP-Turkey-Weather) - Weather data for locations in Turkey.

## Related Tools & Libraries

Agent-facing CLIs, skills and libraries in the same ecosystem — not MCP servers themselves, but built for the same job.

- [yargi-cli](https://github.com/saidsurucu/yargi-cli) - Command-line access to Turkish legal databases, designed for AI agents.
- [borsapy](https://github.com/saidsurucu/borsapy) - Python library for Turkish financial markets (BIST stocks, funds, FX).
- [turkce-imla-skill](https://github.com/saidsurucu/turkce-imla-skill) - Claude skill for comprehensive Turkish spelling and grammar.
- [markapatent-skill](https://github.com/saidsurucu/markapatent-skill) - Claude skill for TÜRKPATENT search via Claude-in-Chrome.
- [trdizin-skill](https://github.com/saidsurucu/trdizin-skill) - Claude skill for searching the TR Dizin academic index.

## Contributing

Found or built a Turkish-domain MCP server that belongs here? [Open a pull request](CONTRIBUTING.md). The bar is simple: it should be open source, work, and serve Turkish data or a Turkish domain.

Much of the ecosystem above was built by [@saidsurucu](https://github.com/saidsurucu) — this list stands on that work.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
