# Offline Tierlist Maker

This is a fork
of [<img src="https://github.com/MP3Martin/tiers-fork/assets/60501493/551ecd17-be63-4309-b66f-245f433462e1" alt="gh" width="18"/>](https://github.com/silverweed/tiers)
**[silverweed/tiers](https://github.com/silverweed/tiers)**.

## Added features

### Query parameters

| Parameter | Type    | Default value | Description                                                         |
|-----------|---------|---------------|---------------------------------------------------------------------|
| `url`     | string  | null          | Loads and automatically imports the config from a URL on page load. |
| `lock`    | boolean | false         | Makes the page readonly, for display.                               |
| `note`    | string  | null          | Shows additional text under the tierlist title.                     |

> [!IMPORTANT]  
> Query parameter values with the string type must be formatted
> using [URL Encoding](https://www.urlencoder.io/)

## Examples

- https://mp3martin.github.io/tiers-fork/?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fmp3martin%2Fpublic-assets%40a77f7ee%2Ftierlists%2Ftest1.json&lock=1&note=Good%20game
