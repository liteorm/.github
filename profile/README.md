<div align="center">

<img src="logo.png" alt="LiteORM" width="128" />

# LiteORM

### A typed query builder and a declarative ORM over one CGo-free core

[**Documentation**](https://liteorm.com) &nbsp;·&nbsp; [**Get started**](https://liteorm.com/docs/getting-started/) &nbsp;·&nbsp; [**API reference**](https://pkg.go.dev/liteorm.org) &nbsp;·&nbsp; [**Source**](https://github.com/go-again/liteorm)

</div>

---

LiteORM is *lite* because it's **modern**, not minimal — built from a clean Go
baseline (generics, `iter.Seq2`, `log/slog`, CGo-free pure-Go SQLite) instead of a
decade-old codebase patched a thousand times. One library gives you an explicit
`query` builder *and* a declarative `orm` over the **same** core — same backends,
same transaction, same normalized errors — across SQLite, Postgres, MySQL & SQL Server.

```sh
go get liteorm.org
```

|   |   |
|---|---|
| 🧩 **Two paradigms, one core** | a typed `query` builder and a declarative `orm` share one Session, dialect, scanner & errors — no library lock-in |
| ⚡ **Modern & lean** | generics-first, no hot-path reflection; CGo-free pure-Go SQLite; a driver-free core, one module per backend |
| 🤖 **Built for agents** | an embedded studio with **AI built in** (English → SQL), plus shipped Agent Skills + `AGENTS.md` |
| 🎯 **Safe by default** | N+1-safe eager loading, tri-state soft-delete, normalized errors on every backend, codegen on-ramps |

<div align="center">

**[Explore the docs →](https://liteorm.com)**

</div>
