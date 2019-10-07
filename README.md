# github-stats
[![GitHub Release Date](https://img.shields.io/github/release-date/spenserblack/github-stats-rs)](https://github.com/spenserblack/github-stats-rs/releases/latest)

A tool to get stats from Github

```rust
use github_stats::Repo;

let repo = Repo::new("rust-lang", "rust");

match repo {
    Ok(repo) => {/* Do some stuff */},
    Err(e) => eprintln!(":("),
}
```
