# India Public Holidays

> Gazetted holidays, restricted holidays, and bank holidays for current and future years

**Category:** india-ref · **Data:** Ministry of Personnel open notification · **License:** public-domain · **Updates:** yearly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/holidays/{year}.json` | JSON |
| `/data/holidays/current.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/india-holidays/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/india-holidays/data.json');
const data = await res.json();
```

## Data

- Source: Ministry of Personnel open notification
- License: public-domain
- Last updated: `2026-08-25T02:26:41.073Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/india-holidays/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

public-domain
