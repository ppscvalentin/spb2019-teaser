# Stagii pe Bune 2019 | Teaser website

Built with Jekyll.

[Figma mockups](https://www.figma.com/proto/HH3K2yFApsmuuKpNCFJdb3VP/Stagii-pe-Bune-Teaser?node-id=16%3A2429&viewport=667%2C360%2C0.181442&scaling=min-zoom)

## Development

```
bundle exec jekyll serve
```


## Build

1. `cp _config.yml _config.production.yml`
 
2. Edit `_config.production.yml`:
    1. Set `GA-TRACKING_ID`
    2. Set `baseurl` and `url`

3. Run build: `bundle exec jekyll build --config _config.production.yml`
