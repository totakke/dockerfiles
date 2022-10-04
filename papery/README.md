# Papery

Static site generator with Jinja2 templates and structured content in Markdown,
YAML, and JSON

This is an unofficial image for [papery](https://github.com/withletters/papery).

## Supported Tags

- [`0.5.0`, `latest`](0.5/Dockerfile)
- [`0.1.10`](0.1/Dockerfile)

## Usage

```
docker pull totakke/papery
docker run -v [/path/to/site]:/papery -p 80:8000 totakke/papery run
```

You can now open your site via port 80.
