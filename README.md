# OSS alternative index

Snapshots of the open-source alternatives we track for two reference sites.

- SwapToSaaS: https://swaptosaas.com/
- SwapToMartech: https://swaptomartech.com/

This is a compiled index, not a paper and not a live API. Prices, deploy ratings, and self-host cost figures are our snapshots. Check the upstream project before you rely on a number.

## What is included

`swaptosaas/`

- `oss.json` — 62 open-source projects and the SaaS products they are compared with
- `saas.json` — the commercial products in that comparison
- `github_metrics.json` — GitHub REST API snapshot
- `hn_mentions.json` — Hacker News story titles and links, via HN Algolia
- `reddit_mentions.json` — public Reddit post titles and links

`swaptomartech/`

- `oss.json`, `saas.json`, `github_metrics.json` — the same kind of index for marketing tools

## What is not included

Affiliate links, search-keyword lists, internal scoring notes, and raw scrape logs stay out of this repository.

## Sources

- GitHub REST API, unauthenticated public repository metadata
- HN Algolia (`https://hn.algolia.com/`)
- Public Reddit post titles and permalinks

Each metrics file has its own `snapshot_utc` or `source_updated` field. These files are not refreshed from this repository.

## License

CC BY 4.0. See `LICENSE`. Attribute Weisung Technology Ltd and link the site the table came from.
