# cfdo.vim

> Wrapper for cdo, cfdo, ldo, lfdo, bufdo, tabdo, argdo, windo

## Deprecated, use https://github.com/FuDesign2008/only.vim instead

## commands

For better performance, before calling `cfdo`/`cdo`/..., the fowlloing status will be set:

```viml
set eventignore=all
let g:ale_fix_on_save=0
let g:ale_enabled=0
```

After calling `cfdo`/`cfo`/..., the status should be restored as before calling.

The fowlloing commands is supported.

| wrapper command | original command |
| :-------------- | :--------------- |
| `Cdo`           | `cdo`            |
| `Cfdo`          | `cfdo`           |
| `Ldo`           | `ldo`            |
| `Lfdo`          | `lfdo`           |
| `Bufdo`         | `bufdo`          |
| `Tabdo`         | `tabdo`          |
| `Argdo`         | `argdo`          |
| `Windo`         | `windo`          |
