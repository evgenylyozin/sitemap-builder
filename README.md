# Sitemap builder

Builds a sitemap for a given website

- param url is used to give the builder the starting point to build a sitemap from
- param depth is used to tell the builder to stop when the specified number of consecuetive jumps from link to link is met (3 is the default)

## Usage examples

To build a sitemap with max depth of 3 and on the default target:

```bash
go run . > sitemap.xml
```

To build a sitemap with max depth of 1 and on the specified target:

```bash
go run . -url https://github.com -depth 1 > sitemap.xml
```
