# Marple

Browser-driven explorer for lucene indexes

This is an unofficial image for [Marple](https://github.com/flaxsearch/marple).

## Usage

```sh
docker pull totakke/marple
docker run -v [/path/to/lucene/index]:/index -p 80:8080 totakke/marple
```

You can now open Marple via port 80.
