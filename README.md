This utility (`rust-ctags`) is intended for use with Exuberant Ctags.
You can just clone this repo and then execution

```
> /path/to/rust-ctags src
```

and it will generate a TAGS file with the Rust language tags from `src`.

Note: the ctags definition is not perfect, but it tends to do the job.
It should probably be extended to account for newer langauge features.
PRs welcome! =)

See also:

- the [rusty tags] crate, which I've never tried, but it looks cool!

[rusty tags]: https://crates.io/crates/rusty-tags
