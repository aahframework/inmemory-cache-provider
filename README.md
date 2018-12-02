<p align="center">
  <img src="https://cdn.aahframework.org/assets/img/aah-logo-64x64.png" />
  <h2 align="center">Inmemory Cache Provider by aah framework</h2>
</p>
<p align="center">
  <p align="center"><a href="https://github.com/go-aah/inmemory-cache-provider/releases/latest"><img src="https://img.shields.io/badge/version-v0.1.0-blue.svg" alt="Version"></a> <a href="https://godoc.org/aahframe.work/cache/provider/inmemory"><img src="https://godoc.org/aahframe.work/cache/provider/inmemory?status.svg" alt="GoDoc"></a></p>
</p>

High performance, eviction modes (TTL, NoTTL, Slide), goroutine safe inmemory cache provider. Library keeps cache entries on heap but omits GC and without impact on performance by applying trick of [go1.5 map non-pointer values](https://github.com/golang/go/issues/9477).

### News

  * `v0.1.0` [released](https://github.com/go-aah/inmemory-cache-provider/releases/latest) and tagged on Dec 02, 2018.

## Usage

```bash
# go.mod
require aahframe.work/cache/provider/inmemory v0.1.0
```

Visit official website https://aahframework.org to learn more about `aah` framework.

## Issues

Please report issues at https://aahframework.org/issues.

## Author

[Jeevanandam M.](https://github.com/jeevatkm) (jeeva@myjeeva.com)

## License

`inmemory-cache-provider` released under MIT License.


