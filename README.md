# template-deno


## run

```sh
deno run --check src/index.ts
```


## lintについて
> lint 目的で使う場合、 deno.enable: true しない。これを有効にすると、依存の解決のルールが deno になってしまい (LSPが乗っ取られる)、node とは非互換になる。
> というわけで format だけ有効にしておく。このとき、 prettier 拡張が入ってると競合するので、 vscode の拡張管理から disable(workspace) する。
> [node プロジェクトでも deno lint | deno fmt する](https://zenn.dev/mizchi/articles/just-lint-by-deno)


prettierとの競合注意


## 参考
- [node プロジェクトでも deno lint | deno fmt する](https://zenn.dev/mizchi/articles/just-lint-by-deno)
- [Effective Deno](https://zenn.dev/uki00a/books/effective-deno)
