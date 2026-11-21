# fetch-retry

A tiny dependency-free wrapper around `fetch` that retries transient failures with exponential backoff and jitter.

## Usage

```bash
node example.js
```

## API

```js
const data = await fetchWithRetry(url, options, {
  retries: 2, baseDelay: 250,
});
```
## License

MIT

## Notes

The project is kept deliberately minimal.
