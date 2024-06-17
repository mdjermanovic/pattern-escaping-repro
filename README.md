# pattern-escaping-repro

`npm run lint` on ubuntu-latest:

```
Run npm run lint

> pattern-escaping-repro@1.0.0 lint
> eslint src


/home/runner/work/pattern-escaping-repro/pattern-escaping-repro/src/a.js
Warning:   1:1  warning  'foo' is not defined  no-undef

/home/runner/work/pattern-escaping-repro/pattern-escaping-repro/src/b.js
Warning:   1:1  warning  'foo' is not defined  no-undef

✖ 2 problems (0 errors, 2 warnings)
```

`npm run lint` on windows-latest:

```
Run npm run lint

> pattern-escaping-repro@1.0.0 lint
> eslint src


D:\a\pattern-escaping-repro\pattern-escaping-repro\src\{a,b}.js
Warning:   1:1  warning  'foo' is not defined  no-undef

✖ 1 problem (0 errors, 1 warning)
```
